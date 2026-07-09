---
title: DocumentProperties
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt Eigenschaften einer Präsentation dar.
type: docs
weight: 2790
url: /de/aspose.slides/documentproperties/
---
## DocumentProperties Klasse

Stellt Eigenschaften einer Präsentation dar.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initialisiert eine neue Instanz der Klasse [`DocumentProperties`](../documentproperties). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lese-/Schreib String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Gibt die App-Version zurück. Nur-Lese String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lese-/Schreib String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lese-/Schreib String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lese-/Schreib String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Gibt die Firmen-Eigenschaft zurück oder legt sie fest. Lese-/Schreib String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lese-/Schreib String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lese-/Schreib String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück. Nur-Lese Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lese-/Schreib DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur-Lese IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Gibt die Anzahl der ausgeblendeten Folien in einem Präsentationsdokument zurück. Nur-Lese Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Gibt die Dokument-Eigenschaft HyperlinkBase zurück oder legt sie fest. Lese-/Schreib String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller in diesem Teil aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lese-/Schreib Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lese-/Schreib Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lese-/Schreib String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese-/Schreib DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Gibt den Namen der letzten Person, die eine Präsentation geändert hat, zurück oder legt ihn fest. Lese-/Schreib String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur-Lese im Fall von Presentation.DocumentProperties (da sie intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die von Methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) zurückgegebene DocumentProperties-Instanz geändert werden. Siehe das Beispiel in der Methodenzusammenfassung von [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie es auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreib Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lese-/Schreib String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Gibt die Gesamtzahl der im Dokument vorhandenen Ton- oder Videoclips zurück. Nur-Lese Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder legt ihn fest. Lese-/Schreib String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Gibt die Anzahl der Folien in einer Präsentation mit Notizen zurück. Nur-Lese Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Gibt die Gesamtzahl der im Dokument gefundenen Absätze zurück, falls zutreffend. Nur-Lese Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lese-/Schreib String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. Lese-/Schreib Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Gibt den Anzeigemodus der Dokument-Vorschaubildes an. Setzen Sie dieses Element auf **true**, um die Skalierung des Vorschaubildes an die Anzeige zu aktivieren. Setzen Sie es auf **false**, um das Beschneiden des Vorschaubildes zu aktivieren, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Lese-/Schreib Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese-/Schreib Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. Nur-Lese Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Gibt den Betreff einer Präsentation zurück oder legt ihn fest. Lese-/Schreib String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lese-/Schreib String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Nur-Lese string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Gesamte Bearbeitungszeit einer Präsentation. Lese-/Schreib TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Gibt die Gesamtzahl der im Dokument enthaltenen Wörter zurück. Nur-Lese Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klonen des aktuellen Objekts |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klonen des aktuellen Objekts |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Liest einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Liest einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Liest einen benannten double-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Liest einen benannten float-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Liest einen benannten int-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Liest einen benannten string-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Liest ein Array von Sensitivitätsbezeichnungen aus den benutzerdefinierten Dokumenteigenschaften (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Entfernt eine mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Setzt eine benannte double-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Setzt eine benannte float-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Setzt eine benannte int-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Setzt eine benannte string-benutzerdefinierte Eigenschaft. |

### Beispiele

Das folgende Beispiel zeigt, wie auf integrierte Eigenschaften einer PowerPoint-Präsentation zugegriffen wird.

```csharp
[C#]
// Instanziieren Sie die Presentation-Klasse, die die Präsentation darstellt
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Erstellen Sie eine Referenz auf das IDocumentProperties-Objekt, das mit der Presentation verknüpft ist
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Zeigen Sie die integrierten Eigenschaften an
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
// Instanziieren Sie die Presentation-Klasse, die die Präsentation darstellt
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Erstellen Sie eine Referenz auf das IDocumentProperties-Objekt, das mit der Presentation verknüpft ist
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Setzen Sie die integrierten Eigenschaften
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Speichern Sie Ihre Präsentation in einer Datei
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Siehe Auch

* Schnittstelle [IDocumentProperties](../idocumentproperties)
* Schnittstelle [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->