# Azure SQL Performance Optimization (5B+ Rows)

## Overview
This project demonstrates how I optimized Azure SQL performance for a high-volume dataset (5B+ rows) used in enterprise reporting.

## Problem
Reporting queries were taking 20–45 minutes, causing dashboard delays and SLA risks.

## Actions
- Analyzed Query Store for top resource-consuming queries
- Implemented covering and filtered indexes
- Rewrote inefficient joins and subqueries
- Reduced tempdb spills by optimizing sort/hash operations
- Validated improvements with reporting teams

## Results
- Reduced query runtime from 45 minutes → under 3 minutes
- Improved dashboard refresh reliability
- Reduced DTU consumption by ~30%

## Tools Used
Azure SQL • T-SQL • Query Store • Execution Plans

## Repository Structure
/sql — optimized queries, indexing scripts  
/images — screenshots of Query Store, execution plans


