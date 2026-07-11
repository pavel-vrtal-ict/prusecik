# Průsečík — dotazník pro partnery

Interaktivní dotazník pro ověření společného byznysového směru. Než tým začne plánovat konkrétní firmu, každý partner projde 17 upřímných otázek o energii, hranicích, zákaznících, riziku a očekáváních.

**Vyplnění trvá asi 25–35 minut.** Dotazník nemá nikoho přesvědčit — má ukázat, kde se představy potkávají a kde ne.

## Pro partnery

**Dotazník:** https://pavel-vrtal-ict.github.io/prusecik/

1. Otevři odkaz výše.
2. Vyber své jméno a projdi všech 17 otázek.
3. Na konci se odpovědi automaticky odešlou e-mailem — nic nemusíš kopírovat.
4. Pro jistotu si můžeš odpovědi i stáhnout nebo zkopírovat jako zálohu.

> Nezavírej stránku, dokud dotazník nedokončíš — rozpracované odpovědi se ukládají jen v prohlížeči.

## Pro Pavla (správa odpovědí)

- **Admin přehled:** https://pavel-vrtal-ict.github.io/prusecik/?admin=1
- Odpovědi chodí e-mailem přes Web3Forms; v adminu je lze vložit a exportovat pro AI analýzu

## Obsah repozitáře

| Soubor | Účel |
|---|---|
| `index.html` | Dotazník (GitHub Pages) |
| `07_otazky_pro_partnery.md` | Referenční znění otázek pro vyhodnocení |
| `05_znalostni_kontext_tymu.md` | Kontext týmu a pravidla analýzy |
| `00_README.md` | Návod na založení Claude/ChatGPT projektů |
| `01–06` | Popisy, instructions a startovací prompty pro AI |

## Lokální náhled

Otevři `index.html` přímo v prohlížeči, nebo spusť jednoduchý server:

```powershell
python -m http.server 8080
```

Potom otevři `http://localhost:8080`.
