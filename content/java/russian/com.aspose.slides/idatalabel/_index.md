---
title: IDataLabel
second_title: Aspose.Slides для Java справка по API
description: Представляет метки серии.
type: docs
url: /ru/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Представляет метки серии.
## Методы

| Метод | Описание |
| --- | --- |
| [isVisible()](#isVisible--) | False означает, что метка данных не видна (и поэтому все флаги Show*- (ShowValue, ...) имеют значение false). |
| [hide()](#hide--) | Сделать метку данных скрытой, установив все флаги Show*- (ShowValue, ...) в состояние false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Возвращает формат метки данных. |
| [getValueFromCell()](#getValueFromCell--) | Получает или задаёт ячейку данных рабочей книги. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Получает или задаёт ячейку данных рабочей книги. |
| [getActualLabelText()](#getActualLabelText--) | Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Получает или задаёт тип формы метки данных. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Получает или задаёт тип формы метки данных. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False означает, что метка данных не видна (и поэтому все флаги Show*- (ShowValue, ...) имеют значение false). Только для чтения boolean.

--------------------

Если метка данных видима, её можно скрыть методом Hide(). Но если метка данных не видима (IsVisible равно false), её можно сделать видимой, установив флаги Show*- (ShowValue, ...) в состояние true.

**Возвращает:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Сделать метку данных скрытой, установив все флаги Show*- (ShowValue, ...) в состояние false. После этого IsVisible будет false.

--------------------

Если метка данных не видима (IsVisible равно false), её можно сделать видимой, установив флаги Show*- (ShowValue, ...) в состояние true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Возвращает формат метки данных. Только для чтения [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Возвращает:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Получает или задаёт ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Возвращает:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Получает или задаёт ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text.

**Возвращает:**
java.lang.String - Фактический текст метки String
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Получает или задаёт тип формы метки данных. Возвращает [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), если форма не определена.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Установить тип формы первой метки данных в Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Получает или задаёт тип формы метки данных. Возвращает [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), если форма не определена.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Установить тип формы первой метки данных в Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |