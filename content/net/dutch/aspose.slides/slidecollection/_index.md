---
title: SlideCollection
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een collectie van dia's voor.
type: docs
weight: 9970
url: /nl/aspose.slides/slidecollection/
---
## SlideCollection klasse

Stelt een collectie van dia's voor.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Haalt het element op op de opgegeven index. Alleen-lezen [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Geeft een synchronisatiewortel terug. Alleen-lezen Object. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie. Een passende layout wordt automatisch geselecteerd uit de opgegeven master (passende layout is de layout met hetzelfde Type of dezelfde Name als de layout van de bron-dia). Als er geen passende layout is, wordt de layout van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout false is). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Voegt een nieuwe lege dia toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie met inachtneming van de pdf-importopties. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Geeft een enumerator terug die door de collectie iterereert. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Geeft de index terug van de opgegeven dia in de collectie. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Voegt een kopie van een opgegeven bron-dia in op de opgegeven positie in de collectie. Een passende layout wordt automatisch geselecteerd uit de opgegeven master (passende layout is de layout met hetzelfde Type of dezelfde Name als de layout van de bron-dia). Als er geen passende layout is, wordt de layout van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout false is). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Verwijdert de eerste instantie van een specifiek object uit de collectie. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Verwijdert het element op de opgegeven index uit de collectie. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Verplaatst een dia in de collectie naar de opgegeven positie. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Verplaatst dia's in de collectie naar de opgegeven positie. Dia's worden geplaatst beginnend vanaf de index in de volgorde waarin ze in de lijst staan. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Maakt een array met alle dia's en geeft deze terug. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Maakt een array met alle dia's uit het opgegeven bereik en geeft deze terug. Een index van de eerste toe te voegen dia. Een aantal toe te voegen dia's. |

### Zie ook

* klasse [DomObject&lt;TParent&gt;](../domobject-1)
* klasse [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->