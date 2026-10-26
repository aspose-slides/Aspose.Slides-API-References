---
title: PdfAccessPermissions
second_title: Aspose.Slides pro C++ referenční příručka
description: Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena.
type: docs
weight: 989
url: /cs/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena.

```cpp
enum class PdfAccessPermissions
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Určuje, že uživatel nemá žádná přístupová oprávnění. |
| PrintDocument | 4 | Určuje, zda uživatel může tisknout dokument (možná ne v nejvyšší kvalitě, v závislosti na tom, zda je také nastaven bit [PdfAccessPermissions::HighQualityPrint](./)). |
| ModifyContent | 8 | Určuje, zda uživatel může měnit obsah dokumentu operacemi jinými než jsou řízeny bity [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Určuje, zda uživatel může kopírovat nebo jinak extrahovat text a grafiku z dokumentu operacemi jinými než jsou řízeny bitem [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Určuje, zda uživatel může přidávat nebo upravovat textové anotace, vyplňovat interaktivní formulářová pole a, pokud je také nastaven bit [PdfAccessPermissions::ModifyContent](./), vytvářet nebo upravovat interaktivní formulářová pole (včetně polí pro podpis). |
| FillExistingFields | 256 | Určuje, zda uživatel může vyplňovat existující interaktivní formulářová pole (včetně polí pro podpis), i když není nastaven bit [PdfAccessPermissions::AddOrModifyFields](./). |
| ExtractTextAndGraphics | 512 | Určuje, zda uživatel může extrahovat text a grafiku pro podporu přístupnosti uživatelům se zdravotním postižením nebo pro jiné účely. |
| AssembleDocument | 1024 | Určuje, zda uživatel může sestavit dokument (vkládat, otáčet nebo mazat stránky a vytvářet záložky nebo miniatury), i když není nastaven bit [PdfAccessPermissions::ModifyContent](./). |
| HighQualityPrint | 2048 | Určuje, zda uživatel může tisknout dokument do podoby, ze které lze vytvořit věrnou digitální kopii obsahu PDF. Když je tento bit ne nastaven (a bit [PdfAccessPermissions::PrintDocument](./) je nastaven), tisk je omezen na nízkoúrovňovou reprezentaci vzhledu, pravděpodobně s degradovanou kvalitou. |

## Viz také

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)