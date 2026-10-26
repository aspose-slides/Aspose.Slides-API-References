---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeratie

Bevat een reeks vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten.

Het PdfAccessPermissions type biedt de volgende leden:

## Velden

| Field | Description |
| :- | :- |
| NONE | Geeft aan dat een gebruiker geen toegangsrechten heeft. |
| PRINT_DOCUMENT | Geeft aan of een gebruiker het document mag afdrukken (mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) ook is ingesteld). |
| MODIFY_CONTENT | Geeft aan of een gebruiker de inhoud van het document mag wijzigen via bewerkingen die niet worden beheerst door bits [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Geeft aan of een gebruiker tekst en grafische elementen uit het document mag kopiëren of op andere wijze extraheren via bewerkingen die niet worden beheerst door bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Geeft aan of een gebruiker tekstannotaties mag toevoegen of wijzigen, interactieve formuliervelden mag invullen, en, als bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) ook is ingesteld, interactieve formuliervelden (inclusief handtekeningvelden) mag creëren of wijzigen. |
| FILL_EXISTING_FIELDS | Geeft aan of een gebruiker bestaande interactieve formuliervelden (inclusief handtekeningvelden) mag invullen, zelfs als bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) niet is ingesteld. |
| EXTRACT_TEXT_AND_GRAPHICS | Geeft aan of een gebruiker tekst en grafische elementen mag extraheren ter ondersteuning van toegankelijkheid voor gebruikers met een beperking of voor andere doeleinden. |
| ASSEMBLE_DOCUMENT | Geeft aan of een gebruiker het document mag samenstellen (pagina's invoegen, roteren of verwijderen en bladwijzers of miniatuurafbeeldingen maken), zelfs als bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) niet is ingesteld. |
| HIGH_QUALITY_PRINT | Geeft aan of een gebruiker het document mag afdrukken naar een voorstelling waaruit een getrouwe digitale kopie van de PDF-inhoud kan worden gegenereerd. Wanneer dit bit niet is ingesteld (en bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/nl/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) wel is ingesteld), wordt afdrukken beperkt tot een laag-niveau voorstelling van het uiterlijk, mogelijk van verminderde kwaliteit. |

### Zie ook
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)