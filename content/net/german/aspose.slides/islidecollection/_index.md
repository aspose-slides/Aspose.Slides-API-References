---
title: ISlideCollection
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Sammlung von Folien dar.
type: docs
weight: 7050
url: /de/aspose.slides/islidecollection/
---
## ISlideCollection Schnittstelle

Stellt eine Sammlung von Folien dar.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Liefert das Element am angegebenen Index. Nur lesbar [`ISlide`](../islide). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (ein passendes Layout ist das Layout mit demselben Type oder Name wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout false ist). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Fügt eine neue leere Folie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Erstelle Folien aus HTML-Text und füge sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Erstelle Folien aus HTML-Text und füge sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Erstelle Folien aus HTML-Text und füge sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Erstelle Folien aus HTML-Text und füge sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Erstelle Folien aus HTML-Text und füge sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Erstelle Folien aus HTML-Text und füge sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Erstelle Folien aus dem PDF-Dokument und füge sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Erstelle Folien aus dem PDF-Dokument und füge sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Erstelle Folien aus dem PDF-Dokument und füge sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Erstelle Folien aus dem PDF-Dokument und füge sie am Ende der Sammlung hinzu, wobei die PDF-Import-Optionen berücksichtigt werden. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Gibt den Index der angegebenen Folie in der Sammlung zurück. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position in die Sammlung ein. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (ein passendes Layout ist das Layout mit demselben Type oder Name wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout false ist). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Entfernt das erste Vorkommen des angegebenen Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Verschiebt die Folie in der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Verschiebt Folien in der Sammlung an die angegebene Position. Die Folien werden beginnend mit dem Index in der Reihenfolge ihres Auftretens in der Liste platziert. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Erstellt und gibt ein Array mit allen Folien zurück. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array mit allen Folien aus dem angegebenen Bereich zurück. |

### Siehe auch

* Schnittstelle [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* Schnittstelle [ISlide](../islide)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->