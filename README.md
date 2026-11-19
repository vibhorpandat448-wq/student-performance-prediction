# student-performance-prediction
# Sports Staff Scheduling Analysis

## 1. Project Overview
This capstone project analyzes weekly sports academy staff rosters across coaches, trainers, physiotherapists, and support staff to detect scheduling overlaps, workload imbalances, availability conflicts, and understaffed time slots.

## 2. Research Question
How are weekly training sessions distributed across sports staff roles and time slots, and where do scheduling overlaps and staffing gaps occur?

## 3. Dataset
- File: `vibhor_sports_staff_schedule.csv`
- Note: Clearly labelled synthetic sample dataset created for educational demonstration (no real club or personal staff records are used).
- Columns: `schedule_id`, `staff_id`, `role`, `day_of_week`, `time_slot`, `session_type`, `duration_hours`, `available_flag`.

## 4. Key Findings
- Identified 2 double-booked scheduling overlaps where the same staff member was assigned to concurrent sessions in the same day and time slot.
- Flagged 2 availability conflicts where physiotherapists (`STF06`, `STF07`) were scheduled on Sunday despite `available_flag = No`.
- Highlighted staffing gaps during Sunday Midday and Sunday Evening slots (only 1 assigned staff member).
