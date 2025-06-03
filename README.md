Plastic WastePulse App - Java Concept Overview
 Overview
 Plastic WastePulse is a Java-based application designed to analyze and visualize global plastic waste
 statistics using datasets like Jambeck et al. (2015). The goal is to provide insights into country-level plastic
 waste generation and mismanagement trends, supporting SDG 13: Climate Action.
 Module 1: Data Processing
 1. Data Processing Module (PlasticDataProcessor.java)- Purpose: Load and parse the CSV dataset.- Features:
  - Read CSV data into Java objects.
  - Extract data for specific countries.
  - Aggregate and rank based on plastic waste metrics.- Example Methods:
  - loadData(String filePath)
  - getCountryData(String countryName)
  - getTopPlasticProducers(int n)
  - getMismanagedPercent(String country)
 Module 2: Data Analysis
 2. Analysis Module (PlasticAnalyzer.java)- Purpose: Analyze trends and perform statistical analysis.- Features:
  - Calculate average plastic waste per person.
  - Rank countries by total/mismanaged plastic waste.
  - Compare data across countries.- Example Methods:
Plastic WastePulse App - Java Concept Overview
  - getAverageWastePerPerson()
  - rankCountriesByWaste()
  - compareTwoCountries(String c1, String c2)
 Module 3: CLI Representation
 3. Representation Module (PlasticStatsCLI.java)- Purpose: Display results in the console (CLI).- Features:
  - Show top generators/mismanagers of waste.
  - ASCII-style graphs for data visualization.
  - Comparative country stats.- Output Example:
  Top 3 Plastic Waste Generators:
  1. China - 60M tons
  2. USA   - 38M tons
  Mismanaged Waste:
  India - 86%
  USA   - 2%
 Module 4: Application Menu
 4. Application Menu (Main.java)- Purpose: Provide a user-friendly command-line menu.- Features:
  - Prompt user to load data file.
  - Options to view top countries, compare stats, or exit.- Sample Menu:
  1. Load Dataset
Plastic WastePulse App - Java Concept Overview
  2. Show Top Waste Generators
  3. Show Mismanaged Waste Stats
  4. Compare Two Countries
  5. Exit
 Summary & SDG 13 Impact
 Benefits:- Modular and simple for Java learners.- Uses real-world data for meaningful insights.- Encourages awareness around plastic waste and sustainability.- Aligned with SDG 13 by showcasing waste management issues.
 The app can be expanded into GUI or integrated with visualization libraries in the future
