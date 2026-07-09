---
title: SlideCollection
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje kolekci snímků.
type: docs
weight: 9970
url: /cs/aspose.slides/slidecollection/
---
## SlideCollection třída

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Vrací počet prvků skutečně obsažených v kolekci. Pouze pro čtení Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Vrací hodnotu, která určuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Vrací prvek na zadaném indexu. Pouze pro čtení [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Vrací kořen synchronizace. Pouze pro čtení Object. |

## Metody

| Název | Popis |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Přidá kopii zadaného snímku na konec kolekce. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Přidá kopii zadaného snímku na konec kolekce. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Přidá kopii zadaného snímku na konec určené sekce. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Přidá kopii zadaného zdrojového snímku na konec kolekce. Vhodné rozložení bude automaticky vybráno z určeného masteru (vhodné rozložení je rozložení se stejným Type nebo Name jako rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, bude rozložení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena výjimka PptxEditException (pokud je allowCloneMissingLayout false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Přidá nový prázdný snímek na konec kolekce. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce s ohledem na možnosti pdf importu. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Vrací enumerátor, který prochází kolekcí. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Vrací index zadaného snímku v kolekci. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Vloží kopii zadaného zdrojového snímku na určenou pozici v kolekci. Vhodné rozložení bude automaticky vybráno z určeného masteru (vhodné rozložení je rozložení se stejným Type nebo Name jako rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, bude rozložení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena výjimka PptxEditException (pokud je allowCloneMissingLayout false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Odstraní prvek na zadaném indexu v kolekci. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Přesune snímek v kolekci na určenou pozici. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Přesune snímky v kolekci na určenou pozici. Snímky budou umístěny počínaje indexem v pořadí, v jakém se vyskytují v seznamu. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Vytvoří a vrátí pole obsahující všechny snímky. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Vytvoří a vrátí pole se všemi snímky ze zadaného rozsahu. Index prvního snímku k přidání. Počet snímků k přidání. |

### Viz také

* třída [DomObject&lt;TParent&gt;](../domobject-1)
* třída [Presentation](../presentation)
* rozhraní [ISlideCollection](../islidecollection)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->