---
title: ILoadOptions
second_title: Aspose.Sildes für .NET API Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 6360
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
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die zur Verwaltung des Verhaltens von Binary Large Objects (BLOBs) verwendet werden können, z. B. die Verwendung temporärer Dateien oder maximaler BLOB-Bytes im Speicher. Diese Optionen sollen das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung festlegen. Ein Binary Large Object (BLOB) ist ein binäres Datum, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio, Video oder die Präsentation selbst sein. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-schreib String. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Gibt die reguläre Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-schreib String. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbol-Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-schreib String. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lese-schreib String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Legt fest, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Gibt die Quellen für externe Schriftarten an, die von der Präsentation verwendet werden. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Das Token zur Überwachung von Unterbrechungsanfragen. Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](../ipresentation)-Instanz. Jede langlaufende Operation, wie das Laden oder Speichern einer Präsentation, wird durch Aufrufen der [`Interrupt`](../iinterruptiontokensource/interrupt)-Methode des [`IInterruptionTokenSource`](../iinterruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lese-schreib [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert wird. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert immer ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und ist der Eigenschaftswert true, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lese-schreib Boolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Liest oder setzt das Passwort. Lese-schreib String. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Gibt die Rückruffunktionsschnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lese-schreib [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenblatt-Verhalten festzulegen. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese-schreib [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->