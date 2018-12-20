# TEAM A : Anime
Contributor :
`Tatas Fachrul`
`Lazuandi Anwar`
`Fandhi Prayoga`
`Setiawan Restu Aji`
`Rizal Prasetya`
`Devi`
`Risky Makira`
`Tri Nanda`

# Installation Animedemy

Clone 
```bash
git clone http://github.com/tatasfachrul/animedemy.git
```

or Download Manual this repositories, then install

## Web Frontend
```bash
cd web-frontend
npm install
```

## Mobile Frontend
```bash
cd mobile-frontend
npm install
```

## Backend
### Install
```bash
cd backend
npm install
```
then make configuration in `env` file and change the following line
```bash
HOST=your_host_address
PORT=your_host_port
DB_CONNECTION=mysql
DB_HOST=your_db_host
DB_PORT=your_db_port
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_DATABASE=your_db
```

### Run
#### Create App Key
```bash
adonis key:generate
```

#### Run Migration
```bash
adonis migration:run
```

## Scrapping


# Installation Redis
Download Redis package via CLI then Install
```bash
wget http://download.redis.io/releases/redis-5.0.3.tar.gz
tar xzf redis-5.0.3.tar.gz
cd redis-5.0.3
make
```

run redis with `src/redis-server`
