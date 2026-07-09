---
title: ISlideCollection
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje kolekci snímků.
type: docs
weight: 7050
url: /cs/aspose.slides/islidecollection/
---
## ISlideCollection rozhraní

Reprezentuje kolekci snímků.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Získá prvek na zadaném indexu. Pouze ke čtení [`ISlide`](../islide). |

## Metody

| Název | Popis |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Přidá kopii zadaného snímku na konec kolekce. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Přidá kopii zadaného snímku na konec kolekce. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Přidá kopii zadaného snímku na konec určené sekce. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Přidá kopii zadaného zdrojového snímku na konec kolekce. Vhodné rozložení bude automaticky vybráno z určeného mistra (vhodné rozložení je rozložení se stejným typem nebo názvem jako rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, bude rozložení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Přidá nový prázdný snímek na konec kolekce. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce s ohledem na možnosti importu PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Vrátí index zadaného snímku v kolekci. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Vloží kopii zadaného zdrojového snímku na určenou pozici v kolekci. Vhodné rozložení bude automaticky vybráno z určeného mistra (vhodné rozložení je rozložení se stejným typem nebo názvem jako rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, bude rozložení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Odstraní prvek na zadaném indexu v kolekci. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Přesune snímek v kolekci na určenou pozici. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Přesune snímky v kolekci na určenou pozici. Snímky budou umístěny počínaje indexem v pořadí, v jakém jsou v seznamu. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Vytvoří a vrátí pole obsahující všechny snímky. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Vytvoří a vrátí pole obsahující všechny snímky ze zadaného rozsahu. |

### Viz také

* rozhraní [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* rozhraní [ISlide](../islide)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->