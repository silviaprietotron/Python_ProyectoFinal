# Proyecto de Visualización de Datos Financieros con Kraken API

Este proyecto permite visualizar el movimiento de precios de criptomonedas en tiempo real a través de gráficos interactivos. Utilizando la API pública de Kraken, los usuarios pueden seleccionar un par de monedas y observar su evolución mediante gráficos de precios, gráficos de velas y Bandas de Bollinger, con la posibilidad de generar señales de compra o venta.

# Funcionalidades

1. Gráfico de Precios: Visualiza el comportamiento del precio de un par de criptomonedas a lo largo del tiempo.
2. Gráfico de Velas: Muestra un gráfico de velas con los valores de apertura, cierre, máximos y mínimos.
3. Bandas de Bollinger: Superpone las Bandas de Bollinger al gráfico de precios o velas, indicando posibles zonas de sobrecompra o sobreventa.
4. Generación de Señales de Compra/Venta: Analiza el comportamiento del precio con respecto a las Bandas de Bollinger para generar alertas visuales.

# Tecnologías Utilizadas

1. Streamlit: Para crear una interfaz interactiva y fácil de usar.
2. Pandas: Para la manipulación y análisis de los datos obtenidos de la API.
3. Matplotlib: Para la creación de gráficos.
4. Kraken API: Para la obtención de datos financieros en tiempo real.

# Requisitos

Para ejecutar este proyecto, es necesario tener instalado Python 3.6 o superior y las siguientes dependencias:

- streamlit
- pandas
- matplotlib
- requests

# Instalación

1. Clona el repositorio:
git clone https://github.com/silviaprietotron/FinalProject.git
cd FinalProject

2. Instala las dependencias desde el archivo requirements.txt:
pip install -r requirements.txt

3. Ejecuta la aplicación:
streamlit run ProyectoFinal_SilviaPrieto.py

Esto abrirá la aplicación en tu navegador predeterminado.

# Uso

Una vez que la aplicación esté en funcionamiento, podrás interactuar con ella a través de la interfaz gráfica proporcionada por Streamlit. Las principales características incluyen:

1. Selección del par de criptomonedas: Utiliza un menú desplegable para elegir el par de criptomonedas que deseas analizar.
2. Gráfico de precios y velas: Elige entre un gráfico de precios o un gráfico de velas para ver la evolución del precio en el tiempo.
3. Bandas de Bollinger: Activa la opción para superponer las Bandas de Bollinger al gráfico seleccionado. Las bandas te ayudarán a identificar posibles zonas de sobrecompra o sobreventa.
4. Generación de señales de compra/venta: Basado en la relación del precio con las bandas, la aplicación generará alertas visuales que te ayudarán a tomar decisiones informadas.
