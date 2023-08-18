---
title: ISlideCollection
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Sammlung von Folien dar.
type: docs
weight: 6500
url: /de/aspose.slides/islidecollection/
---
## ISlideCollection interface

Stellt eine Sammlung von Folien dar.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Ruft das Element am angegebenen Index ab. Schreibgeschützt[`ISlide`](../islide) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. Das geeignete Layout wird automatisch aus dem angegebenen -Master ausgewählt (das geeignete Layout ist das Layout mit demselben Typ oder Namen wie des Layouts der Quellfolie). Wenn es kein geeignetes Layout gibt, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder PptxEditException ausgelöst (wenn allowCloneMissingLayout falsch ist). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Fügt am Ende der Sammlung eine neue leere Folie hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(string) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Gibt einen Index der angegebenen Folie in der Sammlung zurück. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position der Sammlung ein. Das geeignete Layout wird automatisch aus dem angegebenen -Master ausgewählt (das geeignete Layout ist das Layout mit demselben Typ oder Namen wie des Layouts der Quellfolie). Wenn es kein geeignetes Layout gibt, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder PptxEditException ausgelöst (wenn allowCloneMissingLayout falsch ist). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Verschiebt die Folie aus der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Verschiebt Folien aus der Sammlung an die angegebene Position. Folien werden ausgehend vom Index platziert, um sie in der Liste anzuzeigen. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Erstellt ein Array mit allen darin enthaltenen Folien und gibt es zurück. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Erstellt ein Array mit allen Folien aus dem angegebenen Bereich und gibt es zurück. |

### Siehe auch

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
