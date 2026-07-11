---
title: IChartPlotArea
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет свойства заголовка диаграммы.
type: docs
url: /ru/com.aspose.slides/ichartplotarea/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Представляет свойства заголовка диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) | Возвращает формат области построения. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Если расположение области построения определено вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Если расположение области построения определено вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Возвращает формат области построения. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Если расположение области построения определено вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). Чтение/запись [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**Возвращает:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Если расположение области построения определено вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). Чтение/запись [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |