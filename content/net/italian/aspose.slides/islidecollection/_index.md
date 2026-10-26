---
title: ISlideCollection
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una raccolta di slide.
type: docs
weight: 7050
url: /it/aspose.slides/islidecollection/
---
## ISlideCollection interfaccia

Rappresenta una raccolta di slide.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Ottiene l'elemento all'indice specificato. Read-only [`ISlide`](../islide). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Aggiunge una copia di una slide specificata alla fine della raccolta. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Aggiunge una copia di una slide specificata alla fine della raccolta. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Aggiunge una copia di una slide specificata alla fine della sezione specificata. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Aggiunge una copia di una slide sorgente specificata alla fine della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Type o Name del layout della slide sorgente). Se non esiste un layout appropriato, il layout della slide sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà generata una PptxEditException (se allowCloneMissingLayout è false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Aggiunge una nuova slide vuota alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Crea slide da testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Crea slide da testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crea slide da testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crea slide da testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crea slide da testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crea slide da testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Crea slide dal documento PDF e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Crea slide dal documento PDF e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Crea slide dal documento PDF e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Crea slide dal documento PDF e le aggiunge alla fine della raccolta considerando le opzioni di importazione PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Restituisce l'indice della slide specificata nella raccolta. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Inserisce una copia di una slide specificata nella posizione indicata della raccolta. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserisce una copia di una slide specificata nella posizione indicata della raccolta. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserisce una copia di una slide sorgente specificata nella posizione indicata della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Type o Name del layout della slide sorgente). Se non esiste un layout appropriato, il layout della slide sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà generata una PptxEditException (se allowCloneMissingLayout è false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Inserisce una copia di una slide specificata nella posizione indicata della raccolta. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Crea slide da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Rimuove l'elemento all'indice specificato della raccolta. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Sposta la slide dalla raccolta nella posizione specificata. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Sposta le slide dalla raccolta nella posizione specificata. Le slide verranno posizionate a partire dall'indice nell'ordine in cui appaiono nella lista. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Crea e restituisce un array contenente tutte le slide. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Crea e restituisce un array con tutte le slide dell'intervallo specificato. |

### Vedi anche

* interfaccia [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfaccia [ISlide](../islide)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->