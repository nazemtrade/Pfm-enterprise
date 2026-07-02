# Pfm-enterprise
Paper flowers shopping
عالی. این بهترین روش است. تو فایل‌ها را در مخزن GitHub قرار می‌دهی و من پروژه را مرحله‌به‌مرحله توسعه می‌دهم تا در پایان یک ERP واقعی داشته باشیم.

## از امروز پروژه وارد حالت توسعه رسمی می‌شود.

**نام پروژه:** `PFM Enterprise`

**محصول:** Paper Flower ERP

**نسخه فعلی:** **v0.1.0**

---

# Sprint 1 (شروع پروژه)

در پروژه‌های حرفه‌ای، کار را به Sprint تقسیم می‌کنند.

## Sprint 1

### Phase 2.1

تحلیل پایگاه داده

* ✅ تکمیل شده

---

### Phase 2.2

طراحی Database

این بخش شامل:

```
database/

├── 01_CreateDatabase.sql

├── 02_CreateTables.sql

├── 03_CreateIndexes.sql

├── 04_CreateViews.sql

├── 05_CreateTriggers.sql

├── 06_CreateProcedures.sql

├── 07_InsertSampleData.sql

├── ERD.drawio

├── DatabaseDictionary.docx

└── README.md
```

---

### سپس

Frontend

```
frontend/

index.html

login.html

dashboard.html

products.html

orders.html

inventory.html

production.html

customers.html

reports.html
```

---

### Backend

```
backend/

Laravel

Controllers

Models

Middleware

Auth

API

Routes
```

---

### Mobile

```
mobile/

manifest.json

service-worker.js

icons

offline.html
```

---

### Documents

```
docs/

BusinessRequirement.docx

SystemDesign.docx

Architecture.pdf

RoadMap.pdf

Database.pdf
```

---

# روش کار ما

از امروز هر پاسخ من دقیقاً مانند یک Commit خواهد بود.

مثلاً

```
Commit 0001

Project Structure
```

بعد

```
Commit 0002

Database Tables
```

بعد

```
Commit 0003

Authentication
```

و به همین ترتیب تا نسخه **v1.0.0**.

---

# اولین Commit

```
Commit ID

0001
```

عنوان

```
Initial Project Structure
```

پیام Commit

```
Initial architecture for Paper Flower ERP

Project folders

Database

Backend

Frontend

PWA

Documents

Reports

API
```

---

## نکته مهم

از این لحظه دیگر پروژه را مانند یک پروژه واقعی توسعه می‌کنم.

**هیچ فایلی حذف نخواهد شد.**

هر فایل شماره نسخه خواهد داشت.

هر تغییر در فایل CHANGELOG ثبت خواهد شد.

تمام فایل‌ها با هم سازگار خواهند بود.

در پایان، نسخه **1.0.0** قابل نصب و اجرا خواهد بود.

### پیشنهاد تکمیلی

من پیشنهاد می‌کنم در مخزن GitHub برای پروژه یک پوشه به نام **`releases/`** هم ایجاد کنی. در پایان هر فاز، نسخه ZIP همان فاز را داخل آن قرار دهی. این کار باعث می‌شود همیشه بتوانی به نسخه‌های قبلی برگردی و تاریخچه پروژه حفظ شود. این دقیقاً همان روشی است که تیم‌های حرفه‌ای توسعه نرم‌افزار از آن استفاده می‌کنند.

