---
title: IDataLabelFormat
second_title: Aspose.Slides dla Androida - referencja API Java
description: Reprezentuje opcje formatowania dla DataLabel.
type: docs
url: /pl/com.aspose.slides/idatalabelformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Reprezentuje opcje formatowania dla DataLabel.
## Metody

| Metoda | Opis |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Odczyt/zapis boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Odczyt/zapis boolean. |
| [getNumberFormat()](#getNumberFormat--) | Reprezentuje ciąg formatu dla obiektu DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Reprezentuje ciąg formatu dla obiektu DataLabels. |
| [getFormat()](#getFormat--) | Reprezentuje format etykiety danych. |
| [getPosition()](#getPosition--) | Reprezentuje pozycję etykiety danych. |
| [setPosition(int value)](#setPosition-int-) | Reprezentuje pozycję etykiety danych. |
| [getShowLegendKey()](#getShowLegendKey--) | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. |
| [getShowValue()](#getShowValue--) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [getShowCategoryName()](#getShowCategoryName--) | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. |
| [getShowSeriesName()](#getShowSeriesName--) | Zwraca lub ustawia Boolean określający zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Zwraca lub ustawia Boolean określający zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. |
| [getShowPercentage()](#getShowPercentage--) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako data callout lub jako etykieta danych. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako data callout lub jako etykieta danych. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. |
| [getSeparator()](#getSeparator--) | Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości IsNumberFormatLinkedToSource dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości IsNumberFormatLinkedToSource dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val).

**Zwraca:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości IsNumberFormatLinkedToSource dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości IsNumberFormatLinkedToSource dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Reprezentuje ciąg formatu dla obiektu DataLabels. Odczyt/zapis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji DataLabelCollection. Gdy właściwość ta zostanie ustawiona na określoną wartość, ta sama wartość jest również ustawiana w właściwości NumberFormat dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

**Zwraca:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Reprezentuje ciąg formatu dla obiektu DataLabels. Odczyt/zapis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji DataLabelCollection. Gdy właściwość ta zostanie ustawiona na określoną wartość, ta sama wartość jest również ustawiana w właściwości NumberFormat dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje format etykiety danych. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta reprezentuje domyślny format dla nowych etykiet danych w kolekcji DataLabelCollection.

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Reprezentuje pozycję etykiety danych. Odczyt/zapis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection. Reprezentuje pozycję dla obiektów DataLabel. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości Position dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Zwraca:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Reprezentuje pozycję etykiety danych. Odczyt/zapis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection. Reprezentuje pozycję dla obiektów DataLabel. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości Position dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. True if the data label legend key is visible. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLegendKey dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLegendKey dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**Zwraca:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. True if the data label legend key is visible. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLegendKey dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLegendKey dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True displays the percentage value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowValue dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Zwraca:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True displays the percentage value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowValue dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. True to display the category name for the data labels on a chart. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowCategoryName dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Zwraca:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. True to display the category name for the data labels on a chart. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowCategoryName dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Zwraca lub ustawia Boolean określający zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. True to show the series name. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowSeriesName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowSeriesName dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Zwraca:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Zwraca lub ustawia Boolean określający zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. True to show the series name. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowSeriesName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowSeriesName dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True displays the percentage value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowPercentage dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowPercentage dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Zwraca:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True displays the percentage value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowPercentage dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowPercentage dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. True displays the bubble size value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowBubbleSize dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowBubbleSize dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Zwraca:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. True displays the bubble size value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowBubbleSize dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowBubbleSize dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. True displays the leader lines. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLeaderLines dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLeaderLines dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Zwraca:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. True displays the leader lines. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLeaderLines dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLeaderLines dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako data callout lub jako etykieta danych.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLabelAsDataCallout dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLabelAsDataCallout dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Zwraca:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako data callout lub jako etykieta danych.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLabelAsDataCallout dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLabelAsDataCallout dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. True displays cell value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLabelValueFromCell dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLabelValueFromCell dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Zwraca:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. True displays cell value. False to hide. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości ShowLabelValueFromCell dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowLabelValueFromCell dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Odczyt/zapis String.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości Separator dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości Separator dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Zwraca:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Odczyt/zapis String.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to właściwość ta pobiera lub ustawia domyślną wartość właściwości Separator dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości Separator dla wszystkich etykiet danych w kolekcji DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |