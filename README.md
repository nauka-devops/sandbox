# Sandbox — poligon symulacji pracy zespołowej

Testowa aplikacja **Statusownia** — prosta strona statusu usług.
Służy do ćwiczenia pełnego cyklu pracy na GitHubie: branch → commit → push →
Pull Request → review → merge, z włączonym branch protection na `main`.

## Aplikacja

Statyczna strona (`index.html` + `style.css`) pokazująca status "usług" firmy.
Celowo prosta — każda zmiana (nowa usługa, kolor, tekst) to dobry materiał na PR.

Otwórz `index.html` w przeglądarce — zero instalacji.

## Zespół (symulacja)

| Rola | Konto |
|---|---|
| Owner / reviewer | Ariowistus |
| Developer | rvzch08-hue (team `developers`, dostęp: write) |

## Zasady pracy (jak w prawdziwym zespole)

1. **Nikt nie commituje na `main`** — ruleset wymaga Pull Requesta z 1 approvalem.
2. Każda zmiana = branch o opisowej nazwie (`dodaj-usluge-x`, `fix-kolor-statusu`).
3. Commity małe i opisowe.
4. PR opisuje CO i PO CO (nie "zmiany" tylko "dodaję usługę X, bo...").

## Pomysły na ćwiczenia PR

- [ ] dodaj nową usługę do tabeli statusów
- [ ] zmień status usługi (operational → down) i kolor
- [ ] dodaj stopkę z datą aktualizacji
- [ ] wywołaj konflikt: dwie gałęzie edytują tę samą linię → rozwiąż
- [ ] (Etap 6) dodaj Dockerfile z nginx serwującym stronę
