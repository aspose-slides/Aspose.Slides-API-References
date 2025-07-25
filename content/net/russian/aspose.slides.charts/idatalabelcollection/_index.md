---
title: IDataLabelCollection
second_title: Справка по API Aspose.Slides для .NET
description: Представляет метки серии.
type: docs
weight: 1950
url: /ru/aspose.slides.charts/idatalabelcollection/
---

## Интерфейс IDataLabelCollection

Представляет метки серии.

```csharp
public interface IDataLabelCollection : IChartComponent, IEnumerable<IDataLabel>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/idatalabelcollection/asichartcomponent) { get; } | Позволяет получить базовый интерфейс IChartComponent. Только для чтения [`IChartComponent`](../ichartcomponent). |
| [AsIEnumerable](../../aspose.slides.charts/idatalabelcollection/asienumerable) { get; } | Позволяет получить базовый интерфейс IEnumerable. Только для чтения IEnumerable. |
| [Count](../../aspose.slides.charts/idatalabelcollection/count) { get; } | Получает количество всех меток данных в коллекции. Только для чтения Int32. |
| [CountOfVisibleDataLabels](../../aspose.slides.charts/idatalabelcollection/countofvisibledatalabels) { get; } | Получает количество видимых меток данных в коллекции. Только для чтения Int32. |
| [DefaultDataLabelFormat](../../aspose.slides.charts/idatalabelcollection/defaultdatalabelformat) { get; } | Возвращает формат по умолчанию для всех меток данных в коллекции. Только для чтения [`IDataLabelFormat`](../idatalabelformat). |
| [IsVisible](../../aspose.slides.charts/idatalabelcollection/isvisible) { get; } | Ложное значение означает, что метка данных по умолчанию не видима (все флаги Show*- (ShowValue и т.д.) свойства DefaultDataLabelFormat равны false). Только для чтения Boolean. |
| [Item](../../aspose.slides.charts/idatalabelcollection/item) { get; } | Получает метку данных для точки данных с указанным индексом. |
| [LeaderLinesFormat](../../aspose.slides.charts/idatalabelcollection/leaderlinesformat) { get; } | Представляет формат линий лидеров меток данных. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [ParentSeries](../../aspose.slides.charts/idatalabelcollection/parentseries) { get; } | Возвращает родительскую серию диаграммы. Только для чтения [`IChartSeries`](../ichartseries). |

## Методы

| Имя | Описание |
| --- | --- |
| [Hide](../../aspose.slides.charts/idatalabelcollection/hide)() | Делает метку данных скрытой по умолчанию, устанавливая все флаги Show*- (ShowValue и т.д.) свойства DefaultDataLabelFormat в состояние false. IsVisible будет равен false после этого. |
| [IndexOf](../../aspose.slides.charts/idatalabelcollection/indexof)(IDataLabel) | Возвращает индекс указанной метки данных в коллекции. |

### См. Также

* интерфейс [IChartComponent](../ichartcomponent)
* интерфейс [IDataLabel](../idatalabel)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->