
<div style="display: flex; align-items: left;">
  <img src="data/logo.webp" alt="Logo" width="40" height="40">
</div>

# BioPyAssistant

BioPyAssistant is a chatbot designed to assist students from life science curricula with questions related to Python programming.


## Installation

To install BioPyAssistant and its dependencies, run the following commands:

Clone the repository:

```bash
git clone https://github.com/pierrepo/biopyassist
cd biopyassist
```

Create a Conda environment:

```bash
conda env create -f environment.yml
```


## Usage

### Step 1: Activate the Conda Environment

Activate the Conda environment by running:

```bash
conda activate biopyassistenv
```

### Step 2: Create Chroma DB

Create the Chroma database by running:

```bash
python src/create_database.py
```

### Step 3: Set up OpenAI API key

Create a `.env` file with a valid OpenAI API key:

```text
OPENAI_API_KEY=<your-openai-api-key>
```