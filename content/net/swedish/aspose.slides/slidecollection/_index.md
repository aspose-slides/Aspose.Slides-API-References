---
title: SlideCollection
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en samling av bilder.
type: docs
weight: 9990
url: /sv/aspose.slides/slidecollection/
---
## SlideCollection klass

Representerar en samling av bilder.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Returnerar ett värde som indikerar huruvida åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Hämtar elementet på det angivna indexet. Skrivskyddad [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Returnerar en synkroniseringsrot. Skrivskyddad Object. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Lägger till en kopia av en specificerad bild i slutet av den specificerade sektionen. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Lägger till en kopia av en specificerad källbild i slutet av samlingen. Passande layout kommer att väljas automatiskt från den specificerade masteren (passande layout är den layout med samma Type eller Name som layouten för källbilden). Om det inte finns någon passande layout kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Lägger till en ny tom bild i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med hänsyn till PDF-importalternativen. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Kopierar alla element från samlingen till den angivna arrayen. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Returnerar ett index för den specificerade bilden i samlingen. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Infogar en kopia av en specificerad bild på den angivna positionen i samlingen. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Infogar en kopia av en specificerad bild på den angivna positionen i samlingen. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Infogar en kopia av en specificerad källbild på den angivna positionen i samlingen. Passande layout kommer att väljas automatiskt från den specificerade masteren (passande layout är den layout med samma Type eller Name som layouten för källbilden). Om det inte finns någon passande layout kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Infogar en kopia av en specificerad bild på den angivna positionen i samlingen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Tar bort elementet på det angivna indexet i samlingen. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Flyttar bilden från samlingen till den angivna positionen. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Flyttar bilder från samlingen till den angivna positionen. Bilderna placeras med start från index i den ordning de förekommer i listan. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Skapar och returnerar en array med alla bilder i den. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Skapar och returnerar en array med alla bilder från det angivna intervallet. Ett index för den första bilden att lägga till. Ett antal bilder att lägga till. |

### Se också

* klass [DomObject&lt;TParent&gt;](../domobject-1)
* klass [Presentation](../presentation)
* gränssnitt [ISlideCollection](../islidecollection)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->