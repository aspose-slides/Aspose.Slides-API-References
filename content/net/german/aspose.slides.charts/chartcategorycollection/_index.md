---  
title: ChartCategoryCollection
second_title: Aspose.Sildes für .NET API Referenz  
description: Stellt die Sammlung von ChartCategory dar./chartcategory
type: docs
weight: 1200  
url: /de/aspose.slides.charts/chartcategorycollection/
---  

## ChartCategoryCollection Klasse  

Stellt die Sammlung von [`ChartCategory`](../chartcategory) dar  

```csharp  
public class ChartCategoryCollection : DomObject<ChartData>, IChartCategoryCollection  
```  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [Count](../../aspose.slides.charts/chartcategorycollection/count) { get; } | Gibt die Anzahl der Elemente in der Sammlung zurück. Nur-Lese Int32. |  
| [GroupingLevelCount](../../aspose.slides.charts/chartcategorycollection/groupinglevelcount) { get; } | Gibt die Anzahl der verwendeten Kategorisierungsstufen zurück. Ist mehr als eins für mehrstufige Kategorien. Nur-Lese Int32. |  
| [IsSynchronized](../../aspose.slides.charts/chartcategorycollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Liste synchronisiert (threadsicher) ist. Nur-Lese Boolean. |  
| [Item](../../aspose.slides.charts/chartcategorycollection/item) { get; } | Gibt das Element am angegebenen Index zurück. |  
| [SyncRoot](../../aspose.slides.charts/chartcategorycollection/syncroot) { get; } | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die Sammlung zu synchronisieren. Nur-Lese Object. |  
| [UseCells](../../aspose.slides.charts/chartcategorycollection/usecells) { get; set; } | Wenn wahr, wird das Arbeitsblatt zum Speichern von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). Wenn falsch, wird das Arbeitsblatt NICHT zum Speichern von Werten verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Lese-/Schreibe Boolean. |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [Add](../../aspose.slides.charts/chartcategorycollection/add#add)(IChartDataCell) | Wenn die Kategorie in der Sammlung vorhanden ist, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus [`IChartDataCell`](../ichartdatacell) erstellt und der Sammlung hinzugefügt. |  
| [Add](../../aspose.slides.charts/chartcategorycollection/add#add_1)(object) | Erstellt eine neue [`ChartCategory`](../chartcategory) aus dem Wert und fügt sie der Sammlung hinzu. |  
| [Clear](../../aspose.slides.charts/chartcategorycollection/clear)() | Entfernt alle Elemente aus der Sammlung. |  
| [CopyTo](../../aspose.slides.charts/chartcategorycollection/copyto)(Array, int) | Kopiert alle Elemente der Sammlung in das angegebene Array. |  
| [GetEnumerator](../../aspose.slides.charts/chartcategorycollection/getenumerator)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |  
| [IndexOf](../../aspose.slides.charts/chartcategorycollection/indexof)(IChartCategory) | Sucht nach der angegebenen [`ChartCategory`](../chartcategory) und gibt den nullbasierten Index der ersten Vorkommen innerhalb der gesamten Sammlung zurück. |  
| [Remove](../../aspose.slides.charts/chartcategorycollection/remove)(IChartCategory) | Entfernt den angegebenen Wert. |  
| [RemoveAt](../../aspose.slides.charts/chartcategorycollection/removeat)(int) | Entfernt das Element am angegebenen Index. |  

### Siehe auch  

* Klasse [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)  
* Klasse [ChartData](../chartdata)  
* Schnittstelle [IChartCategoryCollection](../ichartcategorycollection)  
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->