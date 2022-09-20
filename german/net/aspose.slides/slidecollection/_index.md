---
title: SlideCollection
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Sammlung von Folien dar.
type: docs
weight: 9220
url: /de/net/aspose.slides/slidecollection/
---
## SlideCollection class

Stellt eine Sammlung von Folien dar.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Ruft die Anzahl der tatsächlich in der Sammlung enthaltenen Elemente ab. SchreibgeschütztInt32 . |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (threadsicher) ist. SchreibgeschütztBoolean . |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Ruft das Element am angegebenen Index ab. Schreibgeschützt[`Slide`](../slide) . |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Gibt einen Synchronisationsstamm zurück. SchreibgeschütztObject . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. Das geeignete Layout wird automatisch aus dem angegebenen -Master ausgewählt (das geeignete Layout ist das Layout mit demselben Typ oder Namen wie des Layouts der Quellfolie). Wenn es kein geeignetes Layout gibt, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder PptxEditException ausgelöst (wenn allowCloneMissingLayout falsch ist). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Fügt am Ende der Sammlung eine neue leere Folie hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(string) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Gibt einen Index der angegebenen Folie in der Sammlung zurück. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position der Sammlung ein. Das geeignete Layout wird automatisch aus dem angegebenen -Master ausgewählt (das geeignete Layout ist das Layout mit demselben Typ oder Namen wie des Layouts der Quellfolie). Wenn es kein geeignetes Layout gibt, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder PptxEditException ausgelöst (wenn allowCloneMissingLayout falsch ist). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Verschiebt die Folie aus der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Verschiebt Folien aus der Sammlung an die angegebene Position. Folien werden ausgehend vom Index platziert, um sie in der Liste anzuzeigen. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Erstellt ein Array mit allen darin enthaltenen Folien und gibt es zurück. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Erstellt ein Array mit allen Folien aus dem angegebenen Bereich und gibt es zurück. Ein Index einer ersten hinzuzufügenden Folie.Eine Reihe von Folien zum Hinzufügen. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
