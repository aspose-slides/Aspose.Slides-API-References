---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeráció

Contains a set of flags specifying which access permissions should be granted when the document is opened with 
            user access.

The PdfAccessPermissions type exposes the following members:

## Mezők

| Field | Description |
| :- | :- |
| NONE | Megadja, hogy a felhasználónak nincs hozzáférési jogosultsága. |
| PRINT_DOCUMENT | Megadja, hogy a felhasználó nyomtathatja-e a dokumentumot (esetleg nem a legmagasabb minőségi szinten, a [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) bit beállításától függően). |
| MODIFY_CONTENT | Megadja, hogy a felhasználó módosíthatja-e a dokumentum tartalmát olyan műveletekkel, amelyek nem a [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS) és [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) bitek által vezéreltek. |
| COPY_TEXT_AND_GRAPHICS | Megadja, hogy a felhasználó másolhat-e vagy egyéb módon kinyerheti-e a szöveget és a grafikákat a dokumentumból olyan műveletekkel, amelyek nem a [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) bit által vezéreltek. |
| ADD_OR_MODIFY_FIELDS | Megadja, hogy a felhasználó hozzáadhat-e vagy módosíthat-e szöveges megjegyzéseket, kitöltheti-e a interaktív űrlapmezőket, és ha a [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) bit is be van állítva, létrehozhat-e vagy módosíthat-e interaktív űrlapmezőket (beleértve az aláírásmezőket). |
| FILL_EXISTING_FIELDS | Megadja, hogy a felhasználó kitöltheti-e a meglévő interaktív űrlapmezőket (beleértve az aláírásmezőket), még akkor is, ha a [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) bit nincs beállítva. |
| EXTRACT_TEXT_AND_GRAPHICS | Megadja, hogy a felhasználó kinyerheti-e a szöveget és a grafikákat a fogyatékkal élő felhasználók akadálymentesítése vagy egyéb célok támogatása érdekében. |
| ASSEMBLE_DOCUMENT | Megadja, hogy a felhasználó összerendezheti-e a dokumentumot (oldalak beszúrása, forgatása vagy törlése, valamint könyvjelzők vagy bélyegkép létrehozása), még akkor is, ha a [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) bit nincs beállítva. |
| HIGH_QUALITY_PRINT | Megadja, hogy a felhasználó nyomtathat-e a dokumentumot egy olyan ábrázolásra, amelyből a PDF tartalom hűséges digitális másolata előállítható. Ha ez a bit nincs beállítva (és a [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/hu/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) bit be van állítva), a nyomtatás alacsonyabb szintű megjelenítésre korlátozódik, amely esetleg romlotta minőségű. |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)