# Cotton-Leaf-Disease-Detection-using-Convolutional-Neural-Networks-CNN-

1. Set Up Your Environment
a. Create a virtual environment:
python -m venv venv

b. Activate the virtual environment:
Windows:
venv\Scripts\activate

macOS/Linux:
source venv/bin/activate

✅ 2. Install Django (if not already installed)
pip install django

✅ 3. Run the Development Server
Navigate to the directory where your manage.py file is located, then run:
python manage.py runserver

If successful, you should see output like:
Watching for file changes with StatReloader
Starting development server at http://127.0.0.1:8000/
Open that address in a browser to view the site.

🛠️ Troubleshooting Tips
If you get an error about missing modules, you may need to install additional dependencies listed in a requirements.txt file (if available):
pip install -r requirements.txt
If you get ModuleNotFoundError: No module named 'CottonLeafdiseases', double-check that the directory CottonLeafdiseases/ exists and contains settings.py.

