---
title: PdfAccessPermissions
second_title: Aspose.Slides för C++ API-referens
description: Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst.
type: docs
weight: 989
url: /sv/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst.

```cpp
enum class PdfAccessPermissions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Anger att en användare inte har åtkomstbehörigheter. |
| PrintDocument | 4 | Anger om en användare får skriva ut dokumentet (möjligen inte på högsta kvalitet, beroende på om bit [PdfAccessPermissions::HighQualityPrint](./) också är satt). |
| ModifyContent | 8 | Anger om en användare får ändra dokumentets innehåll genom operationer annat än de som styrs av bitarna [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Anger om en användare får kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer annat än den som styrs av bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Anger om en användare får lägga till eller ändra textanteckningar, fylla i interaktiva formulärfält och, om bit [PdfAccessPermissions::ModifyContent](./) också är satt, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FillExistingFields | 256 | Anger om en användare får fylla i befintliga interaktiva formulärfält (inklusive signaturfält), även om bit [PdfAccessPermissions::AddOrModifyFields](./) är rensad. |
| ExtractTextAndGraphics | 512 | Anger om en användare får extrahera text och grafik i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| AssembleDocument | 1024 | Anger om en användare får sammanställa dokumentet (infoga, rotera eller ta bort sidor samt skapa bokmärken eller miniatyrbilder), även om bit [PdfAccessPermissions::ModifyContent](./) är rensad. |
| HighQualityPrint | 2048 | Anger om en användare får skriva ut dokumentet till en representation från vilken en korrekt digital kopia av PDF-innehållet kan genereras. När denna bit är rensad (och bit [PdfAccessPermissions::PrintDocument](./) är satt) är utskriften begränsad till en låg nivå-representation av utseendet, möjligen med försämrad kvalitet. |

## Se också

* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)