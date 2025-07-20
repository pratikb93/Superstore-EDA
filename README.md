Superstore Sales Analysis
=========================

A complete end-to-end exploratory data analysis (EDA) project using Python and Pandas on the popular Superstore dataset.

---

**Dataset**
- Source: [Superstore Dataset (Kaggle / Tableau)](https://www.kaggle.com/datasets)
- Contains sales data across 4 years including:
  - Orders, Products, Categories
  - Regions, Countries, Cities
  - Profit, Sales, Discounts, and Shipping data

---

**Objectives**
- Understand regional and category-level performance
- Identify profit drivers and loss-makers
- Analyze seasonal sales trends
- Suggest data-backed business decisions

---

**Tools Used**
- **Python**: Data wrangling and analysis
- **Pandas**: Data manipulation
- **Matplotlib & Seaborn**: Visualizations
- **Jupyter Notebook**: Code + Narrative

---

**Key Insights**

1. **Seasonal Pattern**  
   - Q4 (Oct-Dec) consistently outperforms all other quarters in sales.  
   _Strategy: Focus marketing/promotions in Q4._

2. **U.S. Market Dominance**  
   - US drives ~84% of total profits.  
   _Risk: Over-dependence on a single region._

3. **Discounts Hurt Profitability**  
   - Beyond 20% discount, profits start declining sharply.  
   _Suggestion: Cap promotional discounts._

4. **Sub-category Watch**  
   - **Copiers & Phones** are highly profitable.  
   - **Tables & Bookcases** generate consistent losses.  
   _Strategy: Reprice/rethink loss-making segments._

5. **Country Performance**  
   - Canada & Germany are next in profit after the U.S.  
   _Potential: Grow presence in under-tapped international markets._

---

**Files**

- `Superstore_EDA.ipynb` – Main analysis notebook
- `top10.png`, `SalesvsProfit.png`, etc. – Visual assets
- `README.md` – Project summary