# Titanic Notebook

Este cuaderno utiliza algoritmos de aprendizaje automático para obtener la mejor precisión de predicciones sobre quién sobrevivió al hundimiento del Titanic, dados los atributos en el conjunto de datos.

## Setup

- Instalar [Anaconda](https://www.anaconda.com/)
- Establecer la prioridad del canal a estricta para evitar problemas con la creación del entorno que pueden tomar mucho tiempo.
  - `conda config --set channel_priority strict`
- Corra los siguientes comandos (ya sea en la terminal o en en un Anaconda Prompt):
  - `conda env create -f golden_scenario_env.yml`
  - `conda activate golden_scenario_env`
  - `conda install python=3.7`
- En VS Code, abre el archivo [Titanic.ipynb](Titanic.ipynb) y conéctate al kernel golden_scenario_env

Necesitas configurar el entorno como un `ipykernel` para usarlo desde el cuaderno de Jupyter. Para hacerlo, ejecuta dentro del entorno activado de conda:

`python -m ipykernel install --user --name golden_scenario_env --display-name "Golden Scenario Env"`

También, si deseas soportar la exportación a PDF desde Jupyter, necesitas configurar LaTeX:

`sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic`
