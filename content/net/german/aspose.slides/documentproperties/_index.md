---
title: DocumentProperties
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs
weight: 2700
url: /de/aspose.slides/documentproperties/
---

## DocumentProperties-Klasse

Stellt die Eigenschaften einer Präsentation dar.

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
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Gibt die Vorlage einer Anwendung zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Gibt die App-Version zurück. Nur Lesezugriff String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Gibt die Unternehmens-Eigenschaft zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück. Nur Lesezugriff Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lese-/Schreibzugriff DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur Lesezugriff IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Gibt die Anzahl der in einem Präsentationsdokument versteckten Folien zurück. Nur Lesezugriff Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil exklusiv in diesem Teil von einem Ersteller aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den neuen Hyperlinks, die in diesem Teil angegeben sind, aktualisieren. Lese-/Schreibzugriff Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Gibt die benutzerdefinierte Eigenschaft zurück oder setzt sie, die mit einem angegebenen Namen verknüpft ist. Lese-/Schreibzugriff Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese-/Schreibzugriff DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Gibt den Namen der letzten Person zurück oder setzt ihn, die eine Präsentation geändert hat. Lese-/Schreibzugriff String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur Lesezugriff im Falle von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die DocumentProperties-Instanz geändert werden, die von der Methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) zurückgegeben wird. Bitte siehe das Beispiel in der Zusammenfassung der Methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzugeben, dass Hyperlinks aktualisiert sind. Setzen Sie dieses Element auf **false**, um anzugeben, dass Hyperlinks veraltet sind. Lese-/Schreibzugriff Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Gibt die Gesamtzahl der im Dokument vorhandenen Audio- oder Video-Clips zurück. Nur Lesezugriff Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder setzt ihn. Lese-/Schreibzugriff String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Gibt die Anzahl der Folien in einer Präsentation zurück, die Notizen enthalten. Nur Lesezugriff Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Gibt die Gesamtzahl der im Dokument gefundenen Absätze zurück, sofern zutreffend. Nur Lesezugriff Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. Lese-/Schreibzugriff String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Gibt die Revisionsnummer der Präsentation zurück oder setzt sie. Lese-/Schreibzugriff Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Gibt den Anzeigemodus der Dokumentminiatur an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokumentminiatur für die Anzeige zu aktivieren. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokumentminiatur zu aktivieren, um nur die Abschnitte anzuzeigen, die zur Anzeige passen. Lese-/Schreibzugriff Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese-/Schreibzugriff Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. Nur Lesezugriff Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Gibt das Thema einer Präsentation zurück oder setzt es. Lese-/Schreibzugriff String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptionelle Darstellungen von Dokumentabschnitten. Nur Lesezugriff string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Gesamte Bearbeitungszeit einer Präsentation. Lese-/Schreibzugriff TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Gibt die Gesamtzahl der in einem Dokument enthaltenen Wörter zurück. Nur Lesezugriff Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klont das aktuelle Objekt |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klont das aktuelle Objekt |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Überprüft die Existenz einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Gibt einen benutzerdefinierten Eigenschaftsnamen an dem angegebenen Index zurück. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Holt einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Holt einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Holt einen benannten double-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Holt einen benannten float-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Holt einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Holt einen benannten String-Wert aus den benutzerdefinierten Eigenschaften. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem bestimmten Namen verknüpft ist. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Setzt eine benannte DateTime benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Setzt eine benannte double benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Setzt eine benannte float benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Setzt eine benannte string benutzerdefinierte Eigenschaft. |

### Beispiele

Das folgende Beispiel zeigt, wie man auf integrierte Eigenschaften einer PowerPoint-Präsentation zugreift.

```csharp
[C#]
// Instanziieren Sie die Präsentationsklasse, die die Präsentation darstellt
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Erstellen Sie eine Referenz auf das IDocumentProperties-Objekt, das mit der Präsentation verknüpft ist
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Anzeigen der integrierten Eigenschaften
	Console.WriteLine("Kategorie : " + documentProperties.Category);
	Console.WriteLine("Aktueller Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Erstellungsdatum : " + documentProperties.CreatedTime);
	Console.WriteLine("Autor : " + documentProperties.Author);
	Console.WriteLine("Beschreibung : " + documentProperties.Comments);
}
```

Das folgende Beispiel zeigt, wie man integrierte Eigenschaften einer PowerPoint-Präsentation modifiziert.

```csharp
[C#]
// Instanziieren Sie die Präsentationsklasse, die die Präsentation darstellt
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Erstellen Sie eine Referenz auf das IDocumentProperties-Objekt, das mit der Präsentation verknüpft ist
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Setzen der integrierten Eigenschaften
	documentProperties.Author = "Aspose.Slides für .NET";
	documentProperties.Title = "Ändern der Präsentationseigenschaften";
	documentProperties.Subject = "Aspose Thema";
	// Speichern Sie Ihre Präsentation in einer Datei
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Schnittstelle [IDocumentProperties](../idocumentproperties)
* Schnittstelle [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->