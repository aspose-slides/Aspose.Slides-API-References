---
title: PdfAccessPermissions
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten.
type: docs
weight: 989
url: /nl/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten.

```cpp
enum class PdfAccessPermissions
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Specificeert dat een gebruiker geen toegangsrechten heeft. |
| PrintDocument | 4 | Specificeert of een gebruiker het document mag afdrukken (mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of bit [PdfAccessPermissions::HighQualityPrint](./) ook is ingesteld). |
| ModifyContent | 8 | Specificeert of een gebruiker de inhoud van het document mag wijzigen via bewerkingen anders dan die die worden gecontroleerd door bits [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Specificeert of een gebruiker tekst en afbeeldingen uit het document mag kopiëren of anderszins extraheren via bewerkingen anders dan die die worden gecontroleerd door bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Specificeert of een gebruiker tekstannotaties mag toevoegen of wijzigen, interactieve formuliervelden mag invullen, en, indien bit [PdfAccessPermissions::ModifyContent](./) ook is ingesteld, interactieve formuliervelden (inclusief handtekeningvelden) mag creëren of wijzigen. |
| FillExistingFields | 256 | Specificeert of een gebruiker bestaande interactieve formuliervelden (inclusief handtekeningvelden) mag invullen, zelfs als bit [PdfAccessPermissions::AddOrModifyFields](./) niet is ingesteld. |
| ExtractTextAndGraphics | 512 | Specificeert of een gebruiker tekst en afbeeldingen mag extraheren ter ondersteuning van toegankelijkheid voor gebruikers met een handicap of voor andere doeleinden. |
| AssembleDocument | 1024 | Specificeert of een gebruiker het document mag samenstellen (pagina's invoegen, roteren of verwijderen en bladwijzers of miniatuurafbeeldingen maken), zelfs als bit [PdfAccessPermissions::ModifyContent](./) niet is ingesteld. |
| HighQualityPrint | 2048 | Specificeert of een gebruiker het document mag afdrukken naar een weergave waaruit een getrouwe digitale kopie van de PDF-inhoud kan worden gegenereerd. Wanneer dit bit niet is ingesteld (en bit [PdfAccessPermissions::PrintDocument](./) wel is ingesteld), is afdrukken beperkt tot een laag-niveau weergave van het uiterlijk, mogelijk van verminderde kwaliteit. |

## Zie ook

* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)