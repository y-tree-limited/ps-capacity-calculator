**PLATFORM SUPPORT RESOURCE CALCULATOR**

A purpose-built capacity planning tool for Platform Support.

Unlike standard engineering capacity planners--which assume developers have flat "delivery time"--this tool accounts for the specific interruptions that kill Support productivity: physical walk-ups, rotation duties, and the "context switching tax."

-----

**THE PROBLEM**

Standard capacity spreadsheets usually fail for Support teams because they don't capture the binary nature of our work:

The "Office Anchor" Tax: If you are physically in the office, you are getting tapped on the shoulder, even if you aren't "on duty."

Binary Availability: You are either "On Rota" (interrupted every 15 mins) or "Off Rota." Percentages don't reflect this reality.

Invisible Work: Mentoring, ad-hoc training, and "quick fixes" often eat up 20% of a Senior Engineer's week, but go untracked.

-----

**FEATURES**

This HTML-based calculator provides a realistic "Deep Work" availability score by factoring in:

Granular Commitment Control: Adjust hours for Support Rota, Management, and Mentorship independently.

The "Walk-up Tax": Automatically calculates lost hours based on how many days per week the engineer is physically in the office.

Safety Buffers: Includes a configurable "Slack Time" (default 15%) to prevent 100% utilization booking (which always leads to burnout).

Visual Feedback: Instant red/green feedback loops to show when a team member is over-committed.

-----

**HOW TO USE**

Download the "resource_calculator.html" file.

Open it in any modern web browser (Chrome, Edge, Safari).

Input your details:

Contract Hours (e.g., 35)

Office Days: How many days are you physically present?

Meetings: Average weekly meeting load.

Select Commitments: Tick the boxes that apply to you this week (Support Rota, Project Owner, etc.).

Adjust Hours: Use the up/down arrows to fine-tune the hours for each commitment based on reality.

-----

**THE LOGIC**

The tool uses the following baseline logic (customisable in the UI):

Standard Shrinkage: Fixed 2.5h / week
(Why? Covers breaks, Slack triage, and HR admin.)

Walk-up Tax: 1h per day in office
(Why? Accounts for "drive-by" interruptions and physical distractions.)

Support Rota: Base 20h + Walk-up Tax
(Why? If you are on tickets, you cannot do deep work.)

Safety Buffer: 15% of Total Hours
(Why? Industry standard to handle unexpected sickness or emergencies.)

-----

**INSTALLATION**

No installation required. This is a standalone, client-side HTML file.

Clone the repo.

Double-click "resource_calculator.html".

-----

**LICENSE**

Feel free to modify the logic values in the script tag to match your specific team's operating model.
