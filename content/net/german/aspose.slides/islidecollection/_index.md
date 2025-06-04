---
title: ISlideCollection
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine Sammlung von Folien dar.
type: docs
weight: 6830
url: /de/aspose.slides/islidecollection/
---

## ISlideCollection-Schnittstelle

Stellt eine Sammlung von Folien dar.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Gibt das Element am angegebenen Index zurück. Nur lesbar [`ISlide`](../islide). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. Das entsprechende Layout wird automatisch aus dem angegebenen Master ausgewählt (das entsprechende Layout ist das Layout mit demselben Typ oder Namen wie das Layout der Quellfolie). Wenn kein entsprechendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Fügt eine neue leere Folie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu, wobei die PDF-Importoptionen berücksichtigt werden. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Gibt einen Index der angegebenen Folie in der Sammlung zurück. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Fügen Sie eine Kopie einer bestimmten Folie an einer bestimmten Position der Sammlung hinzu. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Fügt eine Kopie einer bestimmten Folie an einer bestimmten Position der Sammlung hinzu. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Fügt eine Kopie einer bestimmten Quellfolie an einer bestimmten Position der Sammlung hinzu. Das entsprechende Layout wird automatisch aus dem angegebenen Master ausgewählt (das entsprechende Layout ist das Layout mit demselben Typ oder Namen wie das Layout der Quellfolie). Wenn kein entsprechendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Fügt eine leere Folie an einer bestimmten Position der Sammlung hinzu. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position der Sammlung ein. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Entfernt die erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Verschiebt eine Folie von der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Verschiebt Folien aus der Sammlung an die angegebene Position. Folien werden beginnend vom Index in der Reihenfolge eingeordnet, in der sie in der Liste erscheinen. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Erstellt und gibt ein Array mit allen Folien darin zurück. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array mit allen Folien aus dem angegebenen Bereich zurück. |

### Siehe auch

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->