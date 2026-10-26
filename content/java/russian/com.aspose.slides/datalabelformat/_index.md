---
title: DataLabelFormat
second_title: Справочник API Aspose.Slides для Java
description: Представляет параметры форматирования для DataLabel.
type: docs
url: /ru/com.aspose.slides/datalabelformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Представляет параметры форматирования для DataLabel.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Чтение/запись boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Чтение/запись boolean. |
| [getNumberFormat()](#getNumberFormat--) | Представляет строку формата для объекта DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Представляет строку формата для объекта DataLabels. |
| [getFormat()](#getFormat--) | Представляет формат подписи данных. |
| [getPosition()](#getPosition--) | Представляет позицию подписи данных. |
| [setPosition(int value)](#setPosition-int-) | Представляет позицию подписи данных. |
| [getShowLegendKey()](#getShowLegendKey--) | Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. |
| [getShowValue()](#getShowValue--) | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. |
| [getShowCategoryName()](#getShowCategoryName--) | Представляет поведение отображения имени категории подписи данных указанной диаграммы. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Представляет поведение отображения имени категории подписи данных указанной диаграммы. |
| [getShowSeriesName()](#getShowSeriesName--) | Возвращает или задаёт Boolean, указывающий поведение отображения имени серии для подписей данных на диаграмме. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Возвращает или задаёт Boolean, указывающий поведение отображения имени серии для подписей данных на диаграмме. |
| [getShowPercentage()](#getShowPercentage--) | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Представляет поведение отображения линий-выноски подписи данных указанной диаграммы. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Представляет поведение отображения линий-выноски подписи данных указанной диаграммы. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Определяет, будет ли подпись данных указанной диаграммы отображаться как выноска данных или как подпись данных. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Определяет, будет ли подпись данных указанной диаграммы отображаться как выноска данных или как подпись данных. |
| [getSeparator()](#getSeparator--) | Задаёт или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Задаёт или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. |
| [getTextFormat()](#getTextFormat--) | Возвращает текстовый формат диаграммы. |
| [getChart()](#getChart--) | Возвращает диаграмму. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Чтение/запись boolean.

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства IsNumberFormatLinkedToSource по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства значением также задаёт это значение свойству IsNumberFormatLinkedToSource для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" приводит к тому, что у всех DataLabels.get\_Item(i).isNumberFormatLinkedToSource() значение равно val).

**Возвращает:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Чтение/запись boolean.

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства IsNumberFormatLinkedToSource по умолчанию для новых подписи данных в коллекции DataLabelCollection. Установка этого свойства значением также задаёт это значение свойству IsNumberFormatLinkedToSource для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" приводит к тому, что у всех DataLabels.get\_Item(i).isNumberFormatLinkedToSource() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Представляет строку формата для объекта DataLabels. Чтение/запись String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
```

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства NumberFormat по умолчанию для новых подписей данных в коллекции DataLabelCollection. Когда это свойство задаётся значением, это значение также задаётся свойству NumberFormat для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getNumberFormat() значение равно val).

**Возвращает:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Представляет строку формата для объекта DataLabels. Чтение/запись String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
```

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства NumberFormat по умолчанию для новых подписей данных в коллекции DataLabelCollection. Когда это свойство задаётся значением, это значение также задаётся свойству NumberFormat для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getNumberFormat() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Представляет формат подписи данных. Только для чтения [IFormat](../../com.aspose.slides/iformat).

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство представляет формат по умолчанию для новых подписей данных в коллекции DataLabelCollection.

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Представляет позицию подписи данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства Position по умолчанию для новых подписей данных в коллекции DataLabelCollection. Представляет позицию для объектов DataLabel. Установка этого свойства значением также задаёт это значение свойству Position для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setPosition(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getPosition() значение равно val).

**Возвращает:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Представляет позицию подписи данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства Position по умолчанию для новых подписей данных в коллекции DataLabelCollection. Представляет позицию для объектов DataLabel. Установка этого свойства значением также задаёт это значение свойству Position для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setPosition(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getPosition() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. True если ключ легенды подписи данных видим. Чтение/запись boolean.

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства ShowLegendKey по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства значением также задаёт это значение свойству ShowLegendKey для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLegendKey() значение равно val).

**Возвращает:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. True если ключ легенды подписи данных видим. Чтение/запись boolean.

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства ShowLegendKey по умолчанию для новых подписи данных в коллекции DataLabelCollection. Установка этого свойства значением также задаёт это значение свойству ShowLegendKey для всех подписи данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowLegendKey() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Представляет поведение отображения процентного значения подписи данных указанной диаграммы. True отображает процентное значение. False скрывает. Чтение/запись boolean.

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства ShowValue по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства значением также задаёт это значение свойству ShowValue для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowValue() значение равно val).

**Возвращает:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Представляет поведение отображения процентного значения подписи данных указанной диаграммы. True отображает процентное значение. False скрывает. Чтение/запись boolean.

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства ShowValue по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства значением также задаёт это значение свойству ShowValue для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" приводит к тому, что у всех DataLabels.get\_Item(i).getShowValue() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Представляет поведение отображения имени категории подписи данных указанной диаграммы. True отображает имя категории для подписей данных на диаграмме. False скрывает. Чтение/запись boolean.

--------------------

Если родительским объектом этого DataLabelFormat является коллекция DataLabelCollection подписи данных, то это свойство получает или задаёт значение свойства ShowCategoryName по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства значением также задаёт это значение свойству ShowCategoryName для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" приводит к тому, что у всех DataLabels.get\_Item(i).showCategoryName() значение равно val).

**Возвращает:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Представляет поведение отображения имени категории подписи данных указанной диаграммы. True отображает имя категории для подписей данных на диаграмме. False скрывает. Чтение/запись boolean.

--------------------
Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowCategoryName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowCategoryName для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowCategoryName() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Возвращает или задает Boolean, указывающий поведение отображения имени серии для меток данных на диаграмме. True — показывать имя серии. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowSeriesName для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowSeriesName() значение равно val).

**Возврат:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Возвращает или задает Boolean, указывающий поведение отображения имени серии для меток данных на диаграмме. True — показывать имя серии. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowSeriesName для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowSeriesName() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Представляет поведение отображения значения процента в метках данных указанной диаграммы. True — отображать процент. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowPercentage для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowPercentage для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowPercentage() значение равно val).

**Возврат:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Представляет поведение отображения значения процента в метках данных указанной диаграммы. True — отображать процент. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowPercentage для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowPercentage для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowPercentage() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Представляет поведение отображения размера пузыря в метках данных указанной диаграммы. True — отображать размер пузыря. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowBubbleSize для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowBubbleSize() значение равно val).

**Возврат:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Представляет поведение отображения размера пузыря в метках данных указанной диаграммы. True — отображать размер пузыря. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowBubbleSize для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowBubbleSize() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Представляет поведение отображения линий-указателей в метках данных указанной диаграммы. True — отображать линии-указатели. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLeaderLines для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLeaderLines() значение равно val).

**Возврат:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Представляет поведение отображения линий-указателей в метках данных указанной диаграммы. True — отображать линии-указатели. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLeaderLines для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLeaderLines() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Представляет поведение отображения значения ячейки в метках данных указанной диаграммы. True — отображать значение ячейки. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelValueFromCell для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelValueFromCell для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelValueFromCell() значение равно val).

**Возврат:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Представляет поведение отображения значения ячейки в метках данных указанной диаграммы. True — отображать значение ячейки. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelValueFromCell для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelValueFromCell для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelValueFromCell() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Определяет, будет ли метка данных указанной диаграммы отображаться как всплывающий вызов данных или как обычная метка.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelAsDataCallout() значение равно val).

**Возврат:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Определяет, будет ли метка данных указанной диаграммы отображаться как всплывающий вызов данных или как обычная метка.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelAsDataCallout() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. Чтение/запись String.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству Separator для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что у всех DataLabels.get_Item(i).getSeparator() значение равно val).

**Возврат:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. Чтение/запись String.

--------------------

Если родительским объектом данного DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству Separator для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что у всех DataLabels.get_Item(i).getSeparator() значение равно val).
**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Возвращает формат текста диаграммы. Только для чтения [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращает:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)