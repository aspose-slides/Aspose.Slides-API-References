---
title: IDocumentProperties
second_title: Aspose.Slides für .NET API Referenz
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs
weight: 5510
url: /de/aspose.slides/idocumentproperties/
---

## IDocumentProperties Schnittstelle

Stellt die Eigenschaften einer Präsentation dar.

```csharp
public interface IDocumentProperties
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Gibt die Vorlage einer Anwendung zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Gibt die App-Version zurück. Nur-Lese-Zeichenfolge. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder setzt ihn. Lese-/Schreib-Zeichenfolge. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Gibt die Unternehmens-Eigenschaft zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder setzt ihn. Lese-/Schreib-Zeichenfolge. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder setzt ihn. Lese-/Schreib-Zeichenfolge. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück. Nur-Lese-Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation erstellt wurde. Werte sind in UTC. Lese-/Schreib-DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Gibt die Gruppierung der Dokumentteile und die Anzahl der Teile in jeder Gruppe an. Nur-Lese-IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Gibt die Anzahl der in einem Präsentationsdokument versteckten Folien an. Nur-Lese-Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Gibt die HyperlinkBasis-Dokumenteigenschaft zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil exklusiv in diesem Teil von einem Produzenten aktualisiert wurden. Der nächste Produzent, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den neuen Hyperlinks in diesem Teil aktualisieren. Lese-/Schreib-Boolesch. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Gibt die benutzerdefinierte Eigenschaft zurück oder setzt sie, die mit einem bestimmten Namen verknüpft ist. Lese-/Schreib-Objekt. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lese-/Schreib-DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Gibt den Namen der letzten Person zurück, die eine Präsentation bearbeitet hat, oder setzt ihn. Lese-/Schreib-Zeichenfolge. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur-Lese im Falle von Presentation.DocumentProperties (da es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). Kann über die DocumentProperties-Instanz geändert werden, die durch die Methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) zurückgegeben wird. Bitte siehe das Beispiel in der Zusammenfassung der Methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lese-/Schreib-Boolesch. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Gibt die Gesamtzahl der im Dokument vorhandenen Audio- oder Videoclips an. Nur-Lese-Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder setzt ihn. Lese-/Schreib-Zeichenfolge. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Gibt die Anzahl der Folien in einer Präsentation an, die Notizen enthalten. Nur-Lese-Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Gibt die Gesamtzahl der Absätze in einem Dokument an, falls zutreffend. Nur-Lese-Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder setzt es. Lese-/Schreib-Zeichenfolge. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Gibt die Überarbeitungsnummer der Präsentation zurück oder setzt sie. Lese-/Schreib-Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Gibt den Anzeigemodus des Dokumentminiaturansicht an. Setzen Sie dieses Element auf **true**, um die Skalierung der Dokumentminiaturansicht an die Anzeige zu aktivieren. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokumentminiaturansicht zu aktivieren, sodass nur Abschnitte angezeigt werden, die zu der Anzeige passen. Lese-/Schreib-Boolesch. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lese-/Schreib-Boolesch. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. Nur-Lese-Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Gibt das Thema einer Präsentation zurück oder setzt es. Lese-/Schreib-Zeichenfolge. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder setzt ihn. Lese-/Schreib-Zeichenfolge. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptionelle Darstellungen von Dokumentabschnitten. Nur-Lese-string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Gesamte Bearbeitungszeit einer Präsentation. Lese-/Schreib-TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Gibt die Gesamtzahl der Wörter in einem Dokument an. Nur-Lese-Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Löscht und setzt die Standardwerte für alle integrierten Eigenschaften. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Überprüft, ob eine benutzerdefinierte Eigenschaft mit einem bestimmten Namen vorhanden ist. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Holt einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Holt einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Holt einen benannten double-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Holt einen benannten float-Wert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Holt einen benannten Ganzzahlwert aus den benutzerdefinierten Eigenschaften. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Holt einen benannten Zeichenfolgenwert aus den benutzerdefinierten Eigenschaften. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem bestimmten Namen verknüpft ist. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Setzt eine benannte DateTime benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Setzt eine benannte doppelte benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Setzt eine benannte float benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Setzt eine benannte ganze benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Setzt eine benannte Zeichenfolge benutzerdefinierte Eigenschaft. |

### Siehe auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->