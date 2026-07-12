---
title: PdfAccessPermissions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird.
type: docs
url: /de/com.aspose.slides/pdfaccesspermissions/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Gibt an, dass ein Benutzer keine Zugriffsberechtigungen hat. |
| [PrintDocument](#PrintDocument) | Gibt an, ob ein Benutzer das Dokument drucken darf (möglicherweise nicht in höchster Qualitätsstufe, abhängig davon, ob Bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ebenfalls gesetzt ist). |
| [ModifyContent](#ModifyContent) | Gibt an, ob ein Benutzer den Inhalt des Dokuments durch Vorgänge ändern darf, die nicht von den Bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) gesteuert werden. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Gibt an, ob ein Benutzer Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren darf, durch Vorgänge, die nicht von Bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) gesteuert werden. |
| [AddOrModifyFields](#AddOrModifyFields) | Gibt an, ob ein Benutzer Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, falls Bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ebenfalls gesetzt ist, interaktive Formularfelder (einschließlich Signaturfelder) erstellen oder ändern darf. |
| [FillExistingFields](#FillExistingFields) | Gibt an, ob ein Benutzer vorhandene interaktive Formularfelder (einschließlich Signaturfelder) ausfüllen darf, selbst wenn Bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) nicht gesetzt ist. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Gibt an, ob ein Benutzer Text und Grafiken zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder zu anderen Zwecken extrahieren darf. |
| [AssembleDocument](#AssembleDocument) | Gibt an, ob ein Benutzer das Dokument zusammenstellen darf (Seiten einfügen, drehen oder löschen sowie Lesezeichen oder Miniaturbilder erstellen), selbst wenn Bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) nicht gesetzt ist. |
| [HighQualityPrint](#HighQualityPrint) | Gibt an, ob ein Benutzer das Dokument zu einer Darstellung drucken darf, aus der eine genaue digitale Kopie des PDF-Inhalts erzeugt werden könnte. |
### None {#None}
```
public static final int None
```

Gibt an, dass ein Benutzer keine Zugriffsberechtigungen hat.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Gibt an, ob ein Benutzer das Dokument drucken darf (möglicherweise nicht in höchster Qualitätsstufe, abhängig davon, ob Bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ebenfalls gesetzt ist).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Gibt an, ob ein Benutzer den Inhalt des Dokuments durch Vorgänge ändern darf, die nicht von den Bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) gesteuert werden.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Gibt an, ob ein Benutzer Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren darf, durch Vorgänge, die nicht von Bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) gesteuert werden.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Gibt an, ob ein Benutzer Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, falls Bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ebenfalls gesetzt ist, interaktive Formularfelder (einschließlich Signaturfelder) erstellen oder ändern darf.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Gibt an, ob ein Benutzer vorhandene interaktive Formularfelder (einschließlich Signaturfelder) ausfüllen darf, selbst wenn Bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) nicht gesetzt ist.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Gibt an, ob ein Benutzer Text und Grafiken zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder zu anderen Zwecken extrahieren darf.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Gibt an, ob ein Benutzer das Dokument zusammenstellen darf (Seiten einfügen, drehen oder löschen sowie Lesezeichen oder Miniaturbilder erstellen), selbst wenn Bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) nicht gesetzt ist.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Gibt an, ob ein Benutzer das Dokument zu einer Darstellung drucken darf, aus der eine genaue digitale Kopie des PDF-Inhalts erzeugt werden könnte. Wenn dieses Bit nicht gesetzt ist (und Bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) gesetzt ist), ist das Drucken auf eine niedrigere Darstellungsstufe der Erscheinung beschränkt, möglicherweise mit verringerter Qualität.