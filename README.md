# SQL Notes

My SQL learning journey as a BS Data Science student at PUCIT.
Goal: get comfortable with SQL for data analyst / data science internships.

## Database used
Chinook sample database (a digital music store: customers, invoices, tracks).
Download it from the official Chinook GitHub repo (not stored here, the file is large).

## Tools
- SQLBolt (learning)
- DB Browser for SQLite (practice on Chinook)
- LeetCode SQL 50 (daily problems)

## Overall progress
- [ ] Week 1: SELECT, WHERE, ORDER BY, GROUP BY, HAVING
- [ ] Week 2: JOINs, subqueries, CTEs, window functions

## Folder structure
- `week1/chinook_queries.sql`: my Chinook queries, each with a question and a plain-English comment
- `week1/week1-notes.md`: weekly reflection

---

# Week 1 Checklist (Nov 2 - Nov 8, 2026)

## Monday: Setup and SELECT basics
- [ ] Install DB Browser for SQLite
- [ ] Download Chinook and open it; look at the Customer, Invoice, Track tables
- [ ] SQLBolt lessons 1-3 (SELECT, numeric filters, text filters)
- [ ] Write 5 simple queries on Chinook (e.g. customers from Canada, tracks longer than 5 minutes)
- [ ] Create this repo and commit the README
- [ ] Explain one query out loud (5 min)

## Tuesday: Sorting, DISTINCT, LIMIT
- [ ] SQLBolt lessons 4-5 (DISTINCT, ORDER BY, LIMIT) + review exercise
- [ ] Understand NULL: why `IS NULL` works and `= NULL` doesn't
- [ ] 3 LeetCode Easy problems
- [ ] 5 more queries on Chinook
- [ ] Commit queries to `week1/chinook_queries.sql`
- [ ] Explain one query out loud (5 min)

## Wednesday: Aggregates
- [ ] SQLBolt lesson 10 (COUNT, SUM, AVG, MIN, MAX)
- [ ] Chinook: total revenue, average invoice, most expensive track
- [ ] 3 LeetCode Easy problems
- [ ] Commit queries
- [ ] Explain one query out loud (5 min)

## Thursday: GROUP BY and HAVING
- [ ] SQLBolt lesson 11 (GROUP BY, HAVING)
- [ ] Learn: WHERE filters rows before grouping, HAVING filters groups after
- [ ] Chinook: revenue per country, invoices per customer, countries with more than $50 in sales
- [ ] 3 LeetCode problems
- [ ] Commit queries
- [ ] Explain one query out loud (5 min)

## Friday: Mixed practice
- [ ] 4 LeetCode Easy problems, 20 minutes each before looking at any solution
- [ ] For every wrong problem, write one line on what I misunderstood
- [ ] Commit those notes

## Saturday: Mini project and review (3-4 hrs)
- [ ] Write 10 business questions about Chinook
- [ ] Answer each with a query
- [ ] Add a plain-English comment above each query (what it does + what the result means)
- [ ] Add a one-line result under each query
- [ ] Commit everything to `week1/chinook_queries.sql`
- [ ] Update this README

## Sunday: Light day (30 min)
- [ ] Record a 2-minute voice note explaining GROUP BY to a non-technical friend
- [ ] Count my filler words ("um", "like")
- [ ] Write `week1/week1-notes.md`: what I learned, what confused me, what surprised me, WHERE vs HAVING in my own words
- [ ] Commit the notes

## Sunday self-check (do without help)
- [ ] Find the top 5 customers by spend
- [ ] Count invoices per country and keep only countries with more than 10
- [ ] Explain WHERE vs HAVING in one sentence

If any box is unchecked, repeat that topic before starting Week 2.
