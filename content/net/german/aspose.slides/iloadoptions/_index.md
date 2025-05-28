---
title: ILoadOptions
second_title: Aspose.Slides für .NET API Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 6140
url: /de/aspose.slides/iloadoptions/
---

## ILoadOptions-Schnittstelle

Ermöglicht das Festlegen zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

```csharp
public interface ILoadOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die zur Verwaltung des Verhaltens bei der Verarbeitung von Binary Large Objects (BLOBs) verwendet werden können, z. B. die Verwendung von temporären Dateien oder die maximalen BLOB-Bytes im Arbeitsspeicher. Diese Optionen sind dazu gedacht, ein optimales Verhältnis von Leistung und Speicherverbrauch für eine bestimmte Umgebung oder Anforderungen festzulegen. Ein Binary Large Object (BLOB) ist eine binäre Datenmenge, die als eine einzige Entität gespeichert ist – d. h. ein BLOB kann ein Audio, Video oder die Präsentation selbst sein. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese- und schreibbare Zeichenfolge. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Gibt die reguläre Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese- und schreibbare Zeichenfolge. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbolschriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese- und schreibbare Zeichenfolge. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lese- und schreibbare Zeichenfolge. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestimmt, ob Aspose.Slides alle eingebetteten binären Objekte beim Laden der Präsentation löschen wird. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Gibt Quellen für externe Schriftarten an, die von der Präsentation verwendet werden. Diese Schriftarten sind während der gesamten Lebensdauer der Präsentation verfügbar und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Das Token zur Überwachung von Unterbrechungsanforderungen. Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](../ipresentation) Instanz. Jede langlaufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch Aufruf der [`Interrupt`](../iinterruptiontokensource/interrupt) Methode der [`IInterruptionTokenSource`](../iinterruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Gibt das Format der zu ladenden Präsentation zurück oder legt es fest. Lese- und schreibbare [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft macht Sinn, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert werden muss. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert. Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert true ist, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lese- und schreibbare Boolesche Werte. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Gibt das Passwort zurück oder legt es fest. Lese- und schreibbare Zeichenfolge. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Gibt die Rückruffschnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lese- und schreibbare [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Stellt Optionen dar, die verwendet werden können, um zusätzliches Verhalten von Tabellenkalkulationen anzugeben. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladeprozess fortgesetzt oder abgebrochen wird. Lese- und schreibbare [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe Auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->