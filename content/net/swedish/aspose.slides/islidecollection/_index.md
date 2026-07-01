---
title: ISlideCollection
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en samling av bilder.
type: docs
weight: 7030
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
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Lägger till en kopia av en angiven bild i slutet av samlingen. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Lägger till en kopia av en angiven bild i slutet av samlingen. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Lägger till en kopia av en angiven bild i slutet av den angivna sektionen. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Lägger till en kopia av en angiven källbild i slutet av samlingen. Ett lämpligt layout väljs automatiskt från den angivna mastern (ett lämpligt layout är det layout som har samma Typ eller Namn som layouten för källbilden). Om det inte finns ett lämpligt layout klonas layouten för källbilden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Lägger till en ny tom bild i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med hänsyn till PDF-importalternativen. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Returnerar ett index för den angivna bilden i samlingen. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Infogar en kopia av en angiven bild på den angivna positionen i samlingen. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Infogar en kopia av en angiven bild på den angivna positionen i samlingen. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Infogar en kopia av en angiven källbild på den angivna positionen i samlingen. Ett lämpligt layout väljs automatiskt från den angivna mastern (ett lämpligt layout är det layout som har samma Typ eller Namn som layouten för källbilden). Om det inte finns ett lämpligt layout klonas layouten för källbilden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Infogar en kopia av en angiven bild på den angivna positionen i samlingen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Tar bort elementet på det angivna indexet i samlingen. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Flyttar bilden från samlingen till den angivna positionen. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Flyttar bilder från samlingen till den angivna positionen. Bilderna placeras med början från index i den ordning de förekommer i listan. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Skapar och returnerar en array med alla bilder i den. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Skapar och returnerar en array med alla bilder från det angivna intervallet i den. |

### Se även

* gränssnitt [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* gränssnitt [ISlide](../islide)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->