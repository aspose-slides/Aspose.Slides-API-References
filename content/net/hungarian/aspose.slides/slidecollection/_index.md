---
title: SlideCollection
second_title: Aspose.Sildes .NET API Referenciája
description: Egy diák gyűjteményét képviseli.
type: docs
weight: 9950
url: /hu/aspose.slides/slidecollection/
---
## SlideCollection osztály

Egy diák gyűjteményét képviseli.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. Csak olvasható Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Megkapja a megadott indexnél lévő elemet. Csak olvasható [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Visszaad egy szinkronizációs gyökeret. Csak olvasható Object. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | A megadott dia egy példányát hozzáadja a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | A megadott dia egy példányát hozzáadja a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | A megadott dia egy példányát a megadott szakasz végéhez adja hozzá. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | A megadott forrásdia egy példányát hozzáadja a gyűjtemény végéhez. A megfelelő elrendezés automatikusan ki lesz választva a megadott mesterből (a megfelelő elrendezés az a layout, amelynek típusa vagy neve megegyezik a forrásdia layoutjával). Ha nincs megfelelő elrendezés, akkor a forrásdia layoutja lesz klónozva (ha az allowCloneMissingLayout true), egyébként PptxEditException lesz dobva (ha az allowCloneMissingLayout false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Új üres diát ad a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Diakat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Diakat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Diakat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Diakat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Diakat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Diakat hoz létre HTML szövegből, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Diakat hoz létre PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Diakat hoz létre PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Diakat hoz létre PDF dokumentumból, és a gyűjtemény végéhez adja őket. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Diakat hoz létre PDF dokumentumból, és a PDF importálási beállítások figyelembevételével a gyűjtemény végéhez adja őket. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | A gyűjtemény összes elemét a megadott tömbbe másolja. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Visszaad egy enumerátort, amely végigjárja a gyűjteményt. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Visszaadja a megadott dia indexét a gyűjteményben. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | A megadott diát egy példányban a gyűjtemény megadott pozíciójába helyezi be. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | A megadott diát egy példányban a gyűjtemény megadott pozíciójába helyezi be. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | A megadott forrásdia egy példányát a gyűjtemény megadott pozíciójába helyezi be. A megfelelő elrendezés automatikusan ki lesz választva a megadott mesterből (a megfelelő elrendezés az a layout, amelynek típusa vagy neve megegyezik a forrásdia layoutjával). Ha nincs megfelelő elrendezés, akkor a forrásdia layoutja lesz klónozva (ha az allowCloneMissingLayout true), egyébként PptxEditException lesz dobva (ha az allowCloneMissingLayout false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | A megadott diát egy példányban a gyűjtemény megadott pozíciójába helyezi be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Diakat hoz létre HTML szövegből, és a gyűjtemény megadott pozíciójába helyezi be őket. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diák az indexnél kezdődően kerülnek elhelyezésre a listában szereplő sorrendben. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes diát tartalmazza. Az első hozzáadandó dia indexe. A hozzáadandó diák száma. |

### Lásd még

* osztály [DomObject&lt;TParent&gt;](../domobject-1)
* osztály [Presentation](../presentation)
* interfész [ISlideCollection](../islidecollection)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->