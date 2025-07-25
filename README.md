# DailyStockPredictor: Inventory Optimization via ML Forecasting 📦📊

SmartStock is a machine learning project that predicts **daily product demand** based on historical retail transactions. It helps e-commerce businesses optimize warehouse inventory, reduce stockouts, and improve supply chain planning.

This project uses data from a UK-based online retail store (UCI/Kaggle dataset) and implements **time series regression** models to forecast next-day sales quantity per SKU.

---

## 📈 Problem Statement

> "How many units of each product should be stocked tomorrow?"

Warehouse space is expensive. Understocking leads to missed sales, and overstocking leads to waste.  
This project uses machine learning to **forecast daily sales quantity**, helping retailers strike the right balance.

---

## 🧠 Features Used

| Feature | Description |
|--------|-------------|
| `StockCode` | Product identifier |
| `Quantity` | Number of items sold |
| `InvoiceDate` | Timestamp of purchase |
| `UnitPrice` | Price per unit |
| `Revenue` | Derived: Quantity × UnitPrice |
| `Day`, `Month`, `Weekday` | Extracted from InvoiceDate |

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Google Colab
- Excel dataset from Kaggle


---

## 🧪 Models Trained

- **XGBoost Regressor**
- Optional: CatBoost (planned)

---

## 📊 Evaluation Metrics

- RMSE (Root Mean Square Error)
- MAPE (optional)
- Visual inspection of prediction vs. actual trends

---

## 📦 Dataset

UK-based online retail dataset originally from UCI repository and hosted on Kaggle:  
🔗 [Online Retail Dataset on Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)

---

## 🚀 How to Run

1. Upload the dataset (`data.xlsx`)
2. Run `e-commerce-sales-forecast.ipynb` in Google Colab
3. Visualize predictions and evaluate inventory suggestions

---

## 📌 Results

- Achieved RMSE of ~10 units per product-day
- Able to flag fast-moving SKUs for proactive restocking
- Insights generated for optimal daily inventory planning

---

## 👨‍💻 Author

**Ojasvi Pathania**  
🔗 [LinkedIn](https://www.linkedin.com/in/ojasvi-pathania) | 🐙 [GitHub](https://github.com/ojasvi-23)

---

## 📢 License

This project is open-source for learning and demonstration purposes. Commercial use of the dataset is prohibited under Kaggle/UCI terms.


