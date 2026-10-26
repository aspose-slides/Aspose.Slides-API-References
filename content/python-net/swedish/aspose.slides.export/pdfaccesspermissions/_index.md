---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Contains a set of flags specifying which access permissions should be granted when the document is opened with 
            user access.

The PdfAccessPermissions type exposes the following members:

## Fält

| Fält | Beskrivning |
| :- | :- |
| NONE | Anger att en användare inte har åtkomstbehörigheter. |
| PRINT_DOCUMENT | Anger om en användare får skriva ut dokumentet (möjligen inte på högsta kvalitetsnivå, beroende på om bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) också är satt). |
| MODIFY_CONTENT | Anger om en användare får ändra dokumentets innehåll genom operationer som inte styrs av bitarna [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Anger om en användare får kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte styrs av bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Anger om en användare får lägga till eller ändra textanteckningar, fylla i interaktiva formulärfält och, om bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) också är satt, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FILL_EXISTING_FIELDS | Anger om en användare får fylla i befintliga interaktiva formulärfält (inklusive signaturfält), även om bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) är avstängd. |
| EXTRACT_TEXT_AND_GRAPHICS | Anger om en användare får extrahera text och grafik för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| ASSEMBLE_DOCUMENT | Anger om en användare får sammanställa dokumentet (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder), även om bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) är avstängd. |
| HIGH_QUALITY_PRINT | Anger om en användare får skriva ut dokumentet till en representation från vilken en exakt digital kopia av PDF-innehållet kan genereras. När denna bit är avstängd (och bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/sv/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) är satt) begränsas utskriften till en lågupplöst representation av utseendet, möjligen med försämrad kvalitet. |


### Se även
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)