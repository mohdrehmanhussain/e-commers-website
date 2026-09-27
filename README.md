# ShopEasy E-Commerce
Django e-commerce project with attractive responsive UI, sample products/images, product details, authentication, cart, checkout, orders and admin.

## Run in VS Code
```powershell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py seed_data
python manage.py createsuperuser
python manage.py runserver
```
Open http://127.0.0.1:8000/
Admin: http://127.0.0.1:8000/admin/
Sample images are loaded from Unsplash URLs.
