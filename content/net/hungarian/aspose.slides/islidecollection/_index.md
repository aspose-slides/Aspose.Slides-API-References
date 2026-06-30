---
title: ISlideCollection
second_title: Aspose.Sildes .NET API-referencia
description: A diák gyűjteményét reprezentálja.
type: docs
weight: 7030
url: /hu/aspose.slides/islidecollection/
---
## ISlideCollection interfész

A diák gyűjteményét reprezentálja.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Az adott indexű elemet adja vissza. Csak olvasható [`ISlide`](../islide). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | A megadott dia egy másolatát a gyűjtemény végéhez adja hozzá. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | A megadott dia egy másolatát a gyűjtemény végéhez adja hozzá. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | A megadott dia egy másolatát a megadott szekció végéhez adja hozzá. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | A megadott forrásdia egy másolatát a gyűjtemény végéhez adja hozzá. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mesterből (a megfelelő elrendezés a forrásdia elrendezésével azonos Type vagy Name értékkel rendelkezik). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha allowCloneMissingLayout igaz), vagy PptxEditException keletkezik (ha allowCloneMissingLayout hamis). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Új, üres diát ad a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Diákat hoz létre HTML-szövegből, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Diákat hoz létre HTML-szövegből, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Diákat hoz létre HTML-szövegből, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Diákat hoz létre PDF-dokumentumból, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Diákat hoz létre PDF-dokumentumból, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Diákat hoz létre PDF-dokumentumból, és azok a gyűjtemény végéhez kerülnek. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Diákat hoz létre PDF-dokumentumból, és azok a gyűjtemény végéhez kerülnek a pdf importálási beállítások figyelembevételével. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Visszaadja a megadott dia indexét a gyűjteményben. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Egy megadott dia másolatát a megadott pozícióba illeszti be a gyűjteményben. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Egy megadott dia másolatát a megadott pozícióba illeszti be a gyűjteményben. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Egy megadott forrásdia másolatát a megadott pozícióba illeszti be a gyűjteményben. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mesterből (a megfelelő elrendezés a forrásdia elrendezésével azonos Type vagy Name értékkel rendelkezik). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha allowCloneMissingLayout igaz), vagy PptxEditException keletkezik (ha allowCloneMissingLayout hamis). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Egy megadott dia másolatát a megadott pozícióba illeszti be a gyűjteményben. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML-szövegből, és a megadott pozícióba szúrja be a gyűjteménybe. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Az adott objektum első előfordulását eltávolítja a gyűjteményből. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Az adott indexű elemet eltávolítja a gyűjteményből. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Áthelyezi a diát a gyűjteményben a megadott pozícióra. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Áthelyezi a diákat a gyűjteményből a megadott pozícióra. A diák a listában szereplő sorrendben, az indextől kezdve kerülnek be. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő diákat tartalmazza. |

### Lásd még

* interfész [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfész [ISlide](../islide)
* névtér [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->