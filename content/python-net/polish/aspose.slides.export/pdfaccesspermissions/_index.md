---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeracja

Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument jest otwierany z 
            dostępem użytkownika.

Typ PdfAccessPermissions udostępnia następujące elementy:

## Pola

| Pole | Opis |
| :- | :- |
| NONE | Określa, że użytkownik nie posiada uprawnień dostępu. |
| PRINT_DOCUMENT | Określa, czy użytkownik może drukować dokument (być może nie w najwyższej jakości, w zależności od <br/>            czy bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) jest również ustawiony). |
| MODIFY_CONTENT | Określa, czy użytkownik może modyfikować zawartość dokumentu operacjami innymi niż te kontrolowane<br/>            przez bity [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Określa, czy użytkownik może kopiować lub w inny sposób wydobywać tekst i grafikę z dokumentu operacjami <br/>            innymi niż te kontrolowane przez bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Określa, czy użytkownik może dodawać lub modyfikować adnotacje tekstowe, wypełniać interaktywne pola formularzy i, jeśli bit<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) jest również ustawiony, tworzyć lub modyfikować interaktywne pola formularzy (w tym pola podpisu <br/>            ). |
| FILL_EXISTING_FIELDS | Określa, czy użytkownik może wypełniać istniejące interaktywne pola formularzy (w tym pola podpisu), nawet jeśli<br/>            bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) jest nieustawiony. |
| EXTRACT_TEXT_AND_GRAPHICS | Określa, czy użytkownik może wydobywać tekst i grafikę w celu zapewnienia dostępności dla użytkowników niepełnosprawnych<br/>            lub w innych celach. |
| ASSEMBLE_DOCUMENT | Określa, czy użytkownik może składać dokument (wstawiać, obracać lub usuwać strony oraz tworzyć zakładki lub<br/>            miniatury), nawet jeśli bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) jest nieustawiony. |
| HIGH_QUALITY_PRINT | Określa, czy użytkownik może drukować dokument w reprezentacji, z której można wygenerować wierną cyfrową kopię zawartości PDF. Gdy ten bit jest nieustawiony (a bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/pl/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) jest ustawiony),<br/>            drukowanie jest ograniczone do niskopoziomowej reprezentacji wyglądu, możliwe o obniżonej jakości. |

### Zobacz także
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)