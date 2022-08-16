Windows Installation

Pre Requisite:
1. Docker Desktop app
2. WSL 2

Installation:
1. wget "https://github.com/wlabesamis/ospos-localhost/archive/refs/heads/master.zip" -OutFile "ospos-3.3.7.zip"
2. Expand-Archive -LiteralPath 'ospos-3.3.7.zip' 
3. cd .\ospos-3.3.7\ospos-localhost-master\
4. docker-compose -f docker-compose.yml up --force-recreate -d nginx


Linux Installation

Pre Requisite:
1. Docker & Docker Compose

Installation:
1. wget "https://github.com/wlabesamis/ospos-localhost/archive/refs/heads/master.zip" -O "ospos-3.3.7.zip"
2. unzip ospos-3.3.7.zip
3. cd o1spos-localhost-master\
4. bash scripts/start.sh