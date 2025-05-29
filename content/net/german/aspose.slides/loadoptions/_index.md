---
title: LoadOptions
second_title: Aspose.Sildes für .NET API Referenz
description: Ermöglicht die Angabe zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 7600
url: /de/aspose.slides/loadoptions/
---

## LoadOptions-Klasse

Ermöglicht die Angabe zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Erstellt neue standardmäßige Ladeoptionen. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Erstellt neue Ladeoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die verwendet werden können, um das Verhalten bei der Verwaltung von Binary Large Objects (BLOBs) zu steuern, wie z. B. die Verwendung von temporären Dateien oder die maximalen BLOB-Bytes im Speicher. Diese Optionen sind darauf ausgelegt, das beste Verhältnis zwischen Leistung und Speicherverbrauch für eine bestimmte Umgebung oder Anforderungen zu erzielen. Ein Binary Large Object (BLOB) ist eine binäre Datenmenge, die als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio, ein Video oder die Präsentation selbst sein. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellet Schriftart nicht gefunden wird. Lese-/Schreibzugriff auf String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Gibt die reguläre Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellet Schriftart nicht gefunden wird. Lese-/Schreibzugriff auf String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbolschriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellet Schriftart nicht gefunden wird. Lese-/Schreibzugriff auf String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lese-/Schreibzugriff auf String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestimmt, ob Aspose.Slides alle eingebetteten binären Objekte beim Laden der Präsentation löschen wird. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Gibt die Quellen für externe Schriftarten an, die von der Präsentation verwendet werden. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Das Token zur Überwachung von Unterbrechungsanforderungen. Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](../ipresentation)-Instanz. Jede lang laufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch den Aufruf der Methode [`Interrupt`](../interruptiontokensource/interrupt) von [`InterruptionTokenSource`](../interruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lese-/Schreibzugriff auf [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft macht Sinn, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert von true bedeutet, dass nur die Dokumenten Eigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert werden muss. Der Wert von false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert. Wenn die Dokumenten Eigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert true ist, können die Dokumenten Eigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lese-/Schreibzugriff auf Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Gibt das Passwort zurück oder legt es fest. Lese-/Schreibzugriff auf String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Gibt die Callback-Schnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lese-/Schreibzugriff auf [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Gibt die Optionen für Tabellenkalkulationen zurück. Diese Optionen wirken sich beispielsweise auf die Berechnung von Formeln für Diagramme aus. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladeprozess fortgesetzt oder abgebrochen wird. Lese-/Schreibzugriff auf [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Schnittstelle [ILoadOptions](../iloadoptions)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->