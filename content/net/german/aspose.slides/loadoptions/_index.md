---
title: LoadOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 7860
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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die verwendet werden können, um das Verhalten beim Umgang mit Binary Large Objects (BLOBs) zu steuern, z. B. die Verwendung temporärer Dateien oder die maximale BLOB-Größe im Speicher. Diese Optionen dienen dazu, das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderung einzustellen. Ein Binary Large Object (BLOB) ist ein binäres Datum, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio, Video oder die Präsentation selbst sein. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese/Schreiben String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Gibt die normale Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese/Schreiben String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbol-Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese/Schreiben String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Gibt die Standardsprache für den Präsentationstext zurück oder legt sie fest. Lese/Schreiben String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Gibt die Quellen für externe Schriftarten an, die von der Präsentation verwendet werden sollen. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Das Token zur Überwachung von Unterbrechungsanforderungen. Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](../ipresentation)-Instanz. Jeder langlaufende Vorgang, wie das Laden oder Speichern einer Präsentation, wird über den Aufruf der [`Interrupt`](../interruptiontokensource/interrupt)-Methode des [`InterruptionTokenSource`](../interruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lese/Schreiben [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden und das Passwort ignoriert wird. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen wird. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert immer ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und ist der Eigenschaftswert true, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lese/Schreiben Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Gibt das Passwort zurück oder legt es fest. Lese/Schreiben String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Gibt die Rückruf-Schnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lese/Schreiben [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Ruft Optionen für Tabellenkalkulationen ab. Zum Beispiel beeinflussen diese Optionen die Berechnung von Formeln für Diagramme. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese/Schreiben [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Schnittstelle [ILoadOptions](../iloadoptions)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->