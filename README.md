# Колледж кітапханасының веб-сайты

## Жобаның мақсаты
Колледж студенттері мен оқытушыларына кітаптарды іздеуге және кітапхана қорымен танысуға мүмкіндік беру.

## Қолданылатын технологиялар
- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- Apache
- Docker
- Git және GitHub

## Негізгі мүмкіндіктері
- Кітаптар тізімін қарау
- Кітаптарды іздеу
- Кітапхана туралы ақпарат алу
- Пайдаланушы интерфейсімен жұмыс істеу

## Docker арқылы іске қосу

Image құру:
docker build -t college-library .

Контейнерді іске қосу:
docker run -d -p 8080:80 --name college-library-app college-library

Сайтты ашу:
http://localhost:8080

Контейнерді тоқтату:
docker stop college-library-app

Контейнерді қайта іске қосу:
docker start college-library-app
