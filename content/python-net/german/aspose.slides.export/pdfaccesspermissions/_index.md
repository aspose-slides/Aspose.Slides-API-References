---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions Aufzählung

Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird.

Der Typ PdfAccessPermissions stellt die folgenden Mitglieder bereit:

## Felder

| Feld | Beschreibung |
| :- | :- |
| NONE | Gibt an, dass ein Benutzer keine Zugriffsberechtigungen hat. |
| PRINT_DOCUMENT | Gibt an, ob ein Benutzer das Dokument drucken darf (möglicherweise nicht in höchster Qualität, abhängig davon, ob <br/>            das Bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) ebenfalls gesetzt ist). |
| MODIFY_CONTENT | Gibt an, ob ein Benutzer den Inhalt des Dokuments durch andere Vorgänge als die von den Bits<br/>            [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) gesteuerten, ändern darf. |
| COPY_TEXT_AND_GRAPHICS | Gibt an, ob ein Benutzer Text und Grafiken aus dem Dokument durch andere Vorgänge als die von Bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) gesteuerten, kopieren oder extrahieren darf. |
| ADD_OR_MODIFY_FIELDS | Gibt an, ob ein Benutzer Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, falls das Bit<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) ebenfalls gesetzt ist, interaktive Formularfelder (einschließlich Signatur-<br/>            felder) erstellen oder ändern darf. |
| FILL_EXISTING_FIELDS | Gibt an, ob ein Benutzer bestehende interaktive Formularfelder (einschließlich Signaturfelder) ausfüllen darf, selbst wenn<br/>            das Bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) nicht gesetzt ist. |
| EXTRACT_TEXT_AND_GRAPHICS | Gibt an, ob ein Benutzer Text und Grafiken zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen<br/>            oder zu anderen Zwecken extrahieren darf. |
| ASSEMBLE_DOCUMENT | Gibt an, ob ein Benutzer das Dokument zusammenstellen darf (Seiten einfügen, drehen oder löschen und Lesezeichen oder<br/>            Miniaturbilder erstellen), selbst wenn das Bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) nicht gesetzt ist. |
| HIGH_QUALITY_PRINT | Gibt an, ob ein Benutzer das Dokument so drucken darf, dass daraus eine getreue digitale Kopie des<br/>            PDF-Inhalts erzeugt werden kann. Wenn dieses Bit nicht gesetzt ist (und das Bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/de/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) gesetzt ist),<br/>            ist der Druck auf eine low-level Darstellung des Aussehens beschränkt, möglicherweise von minderinger Qualität. |

### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)