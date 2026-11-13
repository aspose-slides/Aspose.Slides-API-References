---
title: SlideCollection
second_title: Aspose.Sildes .NET API referencia
description: Egy diák gyűjteményét reprezentálja.
type: docs
weight: 9990
url: /hu/aspose.slides/slidecollection/
---
## SlideCollection osztály

Egy diák gyűjteményét reprezentál.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Visszaad egy értéket, amely azt jelzi, hogy a gyűjtemény elérése szinkronizált-e (szálbiztos). Csak olvasható Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | A megadott indexű elemet adja vissza. Csak olvasható [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object. |

## Metódusok

| Name | Description |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Hozzáad egy megadott dia másolatát a megadott szekció végéhez. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Hozzáad egy megadott forrásdia másolatát a gyűjtemény végéhez. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mesterből (a megfelelő elrendezés az, amelyik azonos Type vagy Name értékkel rendelkezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése klónozásra kerül (ha allowCloneMissingLayout igaz), vagy PptxEditException kerül dobásra (ha allowCloneMissingLayout hamis). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Új, üres diát ad a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Diákat hoz létre PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Diákat hoz létre PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Diákat hoz létre PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Diákat hoz létre PDF dokumentumból, és a gyűjtemény végéhez adja őket a pdf importálási beállítások figyelembevételével. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Az összes elemet átmásolja a gyűjteményből a megadott tömbbe. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Visszaadja a megadott dia indexét a gyűjteményben. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Beszúr egy megadott forrásdia másolatát a gyűjtemény megadott pozíciójába. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mesterből (a megfelelő elrendezés az, amelyik azonos Type vagy Name értékkel rendelkezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése klónozásra kerül (ha allowCloneMissingLayout igaz), vagy PptxEditException kerül dobásra (ha allowCloneMissingLayout hamis). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML szövegből, és a megadott pozícióba illeszti őket a gyűjteménybe. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Eltávolítja az elemet a megadott indexnél a gyűjteményből. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diák a listában megjelenő sorrendben kerülnek be az indextől kezdődően. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely tartalmazza az összes diát. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely az adott tartományban lévő összes diát tartalmazza. Az első hozzáadandó dia indexe. A hozzáadandó diák száma. |

### Lásd még

* osztály [DomObject&lt;TParent&gt;](../domobject-1)
* osztály [Presentation](../presentation)
* interfész [ISlideCollection](../islidecollection)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->