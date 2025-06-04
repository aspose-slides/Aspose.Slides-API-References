---
title: LoadOptions
second_title: Aspose.Slides für .NET API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen wie Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 7600
url: /de/aspose.slides/loadoptions/
---

## LoadOptions-Klasse

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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die verwendet werden können, um das Verhalten bei der Handhabung von Binary Large Objects (BLOBs) zu verwalten, wie z.B. die Verwendung temporärer Dateien oder max BLOB-Bytes im Speicher. Diese Optionen zielen darauf ab, das beste Verhältnis von Leistung zu Speicherverbrauch für eine bestimmte Umgebung oder Anforderungen einzurichten. Ein Binary Large Object (BLOB) ist eine binäre Daten, die als eine einzige Einheit gespeichert ist - d.h. BLOB kann eine Audio-, Video- oder Präsentationsdatei selbst sein. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Gibt die asiatische Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-/Schreibzugriff auf String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Gibt die Regulärschriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-/Schreibzugriff auf String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Gibt die Symbolschriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-/Schreibzugriff auf String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Gibt die Standard Sprache für den Text der Präsentation zurück oder legt sie fest. Lese-/Schreibzugriff auf String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestimmt, ob Aspose.Slides während des Ladens der Präsentation alle eingebetteten binären Objekte löschen soll. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Gibt die Quellen für externe Schriftarten an, die von der Präsentation verwendet werden sollen. Diese Schriftarten sind während der gesamten Lebensdauer der Präsentation verfügbar und werden nicht mit anderen Präsentationen geteilt. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Das Token zur Überwachung von Unterbrechungsanforderungen. Dieses Token verwaltet die gesamte Lebensdauer der [`IPresentation`](../ipresentation) Instanz. Jede langlaufende Operation, wie das Laden oder Speichern von Präsentationen, wird durch den Aufruf der Methode [`Interrupt`](../interruptiontokensource/interrupt) der [`InterruptionTokenSource`](../interruptiontokensource) unterbrochen. |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lese-/Schreibzugriff auf [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Ein Wert von true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert werden muss. Ein Wert von false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert. Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert true ist, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lese-/Schreibzugriff auf Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Holt oder legt das Passwort fest. Lese-/Schreibzugriff auf String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Gibt die Callback-Schnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lese-/Schreibzugriff auf [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Holt Optionen für Tabellenkalkulationen. Diese Optionen betreffen beispielsweise die Berechnung von Formeln für Diagramme. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese-/Schreibzugriff auf [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Schnittstelle [ILoadOptions](../iloadoptions)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->