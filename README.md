# 🚛 Logistics & Inventory Performance Monitor

📊 **A Data-Driven Approach to Operational Efficiency in Supply Chain Management**

---

## 🔍 Overview

In today’s increasingly complex and competitive supply chain landscape, organizations require timely, data-driven insights to remain agile, reduce waste, and optimize end-to-end operations. The **Logistics & Inventory Performance Monitor** is a comprehensive Power BI dashboard solution developed to meet this need by offering real-time visibility into logistics, supplier efficiency, inventory levels, shipping costs, and defect rates. Built on a robust star schema data model and powered by advanced DAX calculations, the solution transforms raw transactional data into actionable intelligence that supports smarter decision-making at all levels.

At the core of this project lies a single fact table, `FactSupplyChain`, which captures measurable data across logistics, inventory, production, and sales dimensions. This table is enriched through carefully modeled dimension tables—`DimSupplier`, `DimProduct`, `DimLocation`, `DimCarrier`, `DimCustomer`, and `Calendar`—enabling flexible slicing and dicing across multiple attributes. The model also incorporates calculated metrics such as shipping cost per unit, stock turnover rate, return rate proxy, and lead time averages, all of which serve as key performance indicators (KPIs) in the dashboard.

---<img width="1571" height="890" alt="Data Modelling updated" src="https://github.com/user-attachments/assets/316cbfcc-1efe-47ea-b14a-76cde8cf4ab5" />


## 🟦 Page 1 – Revenue and Sales Overview

The first page of the dashboard serves as a high-level overview of commercial performance. It provides decision-makers with quick insight into revenue generation, customer behavior, supplier contributions, and regional performance. The page begins with essential KPIs, including **Total Revenue ($52.92K)**, **Total Products Sold (4,840)**, **Average Shipping Cost ($529.25)**, **Average Product Price ($49.46)**, and **Average Lead Time (20.80 days)**. These figures set the baseline for evaluating the efficiency and profitability of supply chain activities.

A supplier performance bar chart identifies which suppliers are contributing most to overall revenue, highlighting Supplier 1 as a consistent top performer. Complementing this, a donut chart displays revenue split by customer demographics, revealing that Non-binary and Female segments generate the highest revenue. A geospatial map provides visibility into top revenue-generating locations using latitude and longitude data, covering key cities such as Chennai, Kolkata, Mumbai, and Delhi.

Further insights include a SKU status donut chart, which compares sales volume between products classified as "Optimal" and those considered "Critical." This is useful for aligning revenue generation with inventory health. Another chart explores whether certain suppliers are driving more sales than others, giving supply chain managers an evidence-based understanding of supplier impact on product distribution and profitability. Altogether, Page 1 sets the foundation for revenue-focused decision-making while tying sales performance directly to supplier and customer dynamics.
<img width="1472" height="819" alt="Executive summary Page1" src="https://github.com/user-attachments/assets/b132bc05-c3d3-4a92-b4cb-5deb04e578b6" />

---

## 🟨 Page 2 – Inventory and Stock Management

The second page of the dashboard dives deeper into stock levels, inventory turnover, and supplier delivery performance. The top of the page features refreshed KPIs: **Order Quantity (1.54K)**, **Stock Level (4,840)**, **Stock Turnover Rate (31.75)**, and **Average Lead Time (20.80 days)**. These figures offer a lens into how well the organization is managing its inventory flow and supplier responsiveness.

A bar chart highlights stock levels by product type, with Skincare being the most stocked, followed by Haircare and Cosmetics. This sets the stage for evaluating potential overstock or understock conditions. A subsequent bar chart visualizes stock turnover by category, showing Skincare as the most efficient and Cosmetics as the least, suggesting targeted action to improve inventory movement.

Supplier delivery speed is visualized through a bar chart ranking average lead times. Supplier 1, despite being a top revenue generator, has the longest delivery time, whereas Supplier 3 stands out for its delivery efficiency. A donut chart reveals how stock is distributed across key locations, offering a snapshot of potential geographic imbalances or strategic stock placement.

A detailed matrix compares all five suppliers across key metrics: **Total Revenue**, **Order Quantity**, **Stock Level**, **Stock Turnover Rate**, and **Lead Time**. This comparative view helps in identifying best-in-class suppliers and those that may need improvement. Page 2 equips supply chain leaders with the insights needed to reduce stockouts, improve turnover, and hold suppliers accountable to service levels.
<img width="1490" height="821" alt="Executive summary Page2" src="https://github.com/user-attachments/assets/9fae3911-1c0f-4239-bff7-8fb0ff929d69" />

---

## 🟩 Page 3 – Logistics and Shipping Performance

The third and final page of the dashboard focuses on shipping cost analysis, carrier efficiency, and product quality control. KPIs highlighted include **Defect Rate (227.72%)**, **Total Shipping Cost ($529.25)**, **Shipping Cost per Unit ($34.44)**, and **Total Cost ($58.21K)**. These metrics provide a performance baseline for logistics managers focused on reducing waste, controlling costs, and improving delivery quality.

Visuals on this page start with a breakdown of shipping costs by product type, where Skincare again leads as the most expensive to ship. A treemap visual identifies Carrier B as the top contributor to shipping costs, followed by Carriers C and A. These insights are key for evaluating carrier contracts and determining if shipping spend aligns with performance.

A supplier-level bar chart evaluates which suppliers are incurring the highest shipping costs, which can reveal opportunities for freight consolidation or alternative routing. Another bar chart maps shipping cost by location, showing Chennai and Kolkata as the most expensive locations to service, potentially due to distance or carrier choices.

A data matrix presents a side-by-side view of supplier performance on total units shipped, shipping cost, and cost per unit, providing clarity on shipping efficiency. Finally, a return rate proxy based on the proportion of high defect products is used to estimate potential product returns—an important quality indicator that helps flag problem areas before they impact customer satisfaction.

Page 3 rounds out the analytics story by providing logistics leaders with a clear view of where money is being spent, how carriers are performing, and what quality risks exist in the shipping process.
<img width="1467" height="827" alt="Executive summary Page3" src="https://github.com/user-attachments/assets/76ef3d93-29dd-4967-b057-bf52e2b09c2e" />

---

## 📌 Conclusion

The **Logistics & Inventory Performance Monitor** is a complete, data-driven solution for supply chain optimization. With its unified data model, interactive visualizations, and strategic KPI coverage, the dashboard provides stakeholders with a single source of truth across logistics, inventory, and supplier performance. Whether used for quarterly business reviews, weekly operations meetings, or daily performance monitoring, this Power BI dashboard empowers users to make informed decisions, reduce costs, and drive continuous improvement across the supply chain.

---

> 🔒 *Note: All data used in this dashboard is simulated for educational or demonstration purposes only.*

