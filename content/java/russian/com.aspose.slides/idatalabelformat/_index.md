---
title: IDataLabelFormat
second_title: Aspose.Slides для Java — справка API
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
| [getFormat()](#getFormat--) | Представляет формат подписи данных. |
| [getPosition()](#getPosition--) | Представляет позицию подписи данных. |
| [setPosition(int value)](#setPosition-int-) | Представляет позицию подписи данных. |
| [getShowLegendKey()](#getShowLegendKey--) | Представляет поведение отображения ключа легенды подписи данных указанного диаграммы. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Представляет поведение отображения ключа легенды подписи данных указанного диаграммы. |
| [getShowValue()](#getShowValue--) | Представляет поведение отображения процентного значения подписи данных указанного диаграммы. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Представляет поведение отображения процентного значения подписи данных указанного диаграммы. |
| [getShowCategoryName()](#getShowCategoryName--) | Представляет поведение отображения имени категории подписи данных указанного диаграммы. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Представляет поведение отображения имени категории подписи данных указанного диаграммы. |
| [getShowSeriesName()](#getShowSeriesName--) | Возвращает или задает Boolean, указывающий, отображать ли имя ряда для подписей данных на диаграмме. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Возвращает или задает Boolean, указывающий, отображать ли имя ряда для подписей данных на диаграмме. |
| [getShowPercentage()](#getShowPercentage--) | Представляет поведение отображения процентного значения подписи данных указанного диаграммы. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Представляет поведение отображения процентного значения подписи данных указанного диаграммы. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Представляет поведение отображения значения размера пузыря подписи данных указанного диаграммы. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Представляет поведение отображения значения размера пузыря подписи данных указанного диаграммы. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Представляет поведение отображения линий-проводников подписи данных указанного диаграммы. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Представляет поведение отображения линий-проводников подписи данных указанного диаграммы. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Определяет, будет ли подпись данных указанного диаграммы отображаться как выноска или как подпись данных. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Определяет, будет ли подпись данных указанного диаграммы отображаться как выноска или как подпись данных. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Представляет поведение отображения значения ячейки подписи данных указанного диаграммы. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Представляет поведение отображения значения ячейки подписи данных указанного диаграммы. |
| [getSeparator()](#getSeparator--) | Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства IsNumberFormatLinkedToSource по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает то же значение свойства IsNumberFormatLinkedToSource для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);» приводит к тому, что у всех DataLabels.get_Item(i).isNumberFormatLinkedToSource() будет значение val).

**Возвращает:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства IsNumberFormatLinkedToSource по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает то же значение свойства IsNumberFormatLinkedToSource для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);» приводит к тому, что у всех DataLabels.get_Item(i).isNumberFormatLinkedToSource() будет значение val).

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

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства NumberFormat по умолчанию для новых подписей данных в коллекции DataLabelCollection. При установке этого свойства его значение также задаётся для свойства NumberFormat всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);» приводит к тому, что у всех DataLabels.get_Item(i).getNumberFormat() будет значение val).

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

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства NumberFormat по умолчанию для новых подписей данных в коллекции DataLabelCollection. При установке этого свойства его значение также задаётся для свойства NumberFormat всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);» приводит к тому, что у всех DataLabels.get_Item(i).getNumberFormat() будет значение val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Представляет формат подписи данных. Только чтение [IFormat](../../com.aspose.slides/iformat).

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство представляет формат по умолчанию для новых подписей данных в коллекции DataLabelCollection.

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Представляет позицию подписи данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства Position по умолчанию для новых подписей данных в коллекции DataLabelCollection. Представляет позицию для объектов DataLabel. Установка этого свойства также задает то же значение свойства Position для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setPosition(val)» приводит к тому, что у всех DataLabels.get_Item(i).getPosition() будет значение val).

**Возвращает:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Представляет позицию подписи данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства Position по умолчанию для новых подписей данных в коллекции DataLabelCollection. Представляет позицию для объектов DataLabel. Установка этого свойства также задает то же значение свойства Position для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setPosition(val)» приводит к тому, что у всех DataLabels.get_Item(i).getPosition() будет значение val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Представляет поведение отображения ключа легенды подписи данных указанного диаграммы. Истина, если ключ легенды подписи данных видим. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства ShowLegendKey по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает то же значение свойства ShowLegendKey для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);» приводит к тому, что у всех DataLabels.get_Item(i).getShowLegendKey() будет значение val).

**Возвращает:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Представляет поведение отображения ключа легенды подписи данных указанного диаграммы. Истина, если ключ легенды подписи данных видим. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства ShowLegendKey по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает то же значение свойства ShowLegendKey для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);» приводит к тому, что у всех DataLabels.get_Item(i).getShowLegendKey() будет значение val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Представляет поведение отображения процентного значения подписи данных указанного диаграммы. Истина отображает процентное значение. Ложь скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства ShowValue по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает то же значение свойства ShowValue для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setShowValue(val);» приводит к тому, что у всех DataLabels.get_Item(i).getShowValue() будет значение val).

**Возвращает:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Представляет поведение отображения процентного значения подписи данных указанного диаграммы. Истина отображает процентное значение. Ложь скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства ShowValue по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает то же значение свойства ShowValue для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setShowValue(val);» приводит к тому, что у всех DataLabels.get_Item(i).getShowValue() будет значение val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Представляет поведение отображения имени категории подписи данных указанного диаграммы. Истина отображает имя категории для подписей данных на диаграмме. Ложь скрывает. Чтение/запись boolean.

--------------------

Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection подпичей данных, то это свойство получает или задает значение свойства ShowCategoryName по умолчанию для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства также задает то же значение свойства ShowCategoryName для всех подписей данных в коллекции DataLabelCollection (т. е. «DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);» приводит к тому, что у всех DataLabels.get_Item(i).getShowCategoryName() будет значение val).

**Возвращает:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Представляет поведение отображения имени категории подписи данных указанного диаграммы. Истина отображает имя категории для подписей данных на диаграмме. Ложь скрывает. Чтение/запись boolean.

--------------------
Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowCategoryName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowCategoryName для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowCategoryName() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Возвращает или задает Boolean, указывающий поведение отображения имени серии для меток данных на диаграмме. True — показывать имя серии. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowSeriesName для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowSeriesName() будет равно val).

**Возвращаемое значение:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Возвращает или задает Boolean, указывающий поведение отображения имени серии для меток данных на диаграмме. True — показывать имя серии. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowSeriesName для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowSeriesName() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Представляет поведение отображения процентного значения метки данных на указанной диаграмме. True — отображать процентное значение. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowPercentage для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowPercentage для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowPercentage() будет равно val).

**Возвращаемое значение:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Представляет поведение отображения процентного значения метки данных на указанной диаграмме. True — отображать процентное значение. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowPercentage для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowPercentage для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowPercentage() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Представляет поведение отображения размера пузыря метки данных на указанной диаграмме. True — отображать размер пузыря. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowBubbleSize для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowBubbleSize() будет равно val).

**Возвращаемое значение:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Представляет поведение отображения размера пузыря метки данных на указанной диаграмме. True — отображать размер пузыря. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowBubbleSize для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowBubbleSize() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Представляет поведение отображения линий-выноса метки данных на указанной диаграмме. True — отображать линии-выносы. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLeaderLines для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLeaderLines() будет равно val).

**Возвращаемое значение:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Представляет поведение отображения линий-выноса метки данных на указанной диаграмме. True — отображать линии-выносы. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLeaderLines для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLeaderLines() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Определяет, будет ли метка данных указанной диаграммы отображаться как выноска данных или как обычная метка данных.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelAsDataCallout() будет равно val).

**Возвращаемое значение:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Определяет, будет ли метка данных указанной диаграммы отображаться как выноска данных или как обычная метка данных.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelAsDataCallout() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Представляет поведение отображения значения ячейки метки данных на указанной диаграмме. True — отображать значение ячейки. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelValueFromCell для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelValueFromCell для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelValueFromCell() будет равно val).

**Возвращаемое значение:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Представляет поведение отображения значения ячейки метки данных на указанной диаграмме. True — отображать значение ячейки. False — скрывать. Чтение/запись boolean.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelValueFromCell для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelValueFromCell для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что у всех DataLabels.get_Item(i).getShowLabelValueFromCell() будет равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. Чтение/запись String.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству Separator для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что у всех DataLabels.get_Item(i).getSeparator() будет равно val).

**Возвращаемое значение:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. Чтение/запись String.

--------------------

Если родительским объектом DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых меток данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству Separator для всех меток данных в коллекции DataLabelCollection (например "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что у всех DataLabels.get_Item(i).getSeparator() будет равно val).
**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |