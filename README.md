Google Collab Instructions
  1. Download the Food_Time new.csv file and upload it to your google drive.
  2. Download the food-delivery-time-predicting.ipynb file and upload it to google drive and open it.
  3. Run first code cell and add one code cell after the first code cell, add the following code and run the code cell [ from google.colab import drive drive.mount('/content/drive') ]
  4. This will connect your google drive. After connecting copy the Food_Time new.csv file paath from the left panel.
  5. Replace this code block (dataset = pd.read_csv('/kaggle/input/food-delivery-time/Food_Time new.csv')) with (dataset = pd.read_csv('paste the file path that you copied')) this code block.
  6. Run All

Additional Tips:
  If you want the code to run faster, you can delete the visual code blocks and run it.
