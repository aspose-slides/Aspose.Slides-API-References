---
title: ISlideCollection
second_title: Aspose.Sildes .NET API referencia
description: Diák gyűjteményét képviseli.
type: docs
weight: 7050
url: /hu/aspose.slides/islidecollection/
---
## ISlideCollection interfész

Represents a collection of a slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Visszaadja a megadott indexnél található elemet. Csak olvasható [`ISlide`](../islide). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Hozzáad egy megadott dia másolatát a gyűjtemény végéhez. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Hozzáad egy megadott dia másolatát a megadott szekció végéhez. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Hozzáad egy megadott forrásdia másolatát a gyűjtemény végéhez. A megfelelő elrendezés automatikusan ki lesz választva a megadott masterből (a megfelelő elrendezés azonos Type vagy Name értékkel rendelkezik, mint a forrásdia elrendezése). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése klónozódik (ha allowCloneMissingLayout true), vagy PptxEditException lesz dobva (ha allowCloneMissingLayout false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Hozzáad egy új üres diát a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Diákat hoz létre HTML-szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Diákat hoz létre HTML-szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Diákat hoz létre HTML-szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Diákat hoz létre PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Diákat hoz létre PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Diákat hoz létre PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Diákat hoz létre PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez a pdf import opciók figyelembevételével. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Visszaadja a megadott dia indexét a gyűjteményben. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Beszúr egy megadott forrásdia másolatát a gyűjtemény megadott pozíciójába. A megfelelő elrendezés automatikusan ki lesz választva a megadott masterből (a megfelelő elrendezés azonos Type vagy Name értékkel rendelkezik, mint a forrásdia elrendezése). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése klónozódik (ha allowCloneMissingLayout true), vagy PptxEditException lesz dobva (ha allowCloneMissingLayout false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Diákat hoz létre HTML-szövegből, és beszúrja őket a gyűjteménybe a megadott pozícióban. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Áthelyezi a diát a gyűjteményből a megadott pozícióba. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Áthelyezi a diákat a gyűjteményből a megadott pozícióba. A diákat a listában megjelenő sorrendben, az indextől kezdve helyezi el. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Létrehoz egy tömböt az összes diával, és visszaadja. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Létrehoz egy tömböt a megadott tartományban lévő diákkal, és visszaadja. |

### Lásd még

* interfész [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfész [ISlide](../islide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->