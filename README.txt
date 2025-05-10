Call Center Optimization for United Airlines
===========================================

Problem Statement
-----------------
As United Airlines continues its journey to become the best airline in aviation history, delivering world-class customer service remains a top priority. One critical aspect of this mission is optimizing call center operations, which play a vital role in resolving customer issues efficiently.

Key challenges:
- Reducing Average Handle Time (AHT) - total time agents spend handling a call
- Improving Average Speed to Answer (AST) - time customers wait in queue before an agent responds

Project goals:
1. Enhance customer satisfaction by reducing resolution times
2. Decrease escalations by improving self-service options
3. Boost operational efficiency through better resource allocation

Background
---------
United Airlines uses a mix of human agents and IVR (Interactive Voice Response) systems to handle customer interactions. Optimizing these systems is crucial for:
- Reducing AHT without compromising service quality
- Lowering AST to improve customer experience

Key Metrics
-----------
Average Handle Time (AHT):
Formula: Total Handle Time / Total Number of Calls
Impact: Measures efficiency in resolving calls

Average Speed to Answer (AST):
Formula: Total Waiting Time / Total Number of Calls
Impact: Reflects customer wait time

Objectives & Deliverables
------------------------
1. Identify Drivers of Long AHT & AST
   - Analyze agent performance, call types, sentiment
   - Compare AHT between most/least frequent call reasons

2. Reduce Unnecessary Agent Escalations
   - Detect recurring self-solvable issues in transcripts
   - Propose IVR improvements to automate resolutions

3. Improve Call Reason Categorization
   - Uncover patterns in call reasons
   - Enhance call routing efficiency

Data Dictionary
---------------
call_id - Unique identifier for each call
customer_id - Unique identifier for the customer
agent_id - Unique identifier for the agent
call_start_datetime - When call started
agent_assigned_datetime - When agent answered
call_end_datetime - When call ended
customer_name - Name of customer
mp_status - Loyalty tier (NaN, 0-5)
agent_tone - Agent's tone (neutral/positive/etc.)
customer_tone - Customer's tone
average_sentiment - Conversation sentiment score
silence_percent_average - Average silence duration
call_transcript - Full conversation text
primary_call_reason - Tagged reason for call

Expected Outcomes
----------------
- Actionable insights to optimize AHT & AST
- IVR redesign recommendations
- Improved call routing strategies

Datasets:
- calls.csv
- customers.csv
- reason.csv
- sentiment_statistics.csv
- test.csv
