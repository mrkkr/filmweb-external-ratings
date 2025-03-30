# Zewnętrzne Oceny dla Filmweb

Skrypt użytkownika dodający oceny z IMDb, Rotten Tomatoes i Metacritic bezpośrednio na stronach Filmweb.

## Instalacja

1. Najpierw zainstaluj jedno z tych rozszerzeń:
   - [Violentmonkey](https://violentmonkey.github.io/)
   - [Tampermonkey](https://www.tampermonkey.net/)

2. Kliknij ten link, aby zainstalować skrypt: [Zainstaluj Zewnętrzne Oceny dla Filmweb](filmweb-ratings.user.js)

## Funkcje

- Automatycznie pobiera i wyświetla oceny z:
  - IMDb
  - Rotten Tomatoes
  - Metacritic
- Pokazuje oceny bezpośrednio na stronie filmu w Filmweb
- Klikalne oceny przenoszące do strony źródłowej
- Działa z filmami i serialami
- Używa oryginalnych tytułów dla lepszej dokładności

## Użytkowanie

1. Zainstaluj skrypt jak opisano powyżej
2. Odwiedź dowolną stronę filmu lub serialu na Filmweb
3. Zewnętrzne oceny pojawią się automatycznie pod oceną Filmweb
4. Kliknij na dowolną ocenę, aby przejść do strony źródłowej

## Szczegóły Techniczne

- Wykorzystuje API OMDB do pobierania danych o filmach
- Wymaga Violentmonkey lub Tampermonkey z uprawnieniem GM_xmlhttpRequest
- Działa tylko na domenie filmweb.pl
