---
title: DataLabel
second_title: Справочник API Aspose.Slides для Java
description: Представляет подписи серии.
type: docs
url: /ru/com.aspose.slides/datalabel/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Представляет подписи серии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Создает новый экземпляр класса DataLabel. |
## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [isVisible()](#isVisible--) | Ложь означает, что подпись данных не видна (и поэтому все флаги Show\*-flags (ShowValue, ...) имеют значение false). |
| [hide()](#hide--) | Скрывает подпись данных, устанавливая все флаги Show\*-flags (ShowValue, ...) в состояние false. |
| [getActualLabelText()](#getActualLabelText--) | Возвращает фактический текст подписи на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Инициализирует TextFrameForOverriding текстом из параметра "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Может содержать текст с расширенным форматированием. |
| [getTextFormat()](#getTextFormat--) | Возвращает формат текста. |
| [getX()](#getX--) | Возвращает или задает координату x заголовка как долю ширины диаграммы. |
| [setX(float value)](#setX-float-) | Возвращает или задает координату x заголовка как долю ширины диаграммы. |
| [getY()](#getY--) | Возвращает или задает координату y заголовка как долю высоты диаграммы. |
| [setY(float value)](#setY-float-) | Возвращает или задает координату y заголовка как долю высоты диаграммы. |
| [getWidth()](#getWidth--) | Возвращает или задает ширину заголовка как долю ширины диаграммы. |
| [setWidth(float value)](#setWidth-float-) | Возвращает или задает ширину заголовка как долю ширины диаграммы. |
| [getHeight()](#getHeight--) | Возвращает или задает высоту заголовка как долю высоты диаграммы. |
| [setHeight(float value)](#setHeight-float-) | Возвращает или задает высоту заголовка как долю высоты диаграммы. |
| [getRight()](#getRight--) | Справа. |
| [getBottom()](#getBottom--) | Снизу. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Возвращает формат подписи данных. |
| [getValueFromCell()](#getValueFromCell--) | Получает или задает ячейку данных рабочей книги. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Получает или задает ячейку данных рабочей книги. |
| [getActualX()](#getActualX--) | Указывает фактическое положение x (лево) элемента диаграммы относительно левого верхнего угла диаграммы. |
| [getActualY()](#getActualY--) | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. |
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

**Возврат:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возврат:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Ложь означает, что подпись данных не видна (и поэтому все флаги Show\*-flags (ShowValue, ...) имеют значение false). Только для чтения boolean.

--------------------

Если подпись данных видима, её можно скрыть методом Hide(). Но если подпись данных не видима (IsVisible равно false), её можно сделать видимой, установив флаги Show\*-flags (ShowValue, ...) в состояние true.

**Возврат:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Скрывает подпись данных, устанавливая все флаги Show\*-flags (ShowValue, ...) в состояние false. После этого IsVisible будет false.

--------------------

Если подпись данных не видима (IsVisible is false) вы можете сделать её видимой, установив флаги Show\*-flags (ShowValue, ...) в состояние true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Возвращает фактический текст подписи на основе настроек DataLabelFormat или значение TextFrameForOverriding.Text.

**Возврат:**
java.lang.String - объект java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Инициализирует TextFrameForOverriding текстом из параметра "text". Если TextFrameForOverriding уже инициализирован, то просто изменяет его текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для нового TextFrameForOverriding. |

**Возврат:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Может содержать текст с расширенным форматированием. Если это свойство не null, то это отформатированное текстовое значение переопределяет автоматически сгенерированный текст подписи данных. Автоматически сгенерированный текст подписи данных — это текст, управляемый свойствами ShowSeriesName, ShowValue, ... и отформатированный свойством TextFormatManager.TextFormat. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возврат:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Возвращает формат текста. Только для чтения [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возврат:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Возвращает или задает координату x заголовка как долю ширины диаграммы. Чтение/запись float.

**Возврат:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Возвращает или задает координату x заголовка как долю ширины диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Возвращает или задает координату y заголовка как долю высоты диаграммы. Чтение/запись float.

**Возврат:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Возвращает или задает координату y заголовка как долю высоты диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Возвращает или задает ширину заголовка как долю ширины диаграммы. Чтение/запись float.

**Возврат:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Возвращает или задает ширину заголовка как долю ширины диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Возвращает или задает высоту заголовка как долю высоты диаграммы. Чтение/запись float.

**Возврат:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Возвращает или задает высоту заголовка как долю высоты диаграммы. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Справа. Только для чтения float.

**Возврат:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Снизу. Только для чтения float.

**Возврат:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Возвращает формат подписи данных. Только для чтения [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Возврат:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Получает или задает ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Возврат:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Получает или задает ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Указывает фактическое положение x (лево) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Чтение float.

**Возврат:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Чтение float.

**Возврат:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Чтение float.

**Возврат:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Чтение float.

**Возврат:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возврат:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возврат:**
[IPresentation](../../com.aspose.slides/ipresentation)