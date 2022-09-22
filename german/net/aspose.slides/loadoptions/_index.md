---
title: LoadOptions
second_title: Aspose.Slides für .NET-API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen z. B. Format oder Standardschriftart beim Laden einer Präsentation.
type: docs
weight: 7170
url: /de/net/aspose.slides/loadoptions/
---
## LoadOptions class

Ermöglicht das Festlegen zusätzlicher Optionen (z. B. Format oder Standardschriftart) beim Laden einer Präsentation.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Erstellt neue Standardladeoptionen. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Erstellt neue Ladeoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Stellt die Optionen dar, die verwendet werden können, um das Handhabungsverhalten von Binary Large Objects (BLOBs) zu verwalten, wie die Verwendung temporärer Dateien oder die maximale Anzahl von BLOBs im Speicher. Diese Optionen dienen dazu, das beste Leistungs-/Speicherverbrauchsverhältnis für eine bestimmte Umgebung oder Anforderungen festzulegen. Ein Binary Large Object (BLOB) sind binäre Daten, die als einzelne Entität gespeichert werden – dh BLOB kann selbst ein Audio, Video oder eine Präsentation sein. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Gibt asiatische Schriftarten zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird. Lesen/SchreibenString . |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Gibt zurück oder legt die normale Schriftart fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lesen/SchreibenString . |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Gibt die verwendete Symbolschrift zurück oder legt sie fest, falls die Quellschrift nicht gefunden wird. Lesen/SchreibenString . |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Gibt Quellen für externe Schriftarten an, die von der Präsentation verwendet werden sollen. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Das Token, das auf Unterbrechungsanforderungen überwacht werden soll.  Dieser Token verwaltet das Ganze[`IPresentation`](../ipresentation)Instanzlebensdauer. Alle lang andauernden Operationen, wie das Laden von oder das Speichern einer Präsentation, werden durch Aufrufen von unterbrochen[`Interrupt`](../interruptiontokensource/interrupt) Methode von der[`InterruptionTokenSource`](../interruptiontokensource) . |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Gibt das Format einer zu ladenden Präsentation zurück oder legt es fest. Lesen/Schreiben[`LoadFormat`](../loadformat) . |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert „true“ bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert werden muss. Der Wert „false“ bedeutet, dass die gesamte verschlüsselte Präsentation geladen werden muss Verwendung des richtigen Passworts. Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert. Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der Eigenschaftswert wahr ist, dann können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Lesen SchreibenBoolean . |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Ruft das Passwort ab oder legt es fest. Lesen/SchreibenString . |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Gibt die Callback-Schnittstelle zurück oder legt sie fest, die das Laden externer Ressourcen verwaltet. Lesen/Schreiben[`IResourceLoadingCallback`](../iresourceloadingcallback) . |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Ruft Optionen für Tabellenkalkulationen ab. Diese Optionen wirken sich beispielsweise auf Berechnungsformeln für Diagramme aus. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Siehe auch

* interface [ILoadOptions](../iloadoptions)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
