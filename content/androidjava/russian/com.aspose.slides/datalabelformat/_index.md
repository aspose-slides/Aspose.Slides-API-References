---
title: DataLabelFormat
second_title: Aspose.Slides для Android через справочник Java API
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
| [getShowLegendKey()](#getShowLegendKey--) | Представляет поведение отображения ключа легенды подписи данных указанного chart. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Представляет поведение отображения ключа легенды подписи данных указанного chart. |
| [getShowValue()](#getShowValue--) | Представляет поведение отображения процентного значения подписи данных указанного chart. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Представляет поведение отображения процентного значения подписи данных указанного chart. |
| [getShowCategoryName()](#getShowCategoryName--) | Представляет поведение отображения имени категории подписи данных указанного chart. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Представляет поведение отображения имени категории подписи данных указанного chart. |
| [getShowSeriesName()](#getShowSeriesName--) | Возвращает или задает Boolean, указывающий поведение отображения имени серии для подписей данных на chart. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Возвращает или задает Boolean, указывающий поведение отображения имени серии для подписей данных на chart. |
| [getShowPercentage()](#getShowPercentage--) | Представляет поведение отображения процентного значения подписи данных указанного chart. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Представляет поведение отображения процентного значения подпиши данных указанного chart. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Представляет поведение отображения значения размера пузыря подписи данных указанного chart. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Представляет поведение отображения значения размера пузыря подписи данных указанного chart. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Представляет поведение отображения выносок подписи данных указанного chart. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Представляет поведение отображения выносок подписи данных указанного chart. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Представляет поведение отображения значения ячейки подписи данных указанного chart. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Представляет поведение отображения значения ячейки подписи данных указанного chart. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Определяет, будет ли подпись данных указанного chart отображаться как выноска данных или как подпись данных. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Определяет, будет ли подпись данных указанного chart отображаться как выноска данных или как подпись данных. |
| [getSeparator()](#getSeparator--) | Задает или возвращает Variant, представляющий разделитель, используемый для подписей данных на chart. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Задает или возвращает Variant, представляющий разделитель, используемый для подписей данных на chart. |
| [getTextFormat()](#getTextFormat--) | Возвращает формат текста chart. |
| [getChart()](#getChart--) | Возвращает chart. |
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

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства IsNumberFormatLinkedToSource для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству IsNumberFormatLinkedToSource для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" приводит к тому, что для всех DataLabels.get_Item(i).isNumberFormatLinkedToSource() значение равно val).

**Возвращает:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства IsNumberFormatLinkedToSource для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству IsNumberFormatLinkedToSource для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" приводит к тому, что для всех DataLabels.get_Item(i).isNumberFormatLinkedToSource() значение равно val).

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
> ```

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства NumberFormat для новых подписей данных в коллекции DataLabelCollection. При установке этого свойства значение также задаётся свойству NumberFormat для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" приводит к тому, что для всех DataLabels.get_Item(i).getNumberFormat() значение равно val).

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
> ```

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства NumberFormat для новых подписей данных в коллекции DataLabelCollection. При установке этого свойства значение также задаётся свойству NumberFormat для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" приводит к тому, что для всех DataLabels.get_Item(i).getNumberFormat() значение равно val).

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

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство представляет формат по умолчанию для новых подписей данных в коллекции DataLabelCollection.

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Представляет позицию подписи данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства Position для новых подписей данных в коллекции DataLabelCollection. Представляет позицию для объектов DataLabel. Установка этого свойства со значением также задает это значение свойству Position для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setPosition(val);" приводит к тому, что для всех DataLabels.get_Item(i).getPosition() значение равно val).

**Возвращает:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Представляет позицию подписи данных. Чтение/запись [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства Position для новых подписей данных в коллекции DataLabelCollection. Представляет позицию для объектов DataLabel. Установка этого свойства со значением также задает это значение свойству Position для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setPosition(val);" приводит к тому, что для всех DataLabels.get_Item(i).getPosition() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```


Представляет поведение отображения ключа легенды подписи данных указанного chart. True, если ключ легенды подписи данных видим. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLegendKey для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLegendKey для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLegendKey() значение равно val).

**Возвращает:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```


Представляет поведение отображения ключа легенды подписи данных указанного chart. True, если ключ легенды подписи данных видим. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLegendKey для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLegendKey для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLegendKey() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```


Представляет поведение отображения процентного значения подписи данных указанного chart. True отображает процентное значение. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowValue для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowValue для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowValue() значение равно val).

**Возвращает:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```


Представляет поведение отображения процентного значения подписи данных указанного chart. True отображает процентное значение. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowValue для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowValue для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowValue() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```


Представляет поведение отображения имени категории подписи данных указанного chart. True отображает имя категории для подписей данных на chart. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowCategoryName для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowCategoryName для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowCategoryName() значение равно val).

**Возвращает:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```


Представляет поведение отображения имени категории подписи данных указанного chart. True отображает имя категории для подписей данных на chart. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowCategoryName для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowCategoryName для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowCategoryName() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```


Возвращает или задает Boolean, указывающий поведение отображения имени серии для подписей данных на chart. True отображает имя серии. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowSeriesName для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowSeriesName() значение равно val).

**Возвращает:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```


Возвращает или задает Boolean, указывающий поведение отображения имени серии для подписей данных на chart. True отображает имя серии. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowSeriesName для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowSeriesName для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowSeriesName() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```


Представляет поведение отображения процентного значения подписи данных указанного chart. True отображает процентное значение. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowPercentage для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowPercentage для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowPercentage() значение равно val).

**Возвращает:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```


Представляет поведение отображения процентного значения подписи данных указанного chart. True отображает процентное значение. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowPercentage для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowPercentage для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowPercentage() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```


Представляет поведение отображения значения размера пузыря подписи данных указанного chart. True отображает значение размера пузыря. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowBubbleSize для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowBubbleSize() значение равно val).

**Возвращает:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```


Представляет поведение отображения значения размера пузыря подписи данных указанного chart. True отображает значение размера пузыря. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowBubbleSize для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowBubbleSize() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```


Представляет поведение отображения выносок подписи данных указанного chart. True отображает выноски. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLeaderLines для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLeaderLines() значение равно val).

**Возвращает:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```


Представляет поведение отображения выносок подписи данных указанного chart. True отображает выноски. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLeaderLines для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLeaderLines для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLeaderLines() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```


Представляет поведение отображения значения ячейки подписи данных указанного chart. True отображает значение ячейки. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelValueFromCell для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelValueFromCell для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLabelValueFromCell() значение равно val).

**Возвращает:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```


Представляет поведение отображения значения ячейки подписи данных указанного chart. True отображает значение ячейки. False, чтобы скрыть. Чтение/запись boolean.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelValueFromCell для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelValueFromCell для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLabelValueFromCell() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```


Определяет, будет ли подпись данных указанного chart отображаться как выноска данных или как подпись данных.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLabelAsDataCallout() значение равно val).

**Возвращает:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```


Определяет, будет ли подпись данных указанного chart отображаться как выноска данных или как подпись данных.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству ShowLabelAsDataCallout для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" приводит к тому, что для всех DataLabels.get_Item(i).getShowLabelAsDataCallout() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Задает или возвращает Variant, представляющий разделитель, используемый для подписей данных на chart. Чтение/запись String.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству Separator для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что для всех DataLabels.get_Item(i).getSeparator() значение равно val).

**Возвращает:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Задает или возвращает Variant, представляющий разделитель, используемый для подписей данных на chart. Чтение/запись String.

--------------------

Если родитель этого объекта DataLabelFormat является коллекцией DataLabelCollection подписей данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых подписей данных в коллекции DataLabelCollection. Установка этого свойства со значением также задает это значение свойству Separator для всех подписей данных в коллекции DataLabelCollection (например, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" приводит к тому, что для всех DataLabels.get_Item(i).getSeparator() значение равно val).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Возвращает формат текста chart. Только для чтения [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращает:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Возвращает chart. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)