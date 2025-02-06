# Group Expense Splitter

A **Group Expense Splitter** is a simple, user-friendly calculator designed for splitting costs among multiple people—perfect for travel, group meetups, parties, or any situation where expenses are shared unevenly.

## Overview

When traveling or gathering with friends, managing different expense items (such as meals, drinks, or other activities) can be a hassle. This tool lets you:
- Add and remove participants easily.
- Input expense entries with a clear reason and total amount.
- Adjust individual contributions manually (for example, if one person pays extra for a specific item).
- Automatically calculate each person’s share.
- View detailed logs of all expenses with timestamps, reasons, and per-participant breakdowns.
- Edit or delete expense entries (with confirmation on deletion to prevent accidental removals).
- Export the full expense report in a clean, copyable text format for record-keeping or sharing.

## Features

- **Participant Management**
  - Simple addition and deletion of participants.
  - Displays each participant’s cumulative total expense.
  
- **Expense Entry**
  - Input an expense with a reason and total amount.
  - Select which participants are involved in the expense.
  - Manually adjust individual contributions if needed.
  - Real-time calculation of the remaining amount to be shared evenly.
  
- **Detailed Expense Log**
  - Every expense entry is logged with a timestamp, reason, total amount, and detailed per-participant breakdown.
  - Each log entry includes "Edit" and "Delete" buttons—deletion requires confirmation.
  - Direct editing of expense entries allows on-the-spot correction of amounts or participant distributions.
  
- **Report Export**
  - The expense report can be copied as a structured text report.
  - **Report Format Example:**
    ```
    [기정] 총액: 50,000원
    2025-02-05 10:15 - 밥값 - 30,000원
    2025-02-06 10:20 - 하이볼 - 20,000원

    [준기] 총액: 45,000원
    2025-02-05 10:15 - 밥값 - 30,000원
    2025-02-06 10:20 - 음료 - 15,000원

    [수진] 총액: 40,000원
    2025-02-05 10:15 - 밥값 - 30,000원
    2025-02-06 10:20 - 디저트 - 10,000원
    ```
  - This format lists each participant with their cumulative total followed by each individual expense entry (time, reason, amount).


## Usage

1. **Add Participants**
   - Enter a participant's name in the left sidebar and click **"추가"**.
   - The participant list will update with the new entry along with their current total.

2. **Add an Expense Entry**
   - In the expense section on the right, enter the expense **사유** (e.g., "밥값") and **총 금액** (e.g., "38000").
   - Use the **전체 선택** button to quickly select all participants or select individual participants manually.
   - For each selected participant, adjust the manual contribution if necessary (e.g., 추가 금액을 직접 입력).
   - The calculated shared cost per participant is displayed in real-time.
   - Click **"정산 항목 추가"** to record the expense.

3. **Manage the Expense Log**
   - The **세부 내역서** displays all expense entries with time, reason, and per-participant amounts.
   - Use the **수정** button to edit an entry (a modal window allows direct adjustment of amounts or participants).
   - Use the **삭제** button to remove an entry. A confirmation dialog ensures accidental deletion is avoided.

4. **Export the Expense Report**
   - Click the **정산서 복사** button (located in the left sidebar) to copy a text version of the complete expense report.
   - The report is formatted by participant with each entry listed in the specified format, ready for sharing or record-keeping.

## Installation

1. **Clone or Download the Repository:**

   ```bash
   git clone https://github.com/yourusername/group-expense-splitter.git
