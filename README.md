# AirBnb Vacation Rental Market Analysis in Valencia

![Project Image](https://github.com/pedrocaravaca/inversion-turistica-valencia/blob/main/Datos/Images/portada.jpg)

---

## **Introduction**
The client is a Real Estate company that invests in large cities by buying properties to later rent them out as vacation apartments.

The managers have decided to invest in Valencia and are interested in analyzing the data that the sector leader AirBnb makes public. The objective is to identify the types of properties with the greatest commercial potential for vacation rentals.

As a primary deliverable, the management expects to receive:
- Typologies of properties that the valuation team should prioritize.
- Main neighborhoods or geographic areas to focus on.

---

## **Objectives**
Analyze publicly available data to gain insights into the Valencia rental market and guide the valuation team’s research, especially in terms of:
- **Rental prices**
- **Occupancy levels**
- **Purchase prices**

---

## **Project Results**
1. **Identified 10 neighborhoods with high investment potential:**
   - **Low Investment**: CAMI REAL, MORVEDRE.
   - **Medium Investment**: FAITANAR, PENYA-ROJA.
   - **Medium-High Investment**: CIUTAT UNIVERSITARIA, BENIFERRI.
   - **High Investment**: MAHUELLA-TAULADELLA, LA ROQUETA.

2. **Focus on properties with the following characteristics:**
   - **Size**: 70 m², avoiding smaller properties of 50 m² or large ones of 150 m².
   - **Bedrooms**: Two bedrooms are preferred over three as they maintain the same occupancy rate but are more cost-effective.
   - **Guests**: Properties suitable for 4-5 guests with 3-4 beds have the highest occupancy rates.

3. **Avoid prioritizing proximity to points of interest:**
   - No significant impact on rental prices.
   - Properties further from points of interest often have a lower purchase price.

4. **Prioritize full apartment rentals:**
   - Full apartment rentals have better income potential compared to shared or private rooms.

5. **Opportunities for long-term rentals:**
   - **Medium Occupancy - High Rent**: EL PLA DEL REI.
   - **High Occupancy - High Rent**: CARPESA (limited data available; not considered optimal).

6. **Investment strategies based on size:**
   - **Medium Occupancy - Medium Investment**: Prioritize 70 m² properties over 90 m² ones as they offer similar occupancy rates but are more affordable.
   - **High Occupancy - High Investment**: Avoid 150 m² properties and focus on 120 m² ones, which are more economical (~€60,000 cheaper on average) and have the highest occupancy rates.

---

## **Project Structure**

📁 **Datos**: Contains the datasets for the project.  
📁 **Imagenes**: Contains images used in the analysis and documentation.  
📁 **Notebooks**: Jupyter notebooks documenting the entire project process:  
- `01_Diseño del proyecto.ipynb`: Initial project design.
- `02_Analisis de ficheros y preparacion del caso.ipynb`: Analysis and preparation of the case files.
- `03_Creacion del Datamart Analitico.ipynb`: Creation of the analytical datamart (loading, unifying data, applying data quality processes).
- `04_Preparacion de datos.ipynb`: Feature engineering processes.
- `05_Analisis e Insights.ipynb`: Exploratory data analysis, insights, and recommendations.
- `06_Comunicacion de resultados.ipynb`: Executive summary using McKinsey's Exhibits methodology.

---

## **Instructions**

1. Unzip the file `airbnb.rar` into the `Datos` folder.
2. Update the `project_path` variable in the notebooks to match the location where you replicated the project.

---

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/pedrocaravaca/airbnb-market-analysis.git
   cd airbnb-market-analysis

