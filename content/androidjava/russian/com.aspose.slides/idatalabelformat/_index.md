---
title: IDataLabelFormat
second_title: Aspose.Slides для Android через Java API
description: Представляет параметры форматирования для DataLabel.
type: docs
url: /ru/com.aspose.slides/idatalabelformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Представляет параметры форматирования для DataLabel.
## Методы

| Метод | Описание |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Чтение/запись boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Чтение/запись boolean. |
| [getNumberFormat()](#getNumberFormat--) | Представляет строку формата для объекта DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Представляет строку формата для объекта DataLabels. |
| [getFormat()](#getFormat--) | Представляет формат метки данных. |
| [getPosition()](#getPosition--) | Представляет положение метки данных. |
| [setPosition(int value)](#setPosition-int-) | Представляет положение метки данных. |
| [getShowLegendKey()](#getShowLegendKey--) | Представляет поведение отображения ключа легенды метки данных указанного графика. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Представляет поведение отображения ключа легенды метки данных указанного графика. |
| [getShowValue()](#getShowValue--) | Представляет поведение отображения значения процента метки данных указанного графика. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Представляет поведение отображения значения процента метки данных указанного графика. |
| [getShowCategoryName()](#getShowCategoryName--) | Представляет поведение отображения названия категории метки данных указанного графика. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Представляет поведение отображения названия категории метки данных указанного графика. |
| [getShowSeriesName()](#getShowSeriesName--) | Возвращает или задаёт Boolean, указывающий поведение отображения названия серии для меток данных на графике. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Возвращает или задаёт Boolean, указывающий поведение отображения названия серии для меток данных на графике. |
| [getShowPercentage()](#getShowPercentage--) | Представляет поведение отображения значения процента метки данных указанного графика. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Представляет поведение отображения значения процента метки данных указанного графика. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Представляет поведение отображения значения размера пузыря метки данных указанного графика. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Представляет поведение отображения значения размера пузыря метки данных указанного графика. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Представляет поведение отображения линий-провода метки данных указанного графика. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Представляет поведение отображения линий-провода метки данных указанного графика. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Определяет, будет ли указанная метка данных отображаться как выноска данных или как метка данных. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Определяет, будет ли указанная метка данных отображаться как выноска данных или как метка данных. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Представляет поведение отображения значения ячейки метки данных указанного графика. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Представляет поведение отображения значения ячейки метки данных указанного графика. |
| [getSeparator()](#getSeparator--) | Задает или возвращает Variant, представляющий разделитель, используемый для меток данных на графике. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Задает или возвращает Variant, представляющий разделитель, используемый для меток данных на графике. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства IsNumberFormatLinkedToSource для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству IsNumberFormatLinkedToSource для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" приводит к тому, что у всех DataLabels.get\_Item(i).isNumberFormatLinkedToSource() будет равно val).

**Возвращает:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства IsNumberFormatLinkedToSource для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству IsNumberFormatLinkedToSource для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" приводит к тому, что у всех DataLabels.get\_Item(i).isNumberFormatLinkedToSource() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Представляет строку формата для объекта DataLabels. Чтение/запись String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства NumberFormat для новых меток данных в коллекции DataLabelCollection. При установке этого свойства значение также задаётся свойству NumberFormat для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getNumberFormat() будет равно val).

**Возвращает:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Представляет строку формата для объекта DataLabels. Чтение/запись String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства NumberFormat для новых меток данных в коллекции DataLabelCollection. При установке этого свойства значение также задаётся свойству NumberFormat для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getNumberFormat() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Представляет формат метки данных. Только для чтения [IFormat](../../com.aspose.slides/iformat).

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство представляет формат по умолчанию для новых меток данных в коллекции DataLabelCollection.

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Представляет положение метки данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства Position для новых меток данных в коллекции DataLabelCollection. Представляет положение объектов DataLabel. Установка этого свойства со значением также задаёт это значение свойству Position для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setPosition(val)" приводит к тому, что у всех DataLabels.get\_Item(i).getPosition() будет равно val).

**Возвращает:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Представляет положение метки данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства Position для новых меток данных в коллекции DataLabelCollection. Представляет положение объектов DataLabel. Установка этого свойства со значением также задаёт это значение свойству Position для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setPosition(val)" приводит к тому, что у всех DataLabels.get\_Item(i).getPosition() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Представляет поведение отображения ключа легенды метки данных указанного графика. True если ключ легенды метки данных видим. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLegendKey для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLegendKey для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLegendKey() будет равно val).

**Возвращает:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Представляет поведение отображения ключа легенды метки данных указанного графика. True если ключ легенды метки данных видим. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLegendKey для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLegendKey для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLegendKey() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Представляет поведение отображения значения процента метки данных указанного графика. True отображает значение процента. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowValue для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowValue для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowValue() будет равно val).

**Возвращает:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Представляет поведение отображения значения процента метки данных указанного графика. True отображает значение процента. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowValue для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowValue для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowValue() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Представляет поведение отображения названия категории метки данных указанного графика. True отображает название категории для меток данных на графике. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowCategoryName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowCategoryName для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowCategoryName() будет равно val).

**Возвращает:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Представляет поведение отображения названия категории метки данных указанного графика. True отображает название категории для меток данных на графике. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowCategoryName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowCategoryName для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowCategoryName() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Возвращает или задаёт Boolean, указывающий поведение отображения названия серии для меток данных на графике. True отображает название серии. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowSeriesName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowSeriesName для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowSeriesName() будет равно val).

**Возвращает:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Возвращает или задаёт Boolean, указывающий поведение отображения названия серии для меток данных на графике. True отображает название серии. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowSeriesName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowSeriesName для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowSeriesName() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Представляет поведение отображения значения процента метки данных указанного графика. True отображает значение процента. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowPercentage для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowPercentage для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowPercentage() будет равно val).

**Возвращает:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Представляет поведение отображения значения процента метки данных указанного графика. True отображает значение процента. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowPercentage для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowPercentage для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowPercentage() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Представляет поведение отображения значения размера пузыря метки данных указанного графика. True отображает значение размера пузыря. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowBubbleSize для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowBubbleSize для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowBubbleSize() будет равно val).

**Возвращает:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Представляет поведение отображения значения размера пузыря метки данных указанного графика. True отображает значение размера пузыря. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowBubbleSize для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowBubbleSize для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowBubbleSize() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Представляет поведение отображения линий-провода метки данных указанного графика. True отображает линии-провод. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLeaderLines для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLeaderLines для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLeaderLines() будет равно val).

**Возвращает:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Представляет поведение отображения линий-провода метки данных указанного графика. True отображает линии-провод. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLeaderLines для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLeaderLines для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLeaderLines() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Определяет, будет ли указанная метка данных отображаться как выноска данных или как метка данных.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLabelAsDataCallout() будет равно val).

**Возвращает:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Определяет, будет ли указанная метка данных отображаться как выноска данных или как метка данных.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLabelAsDataCallout() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Представляет поведение отображения значения ячейки метки данных указанного графика. True отображает значение ячейки. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelValueFromCell для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLabelValueFromCell для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLabelValueFromCell() будет равно val).

**Возвращает:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Представляет поведение отображения значения ячейки метки данных указанного графика. True отображает значение ячейки. False скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelValueFromCell для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству ShowLabelValueFromCell для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLabelValueFromCell() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Задает или возвращает Variant, представляющий разделитель, используемый для меток данных на графике. Чтение/запись String.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства Separator для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству Separator для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getSeparator() будет равно val).

**Возвращает:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Задает или возвращает Variant, представляющий разделитель, используемый для меток данных на графике. Чтение/запись String.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задаёт значение по умолчанию свойства Separator для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задаёт это значение свойству Separator для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getSeparator() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |