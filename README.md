# 🌍 TravelTide – Behavioral Segmentation & Perk Recommendation

**TravelTide** is a data analytics project that segments customers based on behavior and demographics to determine the most attractive travel perks for each group.  
It combines traditional indexing, clustering algorithms, and demographic profiling to enable data-driven personalization in travel offers.

---

## ✨ Key Features

- 📊 Behavioral index calculation (Hotel Hunter, Cancellation Rate, etc.)
- 🤖 KMeans clustering to identify user segments
- 📌 Custom perk recommendation logic based on index performance
- 👥 Demographic profiling (age, gender, marital, parental status)
- 📈 Visualization in Tableau for clear stakeholder communication
- 🎯 Actionable segmentation and personalization strategy

---

## 🧠 Project Objectives

- Understand behavioral patterns among travel platform users
- Identify which perks appeal most to different types of users
- Use ML algorithms (clustering) and statistical logic to validate segmentation
- Present clear, interpretable insights using visual storytelling

---

## 🧩 Techniques & Tools

- **SQL** – data extraction & cleaning  
- **Python** – data manipulation, ranking logic, clustering (KMeans)  
- **Tableau** – visualization of clusters and demographics  
- **Canva** – final presentation design  
- **Jupyter Notebook** – analysis workflow

---

## 🛠 Indexes Used

Each customer is scored on key behavioral metrics:

- 🏨 **Hotel Hunter Index** – interest in hotel perks
- 💼 **Average Bags Index** – baggage-related patterns
- ❌ **Cancellation Rate** – reliability & flexibility
- 💰 **Bargain Hunter Index** – sensitivity to discounts
- 🧳 **Combined Booking Index** – preference for bundled perks
- 🔥 **Session Intensity Index** – engagement level

Customers were then **ranked across indexes**, and matched with the perk most relevant to their profile. This was followed by **unsupervised clustering** (KMeans) to validate segment separation.

---

## 📋 Summary of Clusters (Example)

| Cluster | Demographic Highlight          | Behavior Insight                    | Suggested Perk                   |
|---------|--------------------------------|-------------------------------------|----------------------------------|
| 0       | Mostly male, no kids           | Reliable, moderate discount usage   | No Cancellation Fees             |
| 1       | Female, high baggage + deals   | Frequent travelers, value services | Free Checked Bag                 |
| 2       | Married, older                 | Hotel-focused, price-sensitive      | Free Hotel Meal                  |
| 3       | Young, discount chasers        | High activity, low conversion       | Exclusive Discount               |
| 4       | Single, very deal-oriented     | Package deal hunters                | 1 Free Night Hotel with Flight   |

---

## 📁 Project Structure

```bash
TravelTide/
├── data/                   # Raw & processed datasets
├── notebooks/              # Jupyter Notebooks with analysis
├── scripts/                # Python scripts (index logic, clustering)
├── dashboards/             # Tableau story (link below)
└── README.md


## Resources: 
* 📊[ [Dashboards Story](https://public.tableau.com/app/profile/alexandra.meshi/viz/TravelTide_16935125418790/TravelTide) in Tableau

* 🎥 [Video Presentation](https://www.canva.com/design/DAFtYDpuErE/TiREg8ncRvrsOX7qcu45zA/view?utm_content=DAFtYDpuErE&utm_campaign=designshare&utm_medium=link&utm_source=editor)

* 🖼️ [Presentation Slides](https://www.canva.com/design/DAFtYDpuErE/Y0ZKZGRWpbUigcby1MRhdw/edit?utm_content=DAFtYDpuErE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

