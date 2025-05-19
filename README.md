 # مشروع قائمة المهام (Todo Project)

## الوصف
هذا المشروع هو تطبيق ويب لإدارة قائمة المهام باستخدام Django و Django REST Framework. يتيح للمستخدمين تسجيل الدخول وإنشاء وإدارة مهامهم.

## المتطلبات
- Python 3.x
- Django
- Django REST Framework
- Simple JWT (للمصادقة باستخدام JWT)

## كيفية التشغيل

### 1. تثبيت المتطلبات
قم بتثبيت المتطلبات باستخدام الأمر التالي:
```bash
pip install -r requirements.txt
```

### 2. تهيئة قاعدة البيانات
قم بتشغيل الأوامر التالية لتهيئة قاعدة البيانات:
```bash
python manage.py makemigrations
python manage.py migrate
```

### 3. إنشاء مستخدم مسؤول
لإنشاء مستخدم مسؤول، استخدم الأمر التالي:
```bash
python manage.py createsuperuser
```

### 4. تشغيل الخادم
قم بتشغيل الخادم باستخدام الأمر التالي:
```bash
python manage.py runserver
```

### 5. الوصول إلى التطبيق
افتح المتصفح واذهب إلى الرابط التالي: