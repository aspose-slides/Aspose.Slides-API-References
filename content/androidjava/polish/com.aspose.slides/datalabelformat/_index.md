---
title: DataLabelFormat
second_title: Aspose.Slides dla Androida poprzez referencję API Javy
description: Reprezentuje opcje formatowania dla DataLabel.
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
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Odczyt/zapis boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Odczyt/zapis boolean. |
| [getNumberFormat()](#getNumberFormat--) | Reprezentuje ciąg formatowania dla obiektu DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Reprezentuje ciąg formatowania dla obiektu DataLabels. |
| [getFormat()](#getFormat--) | Reprezentuje format etykiety danych. |
| [getPosition()](#getPosition--) | Reprezentuje pozycję etykiety danych. |
| [setPosition(int value)](#setPosition-int-) | Reprezentuje pozycję etykiety danych. |
| [getShowLegendKey()](#getShowLegendKey--) | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. |
| [getShowValue()](#getShowValue--) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [getShowCategoryName()](#getShowCategoryName--) | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. |
| [getShowSeriesName()](#getShowSeriesName--) | Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. |
| [getShowPercentage()](#getShowPercentage--) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako wywołanie danych czy jako etykieta danych. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako wywołanie danych czy jako etykieta danych. |
| [getSeparator()](#getSeparator--) | Ustawia lub zwraca Variant reprezentujący separator używany w etykietach danych na wykresie. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Ustawia lub zwraca Variant reprezentujący separator używany w etykietach danych na wykresie. |
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

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości IsNumberFormatLinkedToSource dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości IsNumberFormatLinkedToSource dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" powoduje, że wszystkie DataLabels.get_Item(i).isNumberFormatLinkedToSource() są równe wartości).

**Zwraca:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości IsNumberFormatLinkedToSource dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości IsNumberFormatLinkedToSource dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" powoduje, że wszystkie DataLabels.get_Item(i).isNumberFormatLinkedToSource() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Reprezentuje ciąg formatowania dla obiektu DataLabels. Odczyt/zapis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji DataLabelCollection. Gdy właściwość ta zostaje ustawiona na określoną wartość, wartość ta jest również ustawiana w właściwości NumberFormat dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" powoduje, że wszystkie DataLabels.get_Item(i).getNumberFormat() są równe wartości).

**Zwraca:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Reprezentuje ciąg formatowania dla obiektu DataLabels. Odczyt/zapis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji DataLabelCollection. Gdy właściwość ta zostaje ustawiona na określoną wartość, wartość ta jest również ustawiana w właściwości NumberFormat dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" powoduje, że wszystkie DataLabels.get_Item(i).getNumberFormat() są równe wartości).

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

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość reprezentuje domyślny format dla nowych etykiet danych w kolekcji DataLabelCollection.

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Reprezentuje pozycję etykiety danych. Odczyt/zapis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection. Reprezentuje pozycję obiektów DataLabel. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości Position dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" powoduje, że wszystkie DataLabels.get_Item(i).getPosition() są równe wartości).

**Zwraca:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Reprezentuje pozycję etykiety danych. Odczyt/zapis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Position dla nowych etykiet danych w kolekcji DataLabelCollection. Reprezentuje pozycję obiektów DataLabel. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości Position dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" powoduje, że wszystkie DataLabels.get_Item(i).getPosition() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. Prawda, jeśli klucz legendy etykiety danych jest widoczny. Fałsz, aby ukryć. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLegendKey dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLegendKey dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLegendKey() są równe wartości).

**Zwraca:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Reprezentuje zachowanie wyświetlania klucza legendy etykiety danych określonego wykresu. Prawda, jeśli klucz legendy etykiety danych jest widoczny. Fałsz, aby ukryć. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLegendKey dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLegendKey dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLegendKey() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowValue dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowValue() są równe wartości).

**Zwraca:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowValue dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowValue dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowValue() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. Prawda wyświetla nazwę kategorii. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowCategoryName dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowCategoryName() są równe wartości).

**Zwraca:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. Prawda wyświetla nazwę kategorii. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowCategoryName dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowCategoryName() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. Prawda wyświetla nazwę serii. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowSeriesName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowSeriesName dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowSeriesName() są równe wartości).

**Zwraca:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Zwraca lub ustawia wartość Boolean określającą zachowanie wyświetlania nazwy serii dla etykiet danych na wykresie. Prawda wyświetla nazwę serii. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowSeriesName dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowSeriesName dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowSeriesName() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowPercentage dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowPercentage dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowPercentage() są równe wartości).

**Zwraca:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości procentowej etykiety danych określonego wykresu. Prawda wyświetla wartość procentową. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowPercentage dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowPercentage dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowPercentage() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. Prawda wyświetla wartość rozmiaru bąbelka. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowBubbleSize dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowBubbleSize dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowBubbleSize() są równe wartości).

**Zwraca:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości rozmiaru bąbelka etykiety danych określonego wykresu. Prawda wyświetla wartość rozmiaru bąbelka. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowBubbleSize dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowBubbleSize dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowBubbleSize() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. Prawda wyświetla linie prowadzące. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLeaderLines dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLeaderLines dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLeaderLines() są równe wartości).

**Zwraca:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Reprezentuje zachowanie wyświetlania linii prowadzących etykiety danych określonego wykresu. Prawda wyświetla linie prowadzące. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLeaderLines dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLeaderLines dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLeaderLines() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. Prawda wyświetla wartość komórki. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelValueFromCell dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLabelValueFromCell dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLabelValueFromCell() są równe wartości).

**Zwraca:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Reprezentuje zachowanie wyświetlania wartości komórki etykiety danych określonego wykresu. Prawda wyświetla wartość komórki. Fałsz ukrywa. Odczyt/zapis boolean.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelValueFromCell dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLabelValueFromCell dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLabelValueFromCell() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako wywołanie danych czy jako etykieta danych.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelAsDataCallout dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLabelAsDataCallout dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLabelAsDataCallout() są równe wartości).

**Zwraca:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Określa, czy etykieta danych określonego wykresu będzie wyświetlana jako wywołanie danych czy jako etykieta danych.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelAsDataCallout dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości ShowLabelAsDataCallout dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" powoduje, że wszystkie DataLabels.get_Item(i).getShowLabelAsDataCallout() są równe wartości).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Ustawia lub zwraca Variant reprezentujący separator używany w etykietach danych na wykresie. Odczyt/zapis String.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Separator dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości Separator dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" powoduje, że wszystkie DataLabels.get_Item(i).getSeparator() są równe wartości).

**Zwraca:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Ustawia lub zwraca Variant reprezentujący separator używany w etykietach danych na wykresie. Odczyt/zapis String.

--------------------

Jeśli rodzicem tego obiektu DataLabelFormat jest kolekcja DataLabelCollection zawierająca etykiety danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Separator dla nowych etykiet danych w kolekcji DataLabelCollection. Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej samej wartości w właściwości Separator dla wszystkich etykiet danych w kolekcji DataLabelCollection (np. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" powoduje, że wszystkie DataLabels.get_Item(i).getSeparator() są równe wartości).

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