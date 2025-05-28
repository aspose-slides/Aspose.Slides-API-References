---
title: DocumentProperties
second_title: Aspose.Slides für .NET API Referenz
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
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Gibt das Template einer Anwendung zurück oder setzt es. Lese-/Schreibwert String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Gibt die App-Version zurück. Schreibgeschützter String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder setzt ihn. Lese-/Schreibwert String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder setzt sie. Lese-/Schreibwert String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder setzt sie. Lese-/Schreibwert String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Gibt die Unternehmens-Eigenschaft zurück oder setzt sie. Lese-/Schreibwert String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. Lese-/Schreibwert String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. Lese-/Schreibwert String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Gibt die Anzahl der benutzerdefinierten Eigenschaften zurück, die tatsächlich in einer Sammlung enthalten sind. Schreibgeschützter Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation erstellt wurde. Werte sind in UTC. Lese-/Schreibwert DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Schreibgeschützter IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Gibt die Anzahl der versteckten Folien in einem Präsentationsdokument zurück. Schreibgeschützter Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Gibt die HyperlinkBase-Dokumenteneigenschaft zurück oder setzt sie. Lese-/Schreibwert String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich in diesem Teil von einem Produzenten aktualisiert wurden. Der nächste Produzent, der dieses Dokument öffnet, wird die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lese-/Schreibwert Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Gibt die benutzerdefinierte Eigenschaft zurück oder setzt sie, die mit einem angegebenen Namen verknüpft ist. Lese-/Schreibwert Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. Lese-/Schreibwert String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese-/Schreibwert DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Gibt den Namen der letzten Person zurück oder setzt ihn, die eine Präsentation geändert hat. Lese-/Schreibwert String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Schreibgeschützt im Fall von Presentation.DocumentProperties (da es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die DocumentProperties-Instanz geändert werden, die von der Methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) zurückgegeben wird. Bitte siehe das Beispiel in der Zusammenfassung der Methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreibwert Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder setzt sie. Lese-/Schreibwert String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Gibt die Gesamtzahl der im Dokument vorhandenen Audio- oder Video-Clips zurück. Schreibgeschützter Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder setzt ihn. Lese-/Schreibwert String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Gibt die Anzahl der Folien in einer Präsentation zurück, die Notizen enthalten. Schreibgeschützter Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Gibt die Gesamtzahl der Absätze in einem Dokument zurück, sofern zutreffend. Schreibgeschützter Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. Lese-/Schreibwert String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Gibt die Überarbeitungsnummer der Präsentation zurück oder setzt sie. Lese-/Schreibwert Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Gibt den Anzeigemodus der Dokumentminiatur an. Setzen Sie dieses Element auf **true**, um die Skalierung der Dokumentminiatur anzuzeigen. Setzen Sie dieses Element auf **false**, um die Dokumentminiatur zu beschneiden, damit nur die Teile angezeigt werden, die in die Anzeige passen. Lese-/Schreibwert Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese-/Schreibwert Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. Schreibgeschützter Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Gibt das Thema einer Präsentation zurück oder setzt es. Lese-/Schreibwert String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder setzt ihn. Lese-/Schreibwert String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptionelle Darstellungen von Dokumentabschnitten. Schreibgeschützter string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Gesamtbearbeitungszeit einer Präsentation. Lese-/Schreibwert TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Gibt die Gesamtzahl der im Dokument enthaltenen Wörter zurück. Schreibgeschützter Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Löscht alle integrierten Eigenschaften und setzt die Standardwerte. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klont das aktuelle Objekt |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klont das aktuelle Objekt |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Gibt einen benutzerdefinierten Eigenschaftsnamen an einem angegebenen Index zurück. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Holt einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Holt einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Holt einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Holt einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Holt einen benannten Integer-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Holt einen benannten String-Wert aus den benutzerdefinierten Eigenschaften. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Setzt eine benannte DateTime benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Setzt eine benannte Double benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Setzt eine benannte Float benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Setzt eine benannte Integer benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Setzt eine benannte String benutzerdefinierte Eigenschaft. |

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

Das folgende Beispiel zeigt, wie man die integrierten Eigenschaften einer PowerPoint-Präsentation ändert.

```csharp
[C#]
// Instanziieren Sie die Präsentationsklasse, die die Präsentation darstellt
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Erstellen Sie eine Referenz auf das IDocumentProperties-Objekt, das mit der Präsentation verknüpft ist
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Setzen Sie die integrierten Eigenschaften
	documentProperties.Author = "Aspose.Slides für .NET";
	documentProperties.Title = "Ändern von Präsentationseigenschaften";
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