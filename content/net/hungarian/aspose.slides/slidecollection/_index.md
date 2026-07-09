---
title: SlideCollection
second_title: Aspose.Sildes a .NET API hivatkozás
description: Diák gyűjteményét képviseli.
type: docs
weight: 9970
url: /hu/aspose.slides/slidecollection/
---
## SlideCollection osztály

A diákat tartalmazó gyűjteményt képviseli.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. Csak olvasható Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Visszaad egy értéket, amely jelzi, hogy a gyűjtemény hozzáférése szinkronizált (szálbiztos). Csak olvasható Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | A megadott indexű elemet adja vissza. Csak olvasható [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | A megadott dia egy példányát a gyűjtemény végéhez adja hozzá. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | A megadott dia egy példányát a gyűjtemény végéhez adja hozzá. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | A megadott dia egy példányát a megadott szakasz végéhez adja hozzá. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | A megadott forrásdia egy példányát a gyűjtemény végéhez adja hozzá. A megfelelő elrendezés automatikusan ki lesz választva a megadott mesterből (a megfelelő elrendezés az, amelynek típusa vagy neve megegyezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, a forrásdia elrendezése klónozódik (ha az allowCloneMissingLayout igaz), vagy PptxEditException kivétel keletkezik (ha az allowCloneMissingLayout hamis). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Új üres diát ad a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | HTML szövegből diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | HTML szövegből diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML szövegből diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML szövegből diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML szövegből diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML szövegből diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | PDF dokumentumból diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | PDF dokumentumból diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF dokumentumból diákat hoz létre, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF dokumentumból diákat hoz létre, és a pdf importálási beállításokat figyelembe véve adja hozzá a gyűjtemény végéhez. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | A gyűjtemény összes elemét a megadott tömbbe másolja. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Visszaad egy enumerátort, amely a gyűjteményen iterál. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Visszaad a megadott dia indexét a gyűjteményben. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | A megadott forrásdia egy példányát a gyűjtemény megadott pozíciójába szúrja be. A megfelelő elrendezés automatikusan ki lesz választva a megadott mesterből (a megfelelő elrendezés az, amelynek típusa vagy neve megegyezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, a forrásdia elrendezése klónozódik (ha az allowCloneMissingLayout igaz), vagy PptxEditException kivétel keletkezik (ha az allowCloneMissingLayout hamis). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | A megadott dia egy példányát a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML szövegből diákat hoz létre, és a gyűjtemény megadott pozíciójába szúrja be. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diák az indexnél kezdődően a listában szereplő sorrendben lesznek elhelyezve. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő diákat tartalmazza. A hozzáadandó első dia indexe. A hozzáadandó diák száma. |

### Lásd még

* osztály [DomObject&lt;TParent&gt;](../domobject-1)
* osztály [Presentation](../presentation)
* interfész [ISlideCollection](../islidecollection)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->