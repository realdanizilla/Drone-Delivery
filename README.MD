# Drone Delivery Route Optimization

- [Drone Delivery Route Optimization](#drone-delivery-route-optimization)
  - [Project Objective](#project-objective)
  - [Project Structure and Steps](#project-structure-and-steps)
  - [Tools and Techniques Utilized](#tools-and-techniques-utilized)
  - [Specific Results and Outcomes](#specific-results-and-outcomes)
  - [What I Have Learned From This Project](#what-i-have-learned-from-this-project)

[Back to Top](#)


## Project Objective
This project focuses on optimizing delivery routes for a drone delivery service. Using geographical data of cities within the delivery zone, we aim to determine the most efficient warehouse location by calculating distances and delivery volumes. The goal is to minimize total weekly travel distances for the drones.

[Back to top](#drone-delivery-route-optimization)

## Project Structure and Steps
1. **Data Setup:**
   - Define the origin city (Willowford) and represent other cities graphically with their coordinates along the X and Y axes in kilometers.
   - Store the coordinates (`x_axis` and `y_axis`) and weekly shipment volume (`shipments`) for each city.

2. **Data Preparation:**
   - Combine the data into a `DataFrame` for easier manipulation and visualization.
   - Calculate the distances between each city using vector lengths and store them in a nested list (`distances`).

3. **Warehouse Optimization:**
   - Calculate the total distance traveled by the drone each week if a warehouse is located in a specific city.
     - Double the distances (round-trip) and multiply by the number of shipments per week to get total travel distance for each city.
   - Identify the city with the lowest total travel distance to determine the optimal warehouse location.

[Back to top](#drone-delivery-route-optimization)

## Tools and Techniques Utilized
- **Python**:
  - **pandas** for DataFrame manipulation and visualization.
  - **Vector Calculations**: To determine distances between cities.
  - **Optimization Techniques**: Applied to identify the most efficient city for the warehouse location.

[Back to top](#drone-delivery-route-optimization)

## Specific Results and Outcomes
- A **distance matrix** was created, showing the distances between all cities in the delivery area.
- Calculated weekly delivery distances for each potential warehouse location.
- Identified the city that minimizes total travel distance, optimizing the drone's delivery routes and saving operational costs.

[Back to top](#drone-delivery-route-optimization)

## What I Have Learned From This Project
- **Geospatial Calculations**: Gained experience working with vector-based distances.
- **Data Manipulation with Python**: Strengthened skills in handling data with `pandas`.
- **Optimization Techniques**: Learned how to minimize travel distances using quantitative methods.
- **Decision Making with Data**: Developed competence in using data to determine efficient operational strategies.

[Back to top](#drone-delivery-route-optimization)
