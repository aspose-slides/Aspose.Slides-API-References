---
title: ISlideCollection
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een verzameling van dia's voor.
type: docs
weight: 7050
url: /nl/aspose.slides/islidecollection/
---
## ISlideCollection interface

Stelt een verzameling van dia’s voor.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Haalt het element op op de opgegeven index. Alleen-lezen [`ISlide`](../islide). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie. Een geschikte lay-out wordt automatisch geselecteerd van de opgegeven master (een geschikte lay-out is de lay-out met hetzelfde Type of dezelfde Naam als de lay-out van de bron-dia). Als er geen geschikte lay-out bestaat, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt een PptxEditException gegooid (als allowCloneMissingLayout false is). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Voegt een nieuwe lege dia toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Maakt dia’s van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Maakt dia’s van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Maakt dia’s van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Maakt dia’s van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Maakt dia’s van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Maakt dia’s van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Maakt dia’s van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Maakt dia’s van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Maakt dia’s van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Maakt dia’s van het PDF-document en voegt ze toe aan het einde van de collectie, rekening houdend met de PDF-importopties. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Retourneert de index van de opgegeven dia in de collectie. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Voegt een kopie van een opgegeven bron-dia in op de opgegeven positie in de collectie. Een geschikte lay-out wordt automatisch geselecteerd van de opgegeven master (een geschikte lay-out is de lay-out met hetzelfde Type of dezelfde Naam als de lay-out van de bron-dia). Als er geen geschikte lay-out bestaat, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt een PptxEditException gegooid (als allowCloneMissingLayout false is). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Maakt dia’s van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Verwijdert het eerste voorkomen van een specifiek object uit de collectie. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Verwijdert het element op de opgegeven index uit de collectie. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Verplaatst een dia in de collectie naar de opgegeven positie. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Verplaatst dia’s in de collectie naar de opgegeven positie. Dia’s worden geplaatst beginnend bij de index in de volgorde waarin ze in de lijst staan. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Maakt een array met alle dia’s en retourneert deze. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Maakt een array met alle dia’s uit het opgegeven bereik en retourneert deze. |

### Zie ook

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->