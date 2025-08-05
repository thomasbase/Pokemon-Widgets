# Pokemon-Widgets
## Project Scope
This project demonstrates an end-to-end data workflow by extracting, cleaning, and visualizing rich structured data from online Pokémon databases. While the subject matter is gamified, the techniques and technologies reflect real-world data science and data engineering challenges, including **web scraping**, **data wrangling**, and **interactive analytics**.
The scope of this project is limited to Pokemon from generations 1-5 (games that were playable on the Nintendo DS lite).

--- 

## Notebooks Overview
The project is composed of multiple interconnected Jupyter notebooks:

- [`National Pokedex.ipynb`](https://github.com/thomasbase/Pokemon-Widgets/blob/main/National%20Pokedex.ipynb):  
  Defines core web scraping functionality used by all other notebooks.
  
- [`Movesets and Natures.ipynb`](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Movesets%20and%20Natures.ipynb):  
  Extracts and processes data on Pokémon moves, abilities, and natures. This notebook generates local `.pkl` files containing dictionaries of DataFrames (logic documented within the notebook).
  
- [`Items and TMs.ipynb`](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Items%20and%20TMs.ipynb):  
  Processes item data and technical machine (TM) availability.
  
- [`Types.ipynb`](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Types.ipynb):  
  Contains logic for Pokémon type effectiveness and matchups.

- [`Widgets.ipynb`](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Widgets.ipynb):  
  Final UI notebook. Consolidates outputs from all other notebooks into a **widget-based interface** for querying and visualizing Pokémon data.

---

## Sample Outputs
Below are screenshots demonstrating user queries from the `Widgets.ipynb` notebook:

**Stats View**  
![Pokemon Stats](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Pokemon%20Stats.png)

**Moveset and Abilities**  
![Pokemon Movesets](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Pokemon%20Moveset.png)

**Head-to-Head Matchup**  
![Pokemon Matchup](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Pokemon%20Matchup.png)

**Type Matchups**  
![Type Matchup](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Type%20Matchup.png)

**Regional Pokédex**  
![Regional Pokedex](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Regional%20Pokedex.png)

**National Pokédex**  
![National Pokedex](https://github.com/thomasbase/Pokemon-Widgets/blob/main/National%20Pokedex.png)

**Move Search by Type**  
![Moves by Type](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Moves%20by%20Type.png)

**Items View**  
![Items](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Items.png)

**Nature Effects**  
![Natures](https://github.com/thomasbase/Pokemon-Widgets/blob/main/Natures.png)

---

## Technologies Used
- **Python**
- **Jupyter Notebooks**
- **Requests / Web Scraping**
- **Pandas / DataFrames**
- **IPyWidgets** for interactivity
- **Matplotlib / Plotly** for visualization