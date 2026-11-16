---
title: DocumentProperties
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs
weight: 2810
url: /de/aspose.slides/documentproperties/
---
## DocumentProperties Klasse

Stellt die Eigenschaften einer Präsentation dar.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Konstruktoren

| Name | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initialisiert eine neue Instanz der Klasse [`DocumentProperties`](../documentproperties). |

## Eigenschaften

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lese/Schreib String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Gibt die App-Version zurück. Nur-Lesen String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lese/Schreib String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lese/Schreib String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lese/Schreib String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Gibt die Firmenangabe zurück oder legt sie fest. Lese/Schreib String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lese/Schreib String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lese/Schreib String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück. Nur-Lesen Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lese/Schreib DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur-Lesen IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Gibt die Anzahl versteckter Folien in einem Präsentationsdokument zurück. Nur-Lesen Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Gibt die Dokument-Eigenschaft HyperlinkBase zurück oder legt sie fest. Lese/Schreib String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lese/Schreib Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Gibt die benutzerdefinierte Eigenschaft mit einem angegebenen Namen zurück oder legt sie fest. Lese/Schreib Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lese/Schreib String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese/Schreib DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Gibt den Namen der zuletzt die Präsentation bearbeitenden Person zurück oder legt ihn fest. Lese/Schreib String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur-Lesen im Fall von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die von Methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) zurückgegebene DocumentProperties-Instanz geändert werden. Siehe das Beispiel in der Methodenzusammenfassung [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie es auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese/Schreib Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lese/Schreib String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Gibt die Gesamtzahl von Ton- oder Videoclips zurück, die im Dokument enthalten sind. Nur-Lesen Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder legt ihn fest. Lese/Schreib String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Gibt die Anzahl der Folien einer Präsentation zurück, die Notizen enthalten. Nur-Lesen Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Gibt die Gesamtzahl der Absätze im Dokument zurück, falls zutreffend. Nur-Lesen Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lese/Schreib String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. Lese/Schreib Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Gibt den Anzeigemodus der Dokument-Miniaturansicht an. Setzen Sie dieses Element auf **true**, um das Skalieren der Miniaturansicht an das Display zu aktivieren. Setzen Sie es auf **false**, um das Zuschneiden der Miniaturansicht so zu aktivieren, dass nur zum Display passende Abschnitte angezeigt werden. Lese/Schreib Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Gibt an, ob die Präsentation von mehreren Personen gemeinsam genutzt wird. Lese/Schreib Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. Nur-Lesen Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Gibt das Thema einer Präsentation zurück oder legt es fest. Lese/Schreib String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lese/Schreib String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Nur-Lesen string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Gesamte Bearbeitungszeit einer Präsentation. Lese/Schreib TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Gibt die Gesamtzahl der Wörter im Dokument zurück. Nur-Lesen Int32. |

## Methoden

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klont das aktuelle Objekt |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klont das aktuelle Objekt |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Ruft einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Ruft einen benannten double-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Ruft einen benannten float-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Ruft einen benannten Integer-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Ruft einen benannten String-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Gibt ein Array von Sensitivitäts-Labels aus den benutzerdefinierten Dokumenteigenschaften zurück (Microsoft Information Protection SDK-Metadaten). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verbunden ist. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Setzt eine benannte double-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Setzt eine benannte float-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Setzt eine benannte Integer-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Setzt eine benannte String-benutzerdefinierte Eigenschaft. |

### Beispiele

Das folgende Beispiel zeigt, wie auf integrierte Eigenschaften einer PowerPoint-Präsentation zugegriffen wird.

```csharp
[C#]
// Instanziiert die Presentation-Klasse, die die Präsentation darstellt
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Erstellt eine Referenz zum IDocumentProperties-Objekt, das mit der Presentation verknüpft ist
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Gibt die integrierten Eigenschaften aus
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Das folgende Beispiel zeigt, wie integrierte Eigenschaften einer PowerPoint-Präsentation geändert werden.

```csharp
[C#]
// Instanziiert die Presentation-Klasse, die die Präsentation darstellt
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Erstellt eine Referenz zum IDocumentProperties-Objekt, das mit der Presentation verknüpft ist
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Setzt die integrierten Eigenschaften
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Speichert die Präsentation in einer Datei
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->