---
title: ILoadOptions
second_title: Aspose.Slides für .NET API-Referenz
description: Ermöglicht die Angabe zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 6140
url: /de/aspose.slides/iloadoptions/
---

## ILoadOptions-Schnittstelle

Ermöglicht die Angabe zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

```csharp
public interface ILoadOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die zur Verwaltung des Verhaltens beim Umgang mit Binary Large Objects (BLOBs) verwendet werden können, wie z. B. die Verwendung von temporären Dateien oder die maximalen BLOB-Bytes im Speicher. Diese Optionen sind darauf ausgelegt, das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderungen zu konfigurieren. Ein Binary Large Object (BLOB) ist eine binäre Datenmenge, die als einzelne Entität gespeichert wird - z. B. kann ein BLOB ein Audio-, Video- oder Präsentationsobjekt selbst sein. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese- und Schreibzeichenfolge. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Gibt die reguläre Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese- und Schreibzeichenfolge. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbolschriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese- und Schreibzeichenfolge. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lese- und Schreibzeichenfolge. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestimmt, ob Aspose.Slides alle eingebetteten binären Objekte beim Laden der Präsentation löschen soll. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Gibt die Quellen für externe Schriftarten an, die von der Präsentation verwendet werden sollen. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Das Token, um Unterbrechungsanforderungen zu überwachen. Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](../ipresentation)-Instanz. Jede langandauernde Operation, wie das Laden oder Speichern einer Präsentation, wird über den Aufruf der [`Interrupt`](../iinterruptiontokensource/interrupt)-Methode der [`IInterruptionTokenSource`](../iinterruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Gibt das Format einer Präsentation zurück oder legt es fest, die geladen werden soll. Lese- und Schreib[`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft macht Sinn, wenn die Präsentationsdatei passwortgeschützt ist. Ein Wert von true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert werden muss. Ein Wert von false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert. Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert true ist, können die Dokumenteigenschaften nicht geladen werden, und es wird eine Ausnahme ausgelöst. Lese- und Schreibboolesch. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Ruft das Passwort ab oder legt es fest. Lese- und Schreibzeichenfolge. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Gibt das Callback-Interface zurück oder legt es fest, das das Laden externer Ressourcen verwaltet. Lese- und Schreib[`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Stellt Optionen dar, die verwendet werden können, um zusätzliches Verhalten von Tabellenkalkulationen anzugeben. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladeprozess fortgesetzt oder abgebrochen wird. Lese- und Schreib[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->