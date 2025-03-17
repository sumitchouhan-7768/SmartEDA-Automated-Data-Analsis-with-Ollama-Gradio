# SmartEDA: Automated Data Analysis with Ollama and Gradio

**SmartEDA** is an automated data analysis tool that leverages the power of **Ollama** (a language model) and **Gradio** (a user interface library) to provide an intuitive and interactive way to analyze datasets. This project is designed to simplify exploratory data analysis (EDA) by automating common tasks and enabling natural language interactions with your data.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Contributing](#contributing)
8. [License](#license)

---

## Overview

SmartEDA combines the capabilities of **Ollama** (a language model for natural language processing) and **Gradio** (a framework for building user interfaces) to create an automated data analysis pipeline. Users can upload datasets, ask questions in natural language, and receive insights, visualizations, and summaries without writing code.

---

## Features

- **Automated Data Analysis:** Perform exploratory data analysis (EDA) with minimal user input.
- **Natural Language Queries:** Interact with your data using natural language (e.g., "Show me the distribution of age").
- **Interactive Visualizations:** Generate charts, graphs, and summaries dynamically.
- **User-Friendly Interface:** Built with Gradio for an intuitive and interactive experience.
- **Customizable Workflow:** Easily extend the tool to support additional datasets and analysis tasks.

---

## Technologies Used

- **Ollama:** A language model for natural language understanding and generation.
- **Gradio:** A library for building quick and easy user interfaces for machine learning models.
- **Pandas:** For data manipulation and analysis.
- **NumPy:** For numerical computations.
- **Matplotlib/Seaborn:** For data visualization.
- **Scikit-learn:** For statistical analysis and machine learning tasks (optional).

---

## Installation

To set up SmartEDA locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sumitchouhan-7768/SmartEDA-Automated-Data-Analysis-with-Ollama-Gradio.git
   cd SmartEDA-Automated-Data-Analysis-with-Ollama-Gradio
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up Ollama:**
   - Install Ollama (if not already installed):
     ```bash
     pip install ollama  # Replace with the correct installation command
     ```
   - Configure Ollama with your API key or local model (if required).

5. **Run the application:**
   ```bash
   python app.py
   ```

---

## Usage

1. **Launch the Gradio Interface:**
   - After running `app.py`, open the provided Gradio interface in your browser.

2. **Upload Your Dataset:**
   - Upload a CSV or Excel file containing your dataset.

3. **Ask Questions:**
   - Use natural language to ask questions about your data (e.g., "What is the average age?" or "Show me a histogram of sales").

4. **View Results:**
   - The tool will generate visualizations, summaries, and insights based on your queries.

---

## Configuration

You can customize SmartEDA by modifying the `config.yaml` file or environment variables. Key configurations include:

- **Ollama Settings:** API key, model name, and parameters.
- **Gradio Settings:** Interface layout, theme, and input/output components.
- **Data Analysis Settings:** Default visualizations, summary statistics, etc.

---

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Ollama Team:** For providing the language model capabilities.
- **Gradio Team:** For making it easy to build interactive interfaces.
- **Pandas and Matplotlib Teams:** For their powerful data analysis and visualization libraries.

---

For any questions or issues, please open an issue on the [GitHub repository](https://github.com/sumitchouhan-7768/SmartEDA-Automated-Data-Analysis-with-Ollama-Gradio).

---
