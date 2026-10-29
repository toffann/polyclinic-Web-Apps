## 👥 Roles & Features

- **Admin**: Full control over users, doctors, patients, polyclinics, schedules, and medicine inventory.
- **Doctor**: Manage examination schedules, prescriptions, and patient records.
- **Patient**: Book appointments, choose doctors, and purchase prescribed medicines.

---

## 🛠️ Tech Stack

- **Framework**: Laravel 13 (PHP 8.3)
- **Database**: MySQL
- **Frontend**: Tailwind CSS, DaisyUI, Vite

---

## ⚙️ Quick Setup

1. **Clone & Install Dependencies**
   ```bash
   git clone [https://github.com/toffann/polyclinic-Web-Apps.git](https://github.com/toffann/polyclinic-Web-Apps.git)
   cd poliklinik-app
   composer install && npm install
Environment & Database

Bash
copy .env.example .env
php artisan key:generate
(Update your database details in .env)

Migrate & Run

Bash
php artisan migrate --seed
php artisan serve
(Run npm run dev in a separate terminal for frontend assets)

👨‍💻 Contributor
Taufan Afandi (GitHub)
