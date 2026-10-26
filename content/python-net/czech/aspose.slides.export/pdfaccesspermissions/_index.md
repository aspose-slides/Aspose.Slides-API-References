---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumerace

Obsahuje sadu příznaků určujících, která oprávnění k přístupu mají být udělena, když je dokument otevřen s 
            uživatelským přístupem.

Typ PdfAccessPermissions vystavuje následující členy:

## Pole

| Pole | Popis |
| :- | :- |
| NONE | Určuje, že uživatel nemá žádná oprávnění k přístupu. |
| PRINT_DOCUMENT | Určuje, zda může uživatel dokument tisknout (možná ne v nejvyšší kvalitě, v závislosti na tom, <br/>zda je také nastaven bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT)). |
| MODIFY_CONTENT | Určuje, zda může uživatel měnit obsah dokumentu operacemi jinými než jsou řízeny <br/>bity [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Určuje, zda může uživatel kopírovat nebo jinak extrahovat text a grafiku z dokumentu operacemi <br/>jinými než jsou řízeny bitem [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Určuje, zda může uživatel přidávat nebo měnit textové anotace, vyplňovat interaktivní formulářová pole a pokud je také nastaven bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT), vytvářet nebo měnit interaktivní formulářová pole (včetně podpisových <br/>polí). |
| FILL_EXISTING_FIELDS | Určuje, zda může uživatel vyplnit existující interaktivní formulářová pole (včetně podpisových polí), i když je <br/>bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) vypnutý. |
| EXTRACT_TEXT_AND_GRAPHICS | Určuje, zda může uživatel extrahovat text a grafiku na podporu přístupnosti pro uživatele se zdravotním postižením nebo pro jiné účely. |
| ASSEMBLE_DOCUMENT | Určuje, zda může uživatel sestavit dokument (vkládat, otáčet nebo mazat stránky a vytvářet záložky nebo <br/>náhledové obrázky), i když je bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) vypnutý. |
| HIGH_QUALITY_PRINT | Určuje, zda může uživatel dokument tisknout do podoby, ze které lze vytvořit věrnou digitální kopii obsahu PDF. Když je tento bit vypnutý (a bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/cs/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) je nastaven),<br/>tisk je omezen na nízkoúrovňovou reprezentaci vzhledu, možná s nižší kvalitou. |

### Viz také
* modul [`aspose.slides.export`](/slides/python-net/cs/aspose.slides.export)
* knihovna [`Aspose.Slides`](/slides/python-net)