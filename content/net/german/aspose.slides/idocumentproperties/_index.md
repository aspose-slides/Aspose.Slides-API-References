---
title: IDocumentProperties
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt die Eigenschaften einer Präsentation dar.
type: docs
weight: 5710
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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lesen/Schreiben String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Gibt die App-Version zurück. Nur-Lesen String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Gibt die Firmen-Eigenschaft zurück oder legt sie fest. Lesen/Schreiben String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Gibt die tatsächliche Anzahl der benutzerdefinierten Eigenschaften in einer Sammlung zurück. Nur-Lesen Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Gibt das Erstellungsdatum einer Präsentation zurück. Die Werte sind in UTC. Lesen/Schreiben DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur-Lesen IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Gibt die Anzahl versteckter Folien in einem Präsentationsdokument an. Nur-Lesen Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. Lesen/Schreiben String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Produzenten in diesem Teil aktualisiert wurden. Der nächste Produzent, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lesen/Schreiben Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Gibt die benutzerdefinierte Eigenschaft zurück, die mit einem angegebenen Namen verknüpft ist. Lesen/Schreiben Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest. Lesen/Schreiben String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lesen/Schreiben DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Gibt den Namen der zuletzt die Präsentation modifizierenden Person zurück oder legt ihn fest. Lesen/Schreiben String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Die Werte sind in UTC. Nur-Lesen im Fall von Presentation.DocumentProperties (da es intern während des Speicherprozesses des IPresentation-Objekts aktualisiert wird). Kann über die von der Methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) zurückgegebene DocumentProperties-Instanz geändert werden. Siehe das Beispiel in der Methodenübersicht [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lesen/Schreiben Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lesen/Schreiben String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Gibt die Gesamtzahl von Ton- oder Videoclips im Dokument an. Nur-Lesen Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder legt ihn fest. Lesen/Schreiben String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Gibt die Anzahl der Folien in einer Präsentation mit Notizen an. Nur-Lesen Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Gibt die Gesamtzahl der im Dokument gefundenen Absätze an, falls zutreffend. Nur-Lesen Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lesen/Schreiben String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. Lesen/Schreiben Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Gibt den Anzeigemodus der Dokumentvorschau an. Setzen Sie dieses Element auf **true**, um die Skalierung der Dokumentvorschau an das Display zu aktivieren. Setzen Sie dieses Element auf **false**, um das Zuschneiden der Dokumentvorschau zu aktivieren, sodass nur Abschnitte angezeigt werden, die zum Display passen. Lesen/Schreiben Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Gibt an, ob die Präsentation zwischen mehreren Personen geteilt wird. Lesen/Schreiben Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument an. Nur-Lesen Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Gibt das Thema einer Präsentation zurück oder legt es fest. Lesen/Schreiben String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lesen/Schreiben String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptuelle Darstellungen von Dokumentabschnitten. Nur-Lesen string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Gibt die gesamte Bearbeitungszeit einer Präsentation an. Lesen/Schreiben TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Gibt die Gesamtzahl der im Dokument enthaltenen Wörter an. Nur-Lesen Int32. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Ruft einen benannten Booleschen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Ruft einen benannten double-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Ruft einen benannten float-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Ruft einen benannten Integer-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Ruft einen benannten String-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften ab (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Setzt eine benannte double-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Setzt eine benannte float-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Setzt eine benannte integer-benutzerdefinierte Eigenschaft. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Setzt eine benannte string-benutzerdefinierte Eigenschaft. |

### Siehe auch

* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->