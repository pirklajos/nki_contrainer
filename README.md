Requitments:
~~~~~~~~~~~~
- Composer (tested on 2.3.7)
- Docker (tested on 25.0.3)


Installation:
~~~~~~~~~~~~~
cd app
git clone https://github.com/pirklajos/rssreader.git site
cd site
composer install
cd ..
docker-compose up -d
docker exec -i app-mysql mysql -uapp -papppass rssreader < rssreaderapp.sql

open in browser: 
    localhost:8001
