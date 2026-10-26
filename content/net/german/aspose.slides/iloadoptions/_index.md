---
title: ILoadOptions
second_title: Aspose.Sildes für .NET API Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 6340
url: /de/aspose.slides/iloadoptions/
---
## ILoadOptions Schnittstelle

Ermöglicht das Angeben zusätzlicher Optionen (wie Format oder Standardschriftart) beim Laden einer Präsentation.

```csharp
public interface ILoadOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die verwendet werden können, um das Verhalten der Verarbeitung von Binary Large Objects (BLOBs) zu steuern, z. B. die Verwendung temporärer Dateien oder die maximale BLOB-Größe im Speicher. Diese Optionen sollen das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung festlegen. Ein Binary Large Object (BLOB) ist ein Binärdaten, das als einzelne Entität gespeichert wird – d. h. ein BLOB kann ein Audio, Video oder die Präsentation selbst sein. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-Schreib String. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Gibt die reguläre Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-Schreib String. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbol-Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-Schreib String. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lese/Schreib String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Gibt die Quellen für externe Schriftarten an, die von der Präsentation verwendet werden. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Das Token zur Überwachung von Unterbrechungsanforderungen. Dieses Token verwaltet die gesamte Laufzeit der [`IPresentation`](../ipresentation)-Instanz. Jeder lang laufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird durch Aufruf der [`Interrupt`](../iinterruptiontokensource/interrupt)-Methode des [`IInterruptionTokenSource`](../iinterruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Gibt das zu ladende Präsentationsformat zurück oder legt es fest. Lese/Schreib [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei durch ein Passwort geschützt ist. Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden dürfen und das Passwort ignoriert werden muss. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert immer ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und ist der Eigenschaftswert true, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lese-Schreib Boolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Gibt das Passwort zurück oder legt es fest. Lese-Schreib String. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Gibt die Callback-Schnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lese/Schreib [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Stellt Optionen dar, die verwendet werden können, um das Verhalten zusätzlicher Tabellenkalkulationen festzulegen. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese/Schreib [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe Auch

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->