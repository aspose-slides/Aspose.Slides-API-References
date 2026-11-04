---
title: ISlideCollection
second_title: Aspose.Sildes .NET API referencia
description: Diák gyűjteményét képviseli.
type: docs
weight: 7070
url: /hu/aspose.slides/islidecollection/
---
## ISlideCollection interfész

Egy diák gyűjteményét képviseli.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | A megadott indexű elemet adja vissza. Csak olvasható [`ISlide`](../islide). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Hozzáad egy megadott dia másolatát a megadott rész végéhez. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Hozzáad egy megadott forrásdia másolatát a gyűjtemény végéhez. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott masterből (a megfelelő elrendezés a forrásdia elrendezésével azonos Type vagy Name értékkel rendelkező elrendezés). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése klónozódik (if allowCloneMissingLayout is true) vagy PptxEditException lesz dobva (if allowCloneMissingLayout is false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Új üres diát ad hozzá a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Diákat hoz létre HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Diákat hoz létre HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Diákat hoz létre HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Diákat hoz létre a PDF dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Diákat hoz létre a PDF dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Diákat hoz létre a PDF dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Diákat hoz létre a PDF dokumentumból, és hozzáadja őket a gyűjtemény végéhez a pdf import beállítások figyelembevételével. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Visszaadja a megadott dia indexét a gyűjteményben. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Beszúr egy megadott forrásdia másolatát a gyűjtemény megadott pozíciójába. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott masterből (a megfelelő elrendezés a forrásdia elrendezésével azonos Type vagy Name értékkel rendelkező elrendezés). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése klónozódik (if allowCloneMissingLayout is true) vagy PptxEditException lesz dobva (if allowCloneMissingLayout is false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Eltávolítja az adott objektum első előfordulását a gyűjteményből. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diákat a listában szereplő sorrendben, az indextől kezdve helyezi el. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes diát tartalmazza. |

### Lásd még

* interfész [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfész [ISlide](../islide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->