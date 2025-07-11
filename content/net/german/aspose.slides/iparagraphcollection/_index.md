---
title: IParagraphCollection
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Sammlung von Absätzen dar.
type: docs
weight: 6370
url: /de/aspose.slides/iparagraphcollection/
---

## IParagraphCollection-Schnittstelle

Stellt eine Sammlung von Absätzen dar.

```csharp
public interface IParagraphCollection : IEnumerable<IParagraph>, ISlideComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIEnumerable](../../aspose.slides/iparagraphcollection/asienumerable) { get; } | Gibt die IEnumerable-Schnittstelle zurück. Nur-Lese IEnumerable. |
| [AsISlideComponent](../../aspose.slides/iparagraphcollection/asislidecomponent) { get; } | Ermöglicht den Zugriff auf die Basisschnittstelle ISlideComponent. Nur-Lese [`ISlideComponent`](../islidecomponent). |
| [Count](../../aspose.slides/iparagraphcollection/count) { get; } | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen Elemente zurück. Nur-Lese Int32. |
| [Item](../../aspose.slides/iparagraphcollection/item) { get; } | Gibt das Element am angegebenen Index zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.slides/iparagraphcollection/add#add_1)(IParagraph) | Fügt einen Absatz am Ende der Sammlung hinzu. |
| [Add](../../aspose.slides/iparagraphcollection/add#add)(IParagraphCollection) | Fügt den Inhalt der ParagraphCollection am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/iparagraphcollection/addfromhtml#addfromhtml)(string) | Fügt den Text aus dem angegebenen HTML-String in die Sammlung ein. |
| [AddFromHtml](../../aspose.slides/iparagraphcollection/addfromhtml#addfromhtml_1)(string, IExternalResourceResolver, string) | Fügt den Text aus dem angegebenen HTML-String in die Sammlung ein. |
| [Clear](../../aspose.slides/iparagraphcollection/clear)() | Entfernt alle Elemente aus der Sammlung. |
| [ExportToHtml](../../aspose.slides/iparagraphcollection/exporttohtml)(int, int, ITextToHtmlConversionOptions) | Konvertiert die angegebenen Absätze in HTML und gibt sie als String-Objekt zurück. |
| [Insert](../../aspose.slides/iparagraphcollection/insert#insert)(int, IParagraph) | Fügt einen Absatz an der angegebenen Stelle in die Sammlung ein. |
| [Insert](../../aspose.slides/iparagraphcollection/insert#insert_1)(int, IParagraphCollection) | Fügt den Inhalt der ParagraphCollection an der angegebenen Stelle in die Sammlung ein. |
| [Remove](../../aspose.slides/iparagraphcollection/remove)(IParagraph) | Entfernt die erste Vorkommen eines bestimmten Absatzes. |
| [RemoveAt](../../aspose.slides/iparagraphcollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |

### Siehe Auch

* Schnittstelle [IParagraph](../iparagraph)
* Schnittstelle [ISlideComponent](../islidecomponent)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->