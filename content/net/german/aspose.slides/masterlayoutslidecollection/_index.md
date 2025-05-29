---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides für .NET API Referenz
description: Repräsentiert eine Sammlung aller Layout-Folien des definierten Master-Folien. Erweitert die LayoutSlideCollection-Klasse mit Methoden zum Hinzufügen/Einfügen/Entfernen/Klonen/Neuanordnen von Layout-Folien im Kontext der einzelnen Sammlungen von Master-Layout-Folien.
type: docs
weight: 7750
url: /de/aspose.slides/masterlayoutslidecollection/
---

## MasterLayoutSlideCollection-Klasse

Repräsentiert eine Sammlung aller Layout-Folien des definierten Master-Folien. Erweitert die LayoutSlideCollection-Klasse mit Methoden zum Hinzufügen/Einfügen/Entfernen/Klonen/Neuanordnen von Layout-Folien im Kontext der einzelnen Sammlungen von Master-Layout-Folien.

```csharp
public sealed class MasterLayoutSlideCollection : LayoutSlideCollection, 
    IMasterLayoutSlideCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides/layoutslidecollection/count) { get; } | Gibt die Anzahl der Layout-Folien in einer Sammlung zurück. Nur-lesender Int32. |
| [IsSynchronized](../../aspose.slides/layoutslidecollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (Thread-sicher). Nur-lesender Boolean. |
| [Item](../../aspose.slides/layoutslidecollection/item) { get; } | Gibt die Layout-Folie nach dem Index zurück. Nur-lesender [`LayoutSlide`](../layoutslide). |
| [SyncRoot](../../aspose.slides/layoutslidecollection/syncroot) { get; } | Gibt eine Synchronisierungswurzel zurück. Nur-lesendes Objekt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.slides/masterlayoutslidecollection/add)(SlideLayoutType, string) | Fügt eine neue Layout-Folie am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/masterlayoutslidecollection/addclone)(ILayoutSlide) | Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu. |
| [CopyTo](../../aspose.slides/layoutslidecollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetByType](../../aspose.slides/layoutslidecollection/getbytype)(SlideLayoutType) | Gibt die erste Layout-Folie des angegebenen Typs zurück. Ein Typ von Layout-Folie, die gefunden werden soll. [`LayoutSlide`](../layoutslide) mit dem angegebenen Typ oder null, wenn keine Layouts gefunden wurden. |
| [GetEnumerator](../../aspose.slides/layoutslidecollection/getenumerator)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [Insert](../../aspose.slides/masterlayoutslidecollection/insert)(int, SlideLayoutType, string) | Fügt eine neue Layout-Folie an der angegebenen Position der Sammlung ein. |
| [InsertClone](../../aspose.slides/masterlayoutslidecollection/insertclone)(int, ILayoutSlide) | Fügt eine Kopie einer bestimmten Layout-Folie an der angegebenen Position der Sammlung ein. |
| [Remove](../../aspose.slides/layoutslidecollection/remove)(ILayoutSlide) | Entfernt eine Layout-Folie aus der Sammlung. |
| [RemoveAt](../../aspose.slides/masterlayoutslidecollection/removeat)(int) | Entfernt das Element an dem angegebenen Index der Sammlung. |
| [RemoveUnused](../../aspose.slides/layoutslidecollection/removeunused)() | Entfernt ungenutzte Layout-Folien (Layout-Folien, deren HasDependingSlides false ist). |
| [Reorder](../../aspose.slides/masterlayoutslidecollection/reorder)(int, ILayoutSlide) | Verschiebt die Layout-Folie von der Sammlung an die angegebene Position. |

### Siehe auch

* Klasse [LayoutSlideCollection](../layoutslidecollection)
* Schnittstelle [IMasterLayoutSlideCollection](../imasterlayoutslidecollection)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)