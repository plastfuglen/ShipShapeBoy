# Kai-kaos – landstrøm-spillet

Et kort browserspill (90 sekunder) for messer og sosiale medier. Spilleren loser skip inn til kai og kobler dem til landstrøm før eksosen legger seg over byen.

**Spill:** åpne `index.html` i en nettleser. Det er én fil uten byggesteg. Spillet fungerer på mobil, nettbrett og PC.

## Slik spilles det
1. **Dra** en strek fra et skip til kaien med samme farge (gul = cruise, turkis = elferje, oransje = fiskebåt).
2. **Trykk** på et skip som ligger ved kai for å koble det til landstrøm (trykk igjen for å koble fra).
3. Trafoen tåler **10 MW**. Cruiseskipet (7 MW) og elferja (4 MW) kan ikke lade samtidig – du må prioritere.

Skip som ligger ved kai uten strøm, eller venter ute, slipper ut røyk og senker «Byluft». Går byluften til 0, er spillet slutt.

## Poeng
- CO₂ spart: 1 MW landstrøm i 1 sekund ≈ 11,7 kg (1 s i spillet ≈ 1 min i havna, dieselaggregat ≈ 0,7 kg CO₂/kWh)
- +25 til kai, +50 «grønt anløp» (minst 60 % av liggetiden på landstrøm), +200 elferje som går fulladet
- −50 grunnstøting, −100 kollisjon

Tallene er forenklede anslag ment for formidling, ikke beregning.

## Messemodus
- Topplisten lagres lokalt i nettleseren (localStorage) på messe-PC-en/nettbrettet.
- Sluttskjermen går tilbake til startskjermen etter 45 sekunder uten aktivitet.
- Legg logo i `assets/logo.svg`, så vises den nederst til høyre på startskjermen.
