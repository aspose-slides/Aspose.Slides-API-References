---
title: IDataLabel
second_title: Справочник API Aspose.Slides для Java
description: Представляет метки серии.
type: docs
url: /ru/com.aspose.slides/idatalabel/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Представляет метки серии.
## Методы

| Метод | Описание |
| --- | --- |
| [isVisible()](#isVisible--) | False означает, что метка данных не видима (и поэтому все Show*-flags (ShowValue, ...) имеют значение false). |
| [hide()](#hide--) | Сделайте метку данных скрытой, установив все Show*-flags (ShowValue, ...) в состояние false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Возвращает формат метки данных. |
| [getValueFromCell()](#getValueFromCell--) | Получает или задает ячейку данных рабочей книги. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Получает или задает ячейку данных рабочей книги. |
| [getActualLabelText()](#getActualLabelText--) | Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False означает, что метка данных не видима (и поэтому все Show*-flags (ShowValue, ...) имеют значение false). Только для чтения boolean.

--------------------

Если метка данных видима, её можно скрыть с помощью метода Hide(). Но если метка данных не видима (IsVisible равно false), её можно сделать видимой, установив Show*-flags (ShowValue, ...) в состояние true.

**Возвращаемое значение:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Сделайте метку данных скрытой, установив все Show*-flags (ShowValue, ...) в состояние false. После этого IsVisible будет равно false.

--------------------

Если метка данных не видима (IsVisible равно false), её можно сделать видимой, установив Show*-flags (ShowValue, ...) в состояние true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Возвращает формат метки данных. Только для чтения [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Возвращаемое значение:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Получает или задает ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Получает или задает ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text.

**Возвращаемое значение:**
java.lang.String - Actual label text String