---  
title: IDocumentProperties
second_title: Aspose.Slides für .NET API Referenz  
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs  
weight: 5510  
url: /de/aspose.slides/idocumentproperties/
---  
  
## IDocumentProperties-Schnittstelle  
  
Stellt die Eigenschaften einer Präsentation dar.  
  
```csharp  
public interface IDocumentProperties  
```  
  
## Eigenschaften  
  
| Name | Beschreibung |  
| --- | --- |  
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Gibt das Template einer Anwendung zurück oder setzt es. Lese-/Schreibzugriff auf String. |  
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Gibt die App-Version zurück. Nur-Lesezugriff auf String. |  
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff auf String. |  
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder setzt sie. Lese-/Schreibzugriff auf String. |  
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder setzt sie. Lese-/Schreibzugriff auf String. |  
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Gibt die Unternehmensangabe zurück oder setzt sie. Lese-/Schreibzugriff auf String. |  
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff auf String. |  
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff auf String. |  
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück. Nur-Lesezugriff auf Int32. |  
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation erstellt wurde. Werte sind in UTC. Lese-/Schreibzugriff auf DateTime. |  
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur-Lesezugriff auf IHeadingPair[]. |  
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Gibt die Anzahl der versteckten Folien in einem Präsentationsdokument an. Nur-Lesezugriff auf Int32. |  
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Gibt die HyperlinkBase-Dokumenteneigenschaft zurück oder setzt sie. Lese-/Schreibzugriff auf String. |  
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich in diesem Teil von einem Erzeuger aktualisiert wurden. Der nächste Erzeuger, der dieses Dokument öffnet, muss die Hyperlink-Beziehungen mit den neuen Hyperlinks, die in diesem Teil angegeben sind, aktualisieren. Lese-/Schreibzugriff auf Boolean. |  
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Gibt die benutzerdefinierte Eigenschaft zurück oder setzt sie, die mit einem angegebenen Namen verknüpft ist. Lese-/Schreibzugriff auf Object. |  
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. Lese-/Schreibzugriff auf String. |  
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese-/Schreibzugriff auf DateTime. |  
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Gibt den Namen der letzten Person zurück oder setzt ihn, die eine Präsentation geändert hat. Lese-/Schreibzugriff auf String. |  
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur-Lesezugriff im Fall von Presentation.DocumentProperties (da es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die Dokumenteigenschafteninstanz geändert werden, die von der Methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) zurückgegeben wird. Bitte sehen Sie sich das Beispiel in der Zusammenfassung der Methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) an. |  
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Gibt an, ob Hyperlinks in einem Dokument auf dem neuesten Stand sind. Setzen Sie dieses Element auf **true**, um anzugeben, dass Hyperlinks aktualisiert sind. Setzen Sie dieses Element auf **false**, um anzugeben, dass Hyperlinks veraltet sind. Lese-/Schreibzugriff auf Boolean. |  
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder setzt sie. Lese-/Schreibzugriff auf String. |  
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Gibt die Gesamtzahl der im Dokument vorhandenen Audio- oder Videoclips an. Nur-Lesezugriff auf Int32. |  
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder setzt ihn. Lese-/Schreibzugriff auf String. |  
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Gibt die Anzahl der Folien in einer Präsentation an, die Notizen enthalten. Nur-Lesezugriff auf Int32. |  
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Gibt die Gesamtzahl der Absätze im Dokument an, sofern zutreffend. Nur-Lesezugriff auf Int32. |  
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. Lese-/Schreibzugriff auf String. |  
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Gibt die Revisionsnummer der Präsentation zurück oder setzt sie. Lese-/Schreibzugriff auf Int32. |  
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Gibt den Anzeige-Modus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um das Skalieren der Dokumentvorschau für die Anzeige zu aktivieren. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Lese-/Schreibzugriff auf Boolean. |  
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese-/Schreibzugriff auf Boolean. |  
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. Nur-Lesezugriff auf Int32. |  
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Gibt das Thema einer Präsentation zurück oder setzt es. Lese-/Schreibzugriff auf String. |  
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder setzt ihn. Lese-/Schreibzugriff auf String. |  
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptionelle Darstellungen von Dokumentabschnitten. Nur-Lesezugriff auf string[]. |  
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Gesamtbearbeitungszeit einer Präsentation. Lese-/Schreibzugriff auf TimeSpan. |  
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Gibt die Gesamtzahl der Wörter in einem Dokument an. Nur-Lesezugriff auf Int32. |  
  
## Methoden  
  
| Name | Beschreibung |  
| --- | --- |  
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |  
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |  
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |  
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück. |  
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Holt einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |  
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Holt einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |  
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Holt einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften. |  
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Holt einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften. |  
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Holt einen benannten Integer-Wert aus den benutzerdefinierten Eigenschaften. |  
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Holt einen benannten String-Wert aus den benutzerdefinierten Eigenschaften. |  
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |  
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |  
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Setzt eine benannte DateTime benutzerdefinierte Eigenschaft. |  
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Setzt eine benannte Double benutzerdefinierte Eigenschaft. |  
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Setzt eine benannte Float benutzerdefinierte Eigenschaft. |  
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Setzt eine benannte Integer benutzerdefinierte Eigenschaft. |  
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Setzt eine benannte String benutzerdefinierte Eigenschaft. |  
  
### Siehe auch  
  
* Namespace [Aspose.Slides](../../aspose.slides)  
* Assembly [Aspose.Slides](../../)  
  
<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  