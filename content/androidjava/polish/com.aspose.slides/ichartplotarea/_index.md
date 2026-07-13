---
title: IChartPlotArea
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje właściwości tytułu wykresu.
type: docs
url: /pl/com.aspose.slides/ichartplotarea/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Reprezentuje właściwości tytułu wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFormat()](#getFormat--) | Zwraca format obszaru wykresu. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układ obszaru wykresu ma być wewnętrzny (nie obejmujący osi i etykiet osi) czy zewnętrzny (obejmujący oś i etykiety osi). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układ obszaru wykresu ma być wewnętrzny (nie obejmujący osi i etykiet osi) czy zewnętrzny (obejmujący oś i etykiety osi). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Zwraca format obszaru wykresu. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układ obszaru wykresu ma być wewnętrzny (nie obejmujący osi i etykiet osi) czy zewnętrzny (obejmujący oś i etykiety osi). Odczyt/zapis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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


**Zwraca:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Jeśli układ obszaru wykresu jest definiowany ręcznie, ta właściwość określa, czy układ obszaru wykresu ma być wewnętrzny (nie obejmujący osi i etykiet osi) czy zewnętrzny (obejmujący oś i etykiety osi). Odczyt/zapis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |