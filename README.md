# 🏨 Hospitality Revenue Intelligence-PowerBI
As a part of practicing codebasics resume challenge, I have worked on this analysis project.

Link to the [Challenge](https://codebasics.io/challenges/codebasics-resume-project-challenge/4) 

Link to [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYWU0ODMzNDktMDI5NC00Yjg5LWFkMWUtNWZkNjQ3OWUyYWE4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

Link to [Presentation Video](https://www.linkedin.com/feed/update/urn:li:activity:7421107551779414016/)

## 🧾 Project Overview

### Problem statement
Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.
Their revenue management team had decided to hire a 3rd party service provider to provide them insights from their historical data.
### Task List
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download section.
-	Create the metrics according to the metric list.
-	Create a dashboard according to the mock-up provided by stakeholders.
-	Create relevant insights that are not provided in the metric list/mock-up dashboard.

### Provided Mock-up Dashboard

<img width="1280" height="800" alt="mock up dashboard_atliq grands" src="https://github.com/user-attachments/assets/a2ea8ed4-7808-4f1d-9991-53e8ea86f9fb" />

## 🔨Tools Used
-	Excel: Data loading and preparation.
-	Power Query: Data cleaning and transformation.
-	DAX (Data Analysis Expressions): Data modeling and calculations.
-	Power BI: Dashboard creation and visualization.


## 🧠Learnings

### 📊Business Metrics
-	Revenue Generated
-	Revenue Realized
-	Revenue Leakage
-	Total Booking
-	Total Capacity
-	RevPar - Revenue Per Available Room
-	Occupancy %
-	ADR (Average Daily Rate)
-	Sellable Room Night (SRN)
-	Daily Sellable Room Night (DSRN)
-	Utilized Room Night (URN)
-	Daily Utilized Room Night (DURN)
-	Booked Room night (BRN)
-	Daily Booked Room night (DBRN)
-	Realization %
-	Cancellation %
- No Show %
-	Average Rate
-	Revenue WOW Change %  , etc

 ### 📚Learning via Example

For a better understanding of business metrics, below is an example of booking rooms in a hotel.:

If there are 110 rooms in a hotel in which:

5 rooms are out of order --> Total Capacity = 105

If 103 rooms are booked --> Total Booking = 103

If 1 room cancelled and 2 has no-show --> Room sold = 100

RevPar = Rev Realized/ Total Capacity

ADR = Rev Realized/ Total Booking

Occ % = (Total Booking/ Total Capacity) *100


### 📅New Visual
•	Learnt to build a new calendar visual using a matrix table, which can be utilized for various analytical purposes. [Article referred](https://www.linkedin.com/pulse/calendar-matrix-syed-ahmed-ali/?trackingId=VgyLpo%2BYxVRs8tD03PXcPQ%3D%3D)


### 📜Concepts

#### 💠Relationship b/w RevPar, Occ% and ADR

	RevPar = ADR * OCC%

  -	High ADR, Low RevPar
      >Rooms are high price but many rooms are empty.
      
      >So, provide discount, promotions and better discount channel.

  - Low ADR, High RevPar
      >Rooms are cheap and mostly filled.
      
      >So, reduce room rates, reduce discount and upsell premium room.

  -	High ADR, High RevPar
      >Room sold are good price, high occupancy.
      
      >So, maintain the strategy.

-	Low ADR, Low RevPar
      >Rooms are cheap, many rooms are sold.
      
      >So, rethink marketing, target new customer segment, improve property position.

#### 💠Types of Pricing

-	Flat Pricing- No change of pricing at all

-	Weekday/ Weekend Pricing- Different price for weekday & different price for weekend

-	Dynamic Pricing- Change price based on competition, occupancy%


#### 💠RevPar & Occ% fluctuates but ADR is flat
	Occ % flactuates because demand for room changes
	ADR is flat because room price are constant (flat pricing)
	RevPar fluctuates because it is same as product of ADR & Occ% 



#### 💠Relationship b/w ADR and Realization%
	-High ADR & High Real%
		higher room rates
		booking convert into staying
		low cancellation & no-show
		So, protect pricing, strengthen relationship with platform, push more inventory

	-High ADR but weak Real%
		Rooms are costly
		But many bookings are cancel/ no-show/ heavily discounted later
		So, check on free cancellation misuse, last minute drops, change policies (like non-refundable plan, advance payment rule)

	-Lower ADR but Stable Real%
		High room price
		Booking rarely cancel
		So, open inventory during low demand, apply upsell strategies (breakfast add-ons, room upgrade, early check-in & late check-out)



## ⭐ Data Model
<img width="1349" height="674" alt="Power BI Desktop 15-01-2026 16_02_08" src="https://github.com/user-attachments/assets/be0a640d-a20d-42fc-8f32-260dc374fa0d" />


## 🎨 Dashboard 

### Overall View

![overall___gif](https://github.com/user-attachments/assets/5d9d308a-fdd0-4b86-a425-22924e99e0b0)



### Daily View
![daily_gif](https://github.com/user-attachments/assets/4aef9200-e76b-405e-93d4-027ed3ba500e)



## 🔎Important Insights

-	Hotels are following flat pricing since ADR is flat but Occ% and RevPar are fluctuating week over week.
-	Week-29 has recorded the highest Revenue among all, which is 164.5M
-	Mumbai contribute the highest Revenue realized as well as Revenue leakage followed by Banglore, Hydrabad, Delhi.
-	Among all the platform, Makeyourtrip got the highest cancellation% (25.03%) and directoffline got the highest no-show% (5.31%)
-	Cancelled booking and No-show are highest in Atliq Palace and Atliq Exotica.
-	Out of the 4 Room class, Elite type got the highest revenue realized as well as highest revenue leakage; whereas Presidential got the highest ADR and realization %  
-	In case of average rating, Atiq Blu (3.9) achieved highest followed by Atliq Palace (3.7)


## ❓ Questions to ask before starting with dashboard

- What all Key Metrics to be kept in dashboard?
- Which one would be more beneficial to look at DSRN or SRN?
- Does Revenue include refund money of no show and cancellation.
- Do you prefer to keep Week on week change (or) Month on month change.
- What is the objective and goals of building this Power-Bi dashboard?
- In what terms, the success of this project will be measured?
- What will be the dead-line of the project?
