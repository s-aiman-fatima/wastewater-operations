# Wastewater Operations - Unit Converter

## Overview
This project provides a **Wastewater Operations Unit Converter** that allows users to easily convert various units related to wastewater operations. Additionally, it includes a **Lbs/Day Calculation** tool to calculate pollutant load in wastewater.

## Features
- **Unit Converter**: Supports multiple unit conversions such as MGD to GPH, PSI to Bar, Feet to Meters, and more.
- **Lbs/Day Calculation**: Calculates the pollutant load in lbs/day using concentration (mg/L) and flow (MGD).

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS**: Styling and layout.
- **JavaScript**: Handles unit conversion and calculation logic.

## Usage

### 1. Unit Conversion
1. Select a conversion type from the dropdown menu.
2. Enter a numeric value in the input field.
3. Click the "Convert" button to get the result.

### 2. Lbs/Day Calculation
1. Enter the concentration in mg/L.
2. Enter the flow in MGD.
3. Click "Calculate" to get the pollutant load in lbs/day.

## Conversion Formulas
Some key conversion formulas used in the project:

- **MGD to GPH**:  
  \[
  \text{GPH} = \text{MGD} \times 1,000,000
  \]

- **MGD to GPM**:  
  \[
  \text{GPM} = \text{MGD} \times 6944.44
  \]

- **Lbs/Day Calculation**:  
  \[
  \text{Lbs/Day} = \text{Concentration (mg/L)} \times \text{Flow (MGD)} \times 8.34
  \]

## Installation
No installation is required. Simply open the `index.html` file in a web browser.

## Future Enhancements
- Add more unit conversions.
- Improve UI design for better user experience.
- Implement a history log of conversions.

## License
This project is open-source and free to use.
