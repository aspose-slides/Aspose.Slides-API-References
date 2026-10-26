---
title: PdfAccessPermissions
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird.
type: docs
weight: 989
url: /de/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions Aufzählung


Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird.

```cpp
enum class PdfAccessPermissions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Gibt an, dass ein Benutzer keine Zugriffsberechtigungen hat. |
| PrintDocument | 4 | Gibt an, ob ein Benutzer das Dokument drucken darf (möglicherweise nicht in höchster Qualität, abhängig davon, ob das Bit [PdfAccessPermissions::HighQualityPrint](./) ebenfalls gesetzt ist). |
| ModifyContent | 8 | Gibt an, ob ein Benutzer den Inhalt des Dokuments durch andere Vorgänge als die von den Bits [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./) gesteuerten ändern darf. |
| CopyTextAndGraphics | 16 | Gibt an, ob ein Benutzer Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren darf, durch Vorgänge, die nicht vom Bit [PdfAccessPermissions::ExtractTextAndGraphics](./) gesteuert werden. |
| AddOrModifyFields | 32 | Gibt an, ob ein Benutzer Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, falls das Bit [PdfAccessPermissions::ModifyContent](./) ebenfalls gesetzt ist, interaktive Formularfelder (einschließlich Signaturfelder) erstellen oder ändern darf. |
| FillExistingFields | 256 | Gibt an, ob ein Benutzer bestehende interaktive Formularfelder (einschließlich Signaturfelder) ausfüllen darf, selbst wenn das Bit [PdfAccessPermissions::AddOrModifyFields](./) deaktiviert ist. |
| ExtractTextAndGraphics | 512 | Gibt an, ob ein Benutzer Text und Grafiken zum Zweck der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken extrahieren darf. |
| AssembleDocument | 1024 | Gibt an, ob ein Benutzer das Dokument zusammenstellen darf (Seiten einfügen, drehen oder löschen und Lesezeichen oder Vorschaubilder erstellen), selbst wenn das Bit [PdfAccessPermissions::ModifyContent](./) deaktiviert ist. |
| HighQualityPrint | 2048 | Gibt an, ob ein Benutzer das Dokument so drucken darf, dass daraus eine getreue digitale Kopie des PDF-Inhalts erzeugt werden kann. Ist dieses Bit deaktiviert (und das Bit [PdfAccessPermissions::PrintDocument](./) ist gesetzt), ist der Druck auf eine niedrigstufige Darstellung des Aussehens beschränkt, die möglicherweise von geringerer Qualität ist. |

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)