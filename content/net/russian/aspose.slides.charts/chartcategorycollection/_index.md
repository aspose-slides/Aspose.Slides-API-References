---  
title: ChartCategoryCollection
second_title: Aspose.Sildes для .NET API Справочник  
description: Представляет коллекцию ChartCategory./chartcategory
type: docs
weight: 1200  
url: /ru/aspose.slides.charts/chartcategorycollection/
---  

## Class ChartCategoryCollection  

Представляет коллекцию [`ChartCategory`](../chartcategory)  

```csharp  
public class ChartCategoryCollection : DomObject<ChartData>, IChartCategoryCollection  
```  

## Свойства  

| Название | Описание |  
| --- | --- |  
| [Count](../../aspose.slides.charts/chartcategorycollection/count) { get; } | Возвращает количество элементов в коллекции. Только для чтения Int32. |  
| [GroupingLevelCount](../../aspose.slides.charts/chartcategorycollection/groupinglevelcount) { get; } | Возвращает количество уровней группировки категорий. Более одной для многоуровневых категорий. Только для чтения Int32. |  
| [IsSynchronized](../../aspose.slides.charts/chartcategorycollection/issynchronized) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к списку (безопасен для потоков). Только для чтения Boolean. |  
| [Item](../../aspose.slides.charts/chartcategorycollection/item) { get; } | Получает элемент по указанному индексу. |  
| [SyncRoot](../../aspose.slides.charts/chartcategorycollection/syncroot) { get; } | Возвращает объект, который может быть использован для синхронизации доступа к коллекции. Только для чтения Object. |  
| [UseCells](../../aspose.slides.charts/chartcategorycollection/usecells) { get; set; } | Если истинно, то используется рабочий лист для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если ложно, то рабочий лист НЕ используется для хранения значений (в этом случае не поддерживаются многоуровневые категории). Чтение/запись Boolean. |  

## Методы  

| Название | Описание |  
| --- | --- |  
| [Add](../../aspose.slides.charts/chartcategorycollection/add#add)(IChartDataCell) | Если категория существует в коллекции, возвращает ее. Иначе создает новую категорию диаграммы из [`IChartDataCell`](../ichartdatacell) и добавляет ее в коллекцию. |  
| [Add](../../aspose.slides.charts/chartcategorycollection/add#add_1)(object) | Создает новую [`ChartCategory`](../chartcategory) из значения и добавляет ее в коллекцию. |  
| [Clear](../../aspose.slides.charts/chartcategorycollection/clear)() | Удаляет все элементы из коллекции. |  
| [CopyTo](../../aspose.slides.charts/chartcategorycollection/copyto)(Array, int) | Копирует все элементы коллекции в указанной массив. |  
| [GetEnumerator](../../aspose.slides.charts/chartcategorycollection/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |  
| [IndexOf](../../aspose.slides.charts/chartcategorycollection/indexof)(IChartCategory) | Ищет указанную [`ChartCategory`](../chartcategory) и возвращает индекс первого вхождения в целом массиве. |  
| [Remove](../../aspose.slides.charts/chartcategorycollection/remove)(IChartCategory) | Удаляет указанное значение. |  
| [RemoveAt](../../aspose.slides.charts/chartcategorycollection/removeat)(int) | Удаляет элемент по указанному индексу. |  

### Смотрите также  

* класс [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)  
* класс [ChartData](../chartdata)  
* интерфейс [IChartCategoryCollection](../ichartcategorycollection)  
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)  
* сборка [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  