---
title: IDocumentProperties
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert Eigenschaften einer Präsentation.
type: docs
weight: 5240
url: /de/net/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Repräsentiert Eigenschaften einer Präsentation.

```csharp
public interface IDocumentProperties
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Gibt die Vorlage einer Anwendung zurück oder legt sie fest. Lesen/SchreibenString . |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Gibt die App-Version zurück. SchreibgeschütztString . |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Gibt den Autor einer Präsentation zurück oder legt ihn fest. Lesen/SchreibenString . |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Gibt die Kategorie einer Präsentation zurück oder legt sie fest. Lesen/SchreibenString . |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Gibt die Kommentare einer Präsentation zurück oder setzt sie. Lesen/SchreibenString . |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Gibt die Firmeneigenschaft zurück oder legt sie fest. Lesen/SchreibenString . |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest. Lesen/SchreibenString . |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest. Lesen/SchreibenString . |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Gibt die Anzahl der benutzerdefinierten Eigenschaften zurück, die tatsächlich in einer Sammlung enthalten sind. SchreibgeschütztInt32 . |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation erstellt wurde. Werte sind in UTC. Lesen/SchreibenDateTime . |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Gibt die HyperlinkBase-Dokumenteigenschaft zurück oder legt sie fest. Lesen/SchreibenString . |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück oder legt sie fest. Lesen/SchreibenObject . |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Gibt die Schlüsselwörter einer Präsentation zurück oder setzt sie. Lesen/SchreibenString . |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde. Lesen/SchreibenDateTime . |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Gibt den Namen einer Person zurück, die zuletzt eine Präsentation geändert hat, oder legt ihn fest. Lesen/SchreibenString . |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC.P Schreibgeschützt im Falle von Presentation.DocumentProperties (weil es intern aktualisiert wird, während das IPresentation-Objekt gespeichert wird). Kann über die DocumentProperties-Instanz geändert werden, die von der Methode zurückgegeben wird[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Siehe Beispiel in[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) Methodenzusammenfassung. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Gibt die Manager-Eigenschaft zurück oder legt sie fest. Lesen/SchreibenString . |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Gibt den Namen der Anwendung zurück oder legt ihn fest. Lesen/SchreibenString . |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest. Lesen/SchreibenString . |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest. Lesen/SchreibenInt32 . |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Legt fest, ob die Präsentation von mehreren Personen geteilt wird. Lesen/SchreibenBoolean . |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Gibt das Thema einer Präsentation zurück oder legt es fest. Lesen/SchreibenString . |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Gibt den Titel einer Präsentation zurück oder legt ihn fest. Lesen/SchreibenString . |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Gesamtbearbeitungszeit einer Präsentation. Lesen/SchreibenTimeSpan . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Löscht und legt Standardwerte für alle eingebauten Eigenschaften fest. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Entfernt alle benutzerdefinierten Eigenschaften. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Überprüfen Sie die Geschenke einer benutzerdefinierten Eigenschaft mit einem bestimmten Namen. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Ruft einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Ruft einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Ruft einen benannten Gleitkommawert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Ruft einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Ruft einen benannten Zeichenfolgenwert aus den benutzerdefinierten Eigenschaften ab. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Entfernen Sie eine benutzerdefinierte Eigenschaft, die einem bestimmten Namen zugeordnet ist. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Legt eine benannte boolesche benutzerdefinierte Eigenschaft fest. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Legt eine benannte benutzerdefinierte DateTime-Eigenschaft fest. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Legt eine benannte benutzerdefinierte Double-Eigenschaft fest. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Legt eine benannte benutzerdefinierte Float-Eigenschaft fest. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Legt eine benannte benutzerdefinierte Ganzzahleigenschaft fest. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Legt eine benannte benutzerdefinierte Zeichenfolgeneigenschaft fest. |

### Siehe auch

* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
