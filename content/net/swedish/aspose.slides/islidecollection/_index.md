---
title: ISlideCollection
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en samling av bilder.
type: docs
weight: 7070
url: /sv/aspose.slides/islidecollection/
---
## ISlideCollection gränssnitt

Representerar en samling av bilder.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Hämtar elementet på det angivna indexet. Skrivskyddad [`ISlide`](../islide). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Lägger till en kopia av en angiven slide i slutet av samlingen. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Lägger till en kopia av en angiven slide i slutet av samlingen. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Lägger till en kopia av en angiven slide i slutet av den angivna sektionen. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Lägger till en kopia av en angiven källslide i slutet av samlingen. Lämpligt layout väljs automatiskt från den angivna master (lämpligt layout är layouten med samma Type eller Name som layouten för källsliden). Om det inte finns någon lämplig layout klonas layouten för källsliden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Lägger till en ny tom slide i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Skapar slides från HTML text och lägger dem till i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Skapar slides från HTML text och lägger dem till i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Skapar slides från HTML text och lägger dem till i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Skapar slides från HTML text och lägger dem till i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Skapar slides från HTML text och lägger dem till i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Skapar slides från HTML text och lägger dem till i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Skapar slides från PDF-dokumentet och lägger dem till i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Skapar slides från PDF-dokumentet och lägger dem till i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Skapar slides från PDF-dokumentet och lägger dem till i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Skapar slides från PDF-dokumentet och lägger dem till i slutet av samlingen med hänsyn till pdf-importalternativen. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Returnerar ett index för den angivna slide i samlingen. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Infogar en kopia av en angiven slide på den angivna positionen i samlingen. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Infogar en kopia av en angiven slide på den angivna positionen i samlingen. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Infogar en kopia av en angiven källslide på den angivna positionen i samlingen. Lämpligt layout väljs automatiskt från den angivna master (lämpligt layout är layouten med samma Type eller Name som layouten för källsliden). Om det inte finns någon lämplig layout klonas layouten för källsliden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Infogar en kopia av en angiven slide på den angivna positionen i samlingen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Skapar slides från HTML text och infogar dem i samlingen på den angivna positionen. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Tar bort elementet på det angivna indexet i samlingen. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Flyttar slide från samlingen till den angivna positionen. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Flyttar slides från samlingen till den angivna positionen. Slides placeras med start från index i den ordning de förekommer i listan. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Skapar och returnerar en array med alla slides i den. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Skapar och returnerar en array med alla slides från det angivna intervallet i den. |

### Se även

* gränssnitt [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* gränssnitt [ISlide](../islide)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->