---
title: LoadOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 7840
url: /de/aspose.slides/loadoptions/
---
## LoadOptions Klasse

Ermöglicht das Festlegen zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Erstellt neue Standard-Ladeoptionen. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Erstellt neue Ladeoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die zur Verwaltung des Verhaltens von Binary Large Objects (BLOBs) verwendet werden können, z. B. die Verwendung temporärer Dateien oder die maximale Anzahl von BLOB-Bytes im Speicher. Diese Optionen sollen das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung festlegen. Ein Binary Large Object (BLOB) ist ein Binärdaten, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann Audio, Video oder die Präsentation selbst sein. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lesen/Schreiben String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Gibt die Standardschriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lesen/Schreiben String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbolschriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lesen/Schreiben String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Gibt die Standardsprache für Präsentationstext zurück oder legt sie fest. Lesen/Schreiben String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestimmt, ob Aspose.Slides beim Laden einer Präsentation alle eingebetteten Binärobjekte löscht. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Legt die Quellen für externe Schriftarten fest, die von der Präsentation verwendet werden. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Das Token zum Überwachen von Unterbrechungsanfragen. Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](../ipresentation)-Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird durch Aufruf der [`Interrupt`](../interruptiontokensource/interrupt)-Methode des [`InterruptionTokenSource`](../interruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lesen/Schreiben [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert wird. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert stets ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und ist der Eigenschaftswert true, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lesen/Schreiben Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Gibt das Passwort zurück oder legt es fest. Lesen/Schreiben String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Gibt die Rückruffläche zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lesen/Schreiben [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Ruft Optionen für Tabellenkalkulationen ab. Beispielsweise beeinflussen diese Optionen die Berechnung von Formeln für Diagramme. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Schnittstelle [ILoadOptions](../iloadoptions)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->