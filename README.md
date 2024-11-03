# Baby Name Project

## Overview

The Baby Name Project is a creative exploration developed by Ani, Steph, and Annie, focusing on the intersection of data visualization and participatory mapping. This project utilizes NYC Open Data to analyze trends in baby names, expanding the dialogue around identity and culture in urban environments. Through an interactive constellation of names, we invite users to engage with the data, discover connections, and reflect on the stories behind each name.

By leveraging diverse media and formats, our project seeks to transcend traditional gallery spaces, encouraging community participation and exploration in both physical and digital realms. The constellation not only visualizes name popularity but also provides insights into demographic patterns, fostering a deeper understanding of how names shape and are shaped by cultural narratives over time.

## Features

- **Interactive Visualization**: A star-like display of baby names that changes based on user input.
- **Search Functionality**: Users can search for names and see related data.
- **Yearly Trends**: Clickable buttons that show the top baby names for selected years.
- **Dynamic Summaries**: Provides quick insights about name popularity and age estimates.

## Getting Started

### Prerequisites

Ensure you have the following tools installed:

- A modern web browser (Chrome, Firefox, etc.)
- A local server setup (optional for running HTML directly)

### Running the Project

1. Clone the repository or download the HTML file.
2. If you're using a local server, place the HTML file and the CSV file (`Popular_Baby_Names_20241011.csv`) in the server's root directory.
3. Open the HTML file in your browser.

## Code Structure

- **index.html**: The main HTML file containing the structure and script for the visualization.
- **Popular_Baby_Names_20241011.csv**: CSV file containing the baby names data.

## Key Components

### HTML and CSS

- **SVG Element**: The main area where the constellation of names is rendered.
- **Styling**: CSS styles for stars, lines, and labels to enhance user experience.

### JavaScript (D3.js)

- **Data Loading**: Uses D3.js to load the CSV data.
- **Visualization Logic**: Implements the constellation layout, with dynamic updating based on user interactions.
- **Syllable Counting**: Basic function to estimate the number of syllables in names.

### Interaction Features

- **Mouse Events**: Displays name labels on hover.
- **Year Buttons**: Clickable years that update the visualization with the top names for that year.
- **Search Box**: Filters names based on user input and updates the summary.

## Contributing

Contributions are welcome! If you'd like to help improve the project:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request with a description of your changes.

## License

This project is open source and available under the MIT License.

## Acknowledgments

Thanks to the D3.js community for providing powerful tools for data visualization.
