# Text-To-World-Map: README

## Overview
Text-To-World-Map is a project designed to generate spatially accurate maps from text input. It processes textual descriptions of buildings or areas to create structured map layouts, enabling users to visualize and organize spaces effectively. Trained on data sourced from Google Maps, it serves as a stepping stone for integrating spatial understanding into 3D scene generation. With the rapid advancements in text-to-3D modeling, this tool bridges the gap between textual input and 3D world-building. The generated maps can guide the placement of objects within scenes, making it a valuable resource for creating coherent virtual environments. Additionally, this project could be deployed as a Flask app, enabling API calls for seamless integration. In the future, tools like Unity or Blender could directly leverage this functionality to generate entire scenes.

## Setup and Installation
You can set up the project using either `setup.sh` or `requirements.txt`.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Text-To-World-Map
   ```
2. Run the setup script or install dependencies:
   ```bash
   # Using setup.sh
   bash setup.sh

   # Or using requirements.txt
   pip install -r requirements.txt
   ```

3. Obtain API keys from:
   - **Google Cloud Console:** For fetching map data.
   - **OpenAI:** For text processing.

4. Enter API keys in the third cell of `src/main.ipynb`.

## Usage
### Data Preparation
1. Fetch map data using the provided notebook.
2. All fetched data will be stored in a `.pkl` file for reuse.

### Running the Project
1. Open `src/main.ipynb` in Jupyter Notebook.
2. Follow the instructions in the notebook.
3. Use the `text_to_map` function to input your text and generate a map.

## License
This project is licensed under the MIT License.
