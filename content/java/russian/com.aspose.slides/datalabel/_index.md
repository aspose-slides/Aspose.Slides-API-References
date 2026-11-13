---
title: DataLabel
second_title: Справочник API Aspose.Slides для Java
description: Представляет метки серии.
type: docs
url: /ru/com.aspose.slides/datalabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Представляет метки серии.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Создает новый экземпляр класса DataLabel. |

## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [isVisible()](#isVisible--) | False означает, что метка данных не видна (и поэтому все флаги Show\*-flags (ShowValue, ...) имеют значение false). |
| [hide()](#hide--) | Скрыть метку данных, установив все флаги Show\*-flags (ShowValue, ...) в состояние false. |
| [getActualLabelText()](#getActualLabelText--) | Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Инициализирует TextFrameForOverriding текстом из параметра "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Может содержать богато отформатированный текст. |
| [getTextFormat()](#getTextFormat--) | Возвращает формат текста. |
| [getX()](#getX--) | Возвращает или задает координату x заголовка как часть ширины диаграммы. |
| [setX(float value)](#setX-float-) | Возвращает или задает координату x заголовка как часть ширины диаграммы. |
| [getY()](#getY--) | Возвращает или задает координату y заголовка как часть высоты диаграммы. |
| [setY(float value)](#setY-float-) | Возвращает или задает координату y заголовка как часть высоты диаграммы. |
| [getWidth()](#getWidth--) | Возвращает или задает ширину заголовка как часть ширины диаграммы. |
| [setWidth(float value)](#setWidth-float-) | Возвращает или задает ширину заголовка как часть ширины диаграммы. |
| [getHeight()](#getHeight--) | Возвращает или задает высоту заголовка как часть высоты диаграммы. |
| [setHeight(float value)](#setHeight-float-) | Возвращает или задает высоту заголовка как часть высоты диаграммы. |
| [getRight()](#getRight--) | Справа. |
| [getBottom()](#getBottom--) | Снизу. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Возвращает формат метки данных. |
| [getValueFromCell()](#getValueFromCell--) | Получает или задает ячейку данных книги. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Получает или задает ячейку данных книги. |
| [getLabelShapeType()](#getLabelShapeType--) | Получает или задает тип фигуры метки данных. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Получает или задает тип фигуры метки данных. |
| [getActualX()](#getActualX--) | Указывает фактическое положение x (слева) элемента диаграммы относительно верхнего левого угла диаграммы. |
| [getActualY()](#getActualY--) | Указывает фактическую верхнюю позицию элемента диаграммы относительно верхнего левого угла диаграммы. |
| [getActualWidth()](#getActualWidth--) | Указывает фактическую ширину элемента диаграммы. |
| [getActualHeight()](#getActualHeight--) | Указывает фактическую высоту элемента диаграммы. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию FillFormat. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Создает новый экземпляр класса DataLabel.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Родительский ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False означает, что метка данных не видна (и поэтому все флаги Show\*-flags (ShowValue, ...) имеют значение false). Только для чтения boolean.

--------------------

Если метка данных видима, её можно скрыть с помощью метода Hide(). Если же метка данных не видима (IsVisible равно false), её можно сделать видимой, установив флаги Show\*-flags (ShowValue, ...) в состояние true.

**Возвращаемое значение:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Скрыть метку данных, установив все флаги Show\*-flags (ShowValue, ...) в состояние false. После этого IsVisible будет false.

--------------------

Если метка данных не видима (IsVisible равно false), её можно сделать видимой, установив флаги Show\*-flags (ShowValue, ...) в состояние true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text.

**Возвращаемое значение:**
java.lang.String - Объект java.lang.String.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Инициализирует TextFrameForOverriding текстом из параметра "text". Если TextFrameForOverriding уже инициализирован, просто изменяет его текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для нового TextFrameForOverriding. |

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Может содержать богато отформатированный текст. Если это свойство не равно null, то значение этого отформатированного текста переопределяет автоматически сгенерированный текст метки данных. Автоматически сгенерированный текст метки данных — это текст, управляемый свойствами ShowSeriesName, ShowValue, ... и форматированный свойством TextFormatManager.TextFormat. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Возвращает формат текста. Только для чтения [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращаемое значение:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

Возвращает или задает координату x заголовка как часть ширины диаграммы. Чтение/запись float.

**Возвращаемое значение:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Возвращает или задает координату x заголовка как часть ширины диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Возвращает или задает координату y заголовка как часть высоты диаграммы. Чтение/запись float.

**Возвращаемое значение:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Возвращает или задает координату y заголовка как часть высоты диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Возвращает или задает ширину заголовка как часть ширины диаграммы. Чтение/запись float.

**Возвращаемое значение:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Возвращает или задает ширину заголовка как часть ширины диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Возвращает или задает высоту заголовка как часть высоты диаграммы. Чтение/запись float.

**Возвращаемое значение:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Возвращает или задает высоту заголовка как часть высоты диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Справа. Только для чтения float.

**Возвращаемое значение:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

Снизу. Только для чтения float.

**Возвращаемое значение:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Возвращает формат метки данных. Только для чтения [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Возвращаемое значение:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Получает или задает ячейку данных книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Получает или задает ячейку данных книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Получает или задает тип фигуры метки данных. Возвращает [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), если форма не определена.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Set the shape type of the first data label to Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
int

### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Получает или задает тип фигуры метки данных. Возвращает [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), если форма не определена.

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

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Указывает фактическое положение x (слева) элемента диаграммы относительно верхнего левого угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращаемое значение:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Указывает фактическую верхнюю позицию элемента диаграммы относительно верхнего левого угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращаемое значение:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращаемое значение:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращаемое значение:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)