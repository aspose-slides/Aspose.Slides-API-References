---
title: SlideCollection
second_title: Aspose.Sildes pro .NET API referenci
description: Reprezentuje kolekci snímků.
type: docs
weight: 9950
url: /cs/aspose.slides/slidecollection/
---
## SlideCollection třída

Reprezentuje kolekci snímků.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Vrací počet prvků, které jsou ve sbírce skutečně obsaženy. Pouze pro čtení Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Vrací hodnotu, která udává, zda je přístup ke sbírce synchronizován (vláknově bezpečný). Pouze pro čtení Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Vrací prvek na zadaném indexu. Pouze pro čtení [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Vrací kořen synchronizace. Pouze pro čtení Object. |

## Metody

| Název | Popis |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Přidá kopii zadaného snímku na konec sbírky. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Přidá kopii zadaného snímku na konec sbírky. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Přidá kopii zadaného snímku na konec zadané sekce. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Přidá kopii zadaného zdrojového snímku na konec sbírky. Vhodné rozložení bude automaticky vybráno z určeného masteru (vhodné rozložení je rozložení se stejným Typem nebo názvem jako rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, bude rozložení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena výjimka PptxEditException (pokud je allowCloneMissingLayout false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Přidá nový prázdný snímek na konec sbírky. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Vytvoří snímky z HTML textu a přidá je na konec sbírky. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Vytvoří snímky z HTML textu a přidá je na konec sbírky. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Vytvoří snímky z HTML textu a přidá je na konec sbírky. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec sbírky. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec sbírky. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a přidá je na konec sbírky. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Vytvoří snímky z PDF dokumentu a přidá je na konec sbírky. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Vytvoří snímky z PDF dokumentu a přidá je na konec sbírky. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec sbírky. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Vytvoří snímky z PDF dokumentu a přidá je na konec sbírky s ohledem na možnosti importu PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Zkopíruje všechny prvky ze sbírky do zadaného pole. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Vrací enumerátor, který prochází sbírku. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Vrací index zadaného snímku ve sbírce. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Vloží kopii zadaného snímku na určenou pozici ve sbírce. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Vloží kopii zadaného snímku na určenou pozici ve sbírce. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Vloží kopii zadaného zdrojového snímku na určenou pozici ve sbírce. Vhodné rozložení bude automaticky vybráno z určeného masteru (vhodné rozložení je rozložení se stejným Typem nebo názvem jako rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, bude rozložení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena výjimka PptxEditException (pokud je allowCloneMissingLayout false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Vloží kopii zadaného snímku na určenou pozici ve sbírce. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Vytvoří snímky z HTML textu a vloží je do sbírky na určenou pozici. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Odstraní první výskyt konkrétního objektu ze sbírky. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Odstraní prvek na zadaném indexu ve sbírce. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Přesune snímek ve sbírce na určenou pozici. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Přesune snímky ze sbírky na určenou pozici. Snímky budou umístěny počínaje indexem v pořadí, v jakém se objevují v seznamu. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Vytvoří a vrátí pole se všemi snímky. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Vytvoří a vrátí pole se všemi snímky ze zadaného rozsahu. Index prvního snímku k přidání. Počet snímků k přidání. |

### Viz také

* třída [DomObject&lt;TParent&gt;](../domobject-1)
* třída [Presentation](../presentation)
* rozhraní [ISlideCollection](../islidecollection)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->