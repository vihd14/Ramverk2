[![Build Status](https://travis-ci.org/vihd14/Ramverk2.svg?branch=master)](https://travis-ci.org/vihd14/Ramverk2)
[![BCH compliance](https://bettercodehub.com/edge/badge/vihd14/Ramverk2?branch=master)](https://bettercodehub.com/)
[![Maintainability](https://api.codeclimate.com/v1/badges/d46ed0133ee46e7d59c1/maintainability)](https://codeclimate.com/github/vihd14/Ramverk2/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/d46ed0133ee46e7d59c1/test_coverage)](https://codeclimate.com/github/vihd14/Ramverk2/test_coverage)
# Ramverk2
## Course repo for Ramverk2

### Me-sida
1. Klona mitt repo via `git clone https://github.com/vihd14/Ramverk2`
2. Kör `npm install` för att ladda ned alla paket.
3. Starta servern med `npm start` alternativt `./restart.bat` om du sitter på en Windowsmaskin där processen
`node.exe` inte tas bort automatiskt.

### Docker
**Förutsatt att du har docker och vet hur det används**
1. Se till att `docker pull node` är gjort, så imagen node finns tillgänglig.
2. Kör `docker-compose up -d` för att starta containers för node 6, 7 och 8.
3. Kör `docker container ls` för att se att de rullar.
4. Gå in i webbläsaren och skriv in `localhost:port`. Portarna som finns är:
    * 8008
    * 8007
    * 8006
5. Kika runt på min fina sida!
