---
title: SlideCollection
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una raccolta di diapositive.
type: docs
weight: 9970
url: /it/aspose.slides/slidecollection/
---
## SlideCollection classe

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Ottiene il numero di elementi effettivamente contenuti nella raccolta. Sola lettura Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Sola lettura Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Ottiene l'elemento all'indice specificato. Sola lettura [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Restituisce una radice di sincronizzazione. Sola lettura Object. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Aggiunge una copia di una diapositiva specificata alla fine della raccolta. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Aggiunge una copia di una diapositiva specificata alla fine della raccolta. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Aggiunge una copia di una diapositiva sorgente specificata alla fine della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout è false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Aggiunge una nuova diapositiva vuota alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta tenendo conto delle opzioni di importazione PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Restituisce un enumeratore che itera attraverso la raccolta. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Restituisce l'indice della diapositiva specificata nella raccolta. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout è false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Rimuove l'elemento all'indice specificato della raccolta. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Sposta la diapositiva dalla raccolta nella posizione specificata. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Sposta le diapositive dalla raccolta nella posizione specificata. Le diapositive saranno posizionate a partire dall'indice nell'ordine in cui appaiono nella lista. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Crea e restituisce un array contenente tutte le diapositive. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Crea e restituisce un array con tutte le diapositive dell'intervallo specificato. Un indice della prima diapositiva da aggiungere. Un numero di diapositive da aggiungere. |

### Vedi anche

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [Presentation](../presentation)
* interfaccia [ISlideCollection](../islidecollection)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->