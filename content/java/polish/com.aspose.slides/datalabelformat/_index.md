---
title: DataLabelFormat
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje opcje formatowania etykiety danych.
type: docs
url: /pl/com.aspose.slides/datalabelformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Reprezentuje opcje formatowania dla DataLabel.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Zmienna logiczna odczyt/zapis. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Zmienna logiczna odczyt/zapis. |
| [getNumberFormat()](#getNumberFormat--) | Reprezentuje ciąg formatu dla obiektu DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Reprezentuje ciąg formatu dla obiektu DataLabels. |
| [getFormat()](#getFormat--) | Reprezentuje format etykiety danych. |
| [getPosition()](#getPosition--) | Reprezentuje pozycję etykiety danych. |
| [setPosition(int value)](#setPosition-int-) | Reprezentuje pozycję etykiety danych. |
| [getShowLegendKey()](#getShowLegendKey--) | Reprezentuje zachowanie wyświetlania klucza legendy etykiet danych określonego wykresu. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Reprezentuje zachowanie wyświetlania klucza legendy etykiet danych określonego wykresu. |
| [getShowValue()](#getShowValue--) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiet danych określonego wykresu. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiet danych określonego wykresu. |
| [getShowCategoryName()](#getShowCategoryName--) | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiet danych określonego wykresu. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiet danych określonego wykresu. |
| [getShowSeriesName()](#getShowSeriesName--) | Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. |
| [getShowPercentage()](#getShowPercentage--) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiet danych określonego wykresu. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiet danych określonego wykresu. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiet danych określonego wykresu. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiet danych określonego wykresu. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Reprezentuje zachowanie wyświetlania linii prowadzących etykiet danych określonego wykresu. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Reprezentuje zachowanie wyświetlania linii prowadzących etykiet danych określonego wykresu. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Reprezentuje zachowanie wyświetlania wartości komórek etykiet danych określonego wykresu. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Reprezentuje zachowanie wyświetlania wartości komórek etykiet danych określonego wykresu. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Określa, czy etykieta danych określonego wykresu zostanie wyświetlona jako dymek danych czy jako etykieta danych. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Określa, czy etykieta danych określonego wykresu zostanie wyświetlona jako dymek danych czy jako etykieta danych. |
| [getSeparator()](#getSeparator--) | Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. |
| [getTextFormat()](#getTextFormat--) | Zwraca format tekstu wykresu. |
| [getChart()](#getChart--) | Zwraca wykres. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości IsNumberFormatLinkedToSource dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości z wartością ustawia również tę wartość dla właściwości IsNumberFormatLinkedToSource we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" powoduje, że wszystkie DataLabels.get_Item(i).isNumberFormatLinkedToSource() są równe val).

**Zwraca:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości IsNumberFormatLinkedToSource dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości z wartością ustawia również tę wartość dla właściwości IsNumberFormatLinkedToSource we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" powoduje, że wszystkie DataLabels.get_Item(i).isNumberFormatLinkedToSource() są równe val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Reprezentuje ciąg formatu dla obiektu DataLabels. Odczyt/zapis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji DataLabelCollection. Gdy ta właściwość jest ustawiona na wartość, ta wartość jest również ustawiana dla właściwości NumberFormat we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" powoduje, że wszystkie DataLabels.get_Item(i).getNumberFormat() są równe val).

**Zwraca:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Reprezentuje ciąg formatu dla obiektu DataLabels. Odczyt/zapis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji DataLabelCollection. Gdy ta właściwość jest ustawiona na wartość, ta wartość jest również ustawiana dla właściwości NumberFormat we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" powoduje, że wszystkie DataLabels.get_Item(i).getNumberFormat() są równe val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje format etykiety danych. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość reprezentuje domyślny format dla nowych etykiet danych w kolekcji DataLabelCollection.

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Reprezentuje pozycję etykiety danych. Odczyt/zapis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection. Reprezentuje pozycję obiektów DataLabel. Ustawienie tej właściwości na wartość ustawia również tę wartość dla właściwości Position we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" powoduje, że wszystkie DataLabels.get_Item(i).getPosition() są równe val).

**Zwraca:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Reprezentuje pozycję etykiety danych. Odczyt/zapis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection. Reprezentuje pozycję obiektów DataLabel. Ustawienie tej właściwości na wartość ustawia również tę wartość dla właściwości Position we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" powoduje, że wszystkie DataLabels.get_Item(i).getPosition() są równe val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Reprezentuje zachowanie wyświetlania klucza legendy etykiet danych określonego wykresu. Prawda, jeśli klucz legendy etykiety danych jest widoczny. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLegendKey dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości z wartością ustawia również tę wartość dla właściwości ShowLegendKey we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLegendKey() są równe val).

**Zwraca:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Reprezentuje zachowanie wyświetlania klucza legendy etykiet danych określonego wykresu. Prawda, jeśli klucz legendy etykiety danych jest widoczny. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLegendKey dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości z wartością ustawia również tę wartość dla właściwości ShowLegendKey we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLegendKey() są równe val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiet danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości z wartością ustawia również tę wartość dla właściwości ShowValue we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowValue() są równe val).

**Zwraca:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiet danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości z wartością ustawia również tę wartość dla właściwości ShowValue we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowValue() są równe val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Reprezentuje zachowanie wyświetlania nazwy kategorii etykiet danych określonego wykresu. Prawda wyświetla nazwę kategorii dla etykiet danych na wykresie. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości z wartością ustawia również tę wartość dla właściwości ShowCategoryName we wszystkich etykietach danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowCategoryName() są równe val).

**Zwraca:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Reprezentuje zachowanie wyświetlania nazwy kategorii etykiet danych określonego wykresu. Prawda wyświetla nazwę kategorii dla etykiet danych na wykresie. Fałsz ukrywa. Odczyt/zapis boolean.
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. True, aby wyświetlić nazwę serii. False, aby ukryć. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. True, aby wyświetlić nazwę serii. False, aby ukryć. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Zwraca:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. True wyświetla wartość procentową. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. True wyświetla wartość rozmiaru bąbelka. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Zwraca:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. True wyświetla wartość rozmiaru bąbelka. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Reprezentuje zachowanie wyświetlania linii prowadzących etykiet danych określonego wykresu. True wyświetla linie prowadzące. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Zwraca:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Reprezentuje zachowanie wyświetlania linii prowadzących etykiet danych określonego wykresu. True wyświetla linie prowadzące. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. True wyświetla wartość komórki. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Zwraca:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. True wyświetla wartość komórki. False ukrywa. Odczyt/zapis boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako odwołanie danych czy jako etykieta danych.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Zwraca:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako odwołanie danych czy jako etykieta danych.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Odczyt/zapis String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Zwraca:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Odczyt/zapis String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).
**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Zwraca format tekstu wykresu. Tylko do odczytu [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Zwraca:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Zwraca wykres. Tylko do odczytu [IChart](../../com.aspose.slides/ichart).

**Zwraca:**
[IChart](../../com.aspose.slides/ichart)