---
title: SlideCollection
second_title: Aspose.Slides für .NET API Referenz
description: Stellt eine Sammlung von Folien dar.
type: docs
weight: 9660
url: /de/aspose.slides/slidecollection/
---

## SlideCollection-Klasse

Stellt eine Sammlung von Folien dar.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen Elemente zurück. Nur-lesender Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur-lesender Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Gibt das Element an dem angegebenen Index zurück. Nur-lesender [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Gibt eine Synchronisationswurzel zurück. Nur-lesendes Objekt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Fügt eine Kopie einer bestimmten Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Fügt eine Kopie einer bestimmten Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Fügt eine Kopie einer bestimmten Folie am Ende des angegebenen Bereichs hinzu. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Fügt eine Kopie einer bestimmten Quellfolie am Ende der Sammlung hinzu. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (passendes Layout ist das Layout mit demselben Typ oder Namen wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Fügt eine neue leere Folie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu, wobei die PDF-Importoptionen berücksichtigt werden. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Gibt einen Index der angegebenen Folie in der Sammlung zurück. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Fügt eine Kopie einer bestimmten Folie an der angegebenen Position der Sammlung ein. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Fügt eine Kopie einer bestimmten Folie an der angegebenen Position der Sammlung ein. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Fügt eine Kopie einer bestimmten Quellfolie an der angegebenen Position der Sammlung ein. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (passendes Layout ist das Layout mit demselben Typ oder Namen wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder eine PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Fügt eine leere Folie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Entfernt das Element an dem angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Verschiebt eine Folie aus der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Verschiebt Folien aus der Sammlung an die angegebene Position. Die Folien werden in der Reihenfolge platziert, in der sie in der Liste erscheinen, beginnend vom Index. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Erstellt und gibt ein Array mit allen Folien darin zurück. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array mit allen Folien aus dem angegebenen Bereich zurück. Ein Index der ersten Folie, die hinzugefügt werden soll. Eine Anzahl von Folien, die hinzugefügt werden sollen. |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../domobject-1)
* Klasse [Presentation](../presentation)
* Schnittstelle [ISlideCollection](../islidecollection)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->