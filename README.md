# Implemented-merge-sort-in-python
# merge-sort-python

A compact, educational implementation of **Merge Sort** in Python.  
This repository demonstrates the classic divide-and-conquer merge sort algorithm implemented in-place on Python lists.

## Contents
- `merge_sort.py` — the merge sort implementation (in-place).
- `README.md` — this file.
- `tests/` — suggested place for unit tests (not included by default).

## Why this repo?
This is a learning-focused implementation for students and beginners who want to:
- See the merge step implemented clearly.
- Understand how indices are used instead of slicing repeatedly.
- Experiment by adding type hints, tests, or benchmarking.

## Algorithm overview
Merge sort works by:
1. Recursively splitting the list into two halves until each part has size ≤ 1.
2. Merging the halves back together in sorted order.

Time complexity: **O(n log n)** (best, average, worst).  
Space complexity: **O(n)** due to temporary lists (`left_part`, `right_part`) created during the merge.

## Usage

Save your implementation as `merge_sort.py` and run:

```bash
python merge_sort.py
