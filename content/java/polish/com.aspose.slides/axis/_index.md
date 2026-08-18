---
title: Axis
second_title: Odwołanie API Aspose.Slides dla Javy
description: Zawiera obiekt reprezentujący oś wykresu.
type: docs
url: /pl/com.aspose.slides/axis/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Zawiera obiekt, który reprezentuje oś wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getChart()](#getChart--) | Zwraca nadrzędny chart. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Określa, czy value axis przecina category axis pomiędzy kategoriami. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Określa, czy value axis przecina category axis pomiędzy kategoriami. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Określa typ category axis. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Określa typ category axis. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Ustawia własność IAxis.CategoryAxisType na wartość, która jest automatycznie określana na podstawie danych osi. |
| [getCrossAt()](#getCrossAt--) | Określa punkt na axis, w którym perpendicular axis go przecina. |
| [setCrossAt(float value)](#setCrossAt-float-) | Określa punkt na axis, w którym perpendicular axis go przecina. |
| [getDisplayUnit()](#getDisplayUnit--) | Określa wartość skalowania jednostek wyświetlania dla value axis. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Określa wartość skalowania jednostek wyświetlania dla value axis. |
| [getActualMaxValue()](#getActualMaxValue--) | Określa rzeczywistą maksymalną wartość na axis. |
| [getActualMinValue()](#getActualMinValue--) | Określa rzeczywistą minimalną wartość na axis. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Określa rzeczywistą główną jednostkę axis. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Określa rzeczywistą pomocniczą jednostkę axis. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Określa rzeczywistą skalę głównej jednostki axis. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Określa rzeczywistą skalę pomocniczej jednostki axis. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. |
| [getMaxValue()](#getMaxValue--) | Określa maksymalną wartość na value axis. |
| [setMaxValue(double value)](#setMaxValue-double-) | Określa maksymalną wartość na value axis. |
| [getMinorUnit()](#getMinorUnit--) | Określa pomocnicze jednostki dla osi date lub value. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Określa pomocnicze jednostki dla osi date lub value. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Wskazuje, czy pomocnicza jednostka axis jest przypisywana automatycznie. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Wskazuje, czy pomocnicza jednostka axis jest przypisywana automatycznie. |
| [getMajorUnit()](#getMajorUnit--) | Określa główne jednostki dla osi date lub value. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Określa główne jednostki dla osi date lub value. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Wskazuje, czy główna jednostka axis jest przypisywana automatycznie. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Wskazuje, czy główna jednostka axis jest przypisywana automatycznie. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. |
| [getMinValue()](#getMinValue--) | Określa minimalną wartość na value axis. |
| [setMinValue(double value)](#setMinValue-double-) | Określa minimalną wartość na value axis. |
| [isLogarithmic()](#isLogarithmic--) | Określa, czy typ skali value axis jest logarytmiczny. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Określa, czy typ skali value axis jest logarytmiczny. |
| [getLogBase()](#getLogBase--) | Określa podstawę logarytmiczną. |
| [setLogBase(double value)](#setLogBase-double-) | Określa podstawę logarytmiczną. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. |
| [isVisible()](#isVisible--) | Określa, czy axis jest widoczny. |
| [setVisible(boolean value)](#setVisible-boolean-) | Określa, czy axis jest widoczny. |
| [getMajorTickMark()](#getMajorTickMark--) | Określa typ głównego znacznika podziałki dla określonego axis. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Określa typ głównego znacznika podziałki dla określonego axis. |
| [getMinorTickMark()](#getMinorTickMark--) | Określa typ pomocniczego znacznika podziałki dla określonego axis. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Określa typ pomocniczego znacznika podziałki dla określonego axis. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Określa pozycję etykiet znaczników podziałki na określonym axis. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Określa pozycję etykiet znaczników podziałki na określonym axis. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Określa skalę głównej jednostki dla osi date. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Określa skalę głównej jednostki dla osi date. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Określa skalę głównej jednostki dla osi date. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Określa skalę głównej jednostki dla osi date. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Określa najmniejszą jednostkę czasu reprezentowaną na osi date. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Określa najmniejszą jednostkę czasu reprezentowaną na osi date. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Określa format pomocniczych linii siatki na osi wykresu. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Określa format głównych linii siatki na osi wykresu. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Aby ukryć pomocniczą linię siatki, ustaw MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Aby ukryć główną linię siatki, ustaw MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. |
| [getFormat()](#getFormat--) | Określa format axis. |
| [getTextFormat()](#getTextFormat--) | Określa format tekstu. |
| [getTitle()](#getTitle--) | Pobiera tytuł axis. |
| [getCrossType()](#getCrossType--) | Określa CrossType na określonym axis, gdzie inny axis go przecina. |
| [setCrossType(int value)](#setCrossType-int-) | Określa CrossType na określonym axis, gdzie inny axis go przecina. |
| [getPosition()](#getPosition--) | Określa pozycję axis. |
| [setPosition(int value)](#setPosition-int-) | Określa pozycję axis. |
| [hasTitle()](#hasTitle--) | Określa, czy axis ma widoczny tytuł. |
| [setTitle(boolean value)](#setTitle-boolean-) | Określa, czy axis ma widoczny tytuł. |
| [getNumberFormat()](#getNumberFormat--) | Określa ciąg formatu dla etykiet Axis. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Określa ciąg formatu dla etykiet Axis. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Wskazuje, czy format jest powiązany z danymi źródłowymi. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Wskazuje, czy format jest powiązany z danymi źródłowymi. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Określa kąt obrotu etykiet znaczników podziałki. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Określa kąt obrotu etykiet znaczników podziałki. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Określa, ile etykiet znaczników pomijać między rysowanymi etykietami. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Określa, ile etykiet znaczników pomijać między rysowanymi etykietami. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Określa wartość automatycznego odstępu etykiet znaczników. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Określa wartość automatycznego odstępu etykiet znaczników. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Określa, ile znaczników podziałki pominąć przed narysowaniem kolejnego. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Określa, ile znaczników podziałki pominąć przed narysowaniem kolejnego. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Określa wartość automatycznego odstępu znaczników podziałki. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Określa wartość automatycznego odstępu znaczników podziałki. |
| [getLabelOffset()](#getLabelOffset--) | Określa odległość etykiet od axis. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Określa odległość etykiet od axis. |
| [getAggregationType()](#getAggregationType--) | Określa typ agregacji axis kategorii (grupowanie). |
| [setAggregationType(int value)](#setAggregationType-int-) | Określa typ agregacji axis kategorii (grupowanie). |
| [getBinWidth()](#getBinWidth--) | Określa szerokość kosza, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Określa szerokość kosza, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Określa liczbę koszy, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Określa liczbę koszy, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Określa, czy zastosowano kosz przepełnienia. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Określa, czy zastosowano kosz przepełnienia. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Określa automatyczną wartość kosza przepełnienia. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Określa automatyczną wartość kosza przepełnienia. |
| [getOverflowBin()](#getOverflowBin--) | Określa niestandardową wartość kosza przepełnienia. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Określa niestandardową wartość kosza przepełnienia. |
| [isUnderflowBin()](#isUnderflowBin--) | Określa, czy zastosowano kosz niedomiaru. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Określa, czy zastosowano kosz niedomiaru. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Określa automatyczną wartość kosza niedomiaru. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Określa automatyczną wartość kosza niedomiaru. |
| [getUnderflowBin()](#getUnderflowBin--) | Określa niestandardową wartość kosza niedomiaru. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Określa niestandardową wartość kosza niedomiaru. |
| [getSlide()](#getSlide--) | Zwraca nadrzędny slide formatu FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca nadrzędną prezentację formatu FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```


Zwraca nadrzędny chart. Tylko do odczytu [IChart](../../com.aspose.slides/ichart).

**Zwraca:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```


Określa, czy value axis przecina category axis pomiędzy kategoriami. Ta właściwość ma zastosowanie tylko do osi kategorii i nie dotyczy wykresów 3-D. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```


Określa, czy value axis przecina category axis pomiędzy kategoriami. Ta właściwość ma zastosowanie tylko do osi kategorii i nie dotyczy wykresów 3-D. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```


Określa typ category axis. Odczyt/zapis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Zwraca:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```


Określa typ category axis. Odczyt/zapis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```


Ustawia własność IAxis.CategoryAxisType na wartość, która jest automatycznie określana na podstawie danych osi.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```


Określa punkt na axis, w którym perpendicular axis go przecina. Odczyt/zapis float.

**Zwraca:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```


Określa punkt na axis, w którym perpendicular axis go przecina. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```


Określa wartość skalowania jednostek wyświetlania dla value axis. Odczyt/zapis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Zwraca:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```


Określa wartość skalowania jednostek wyświetlania dla value axis. Odczyt/zapis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```


Określa rzeczywistą maksymalną wartość na axis. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```


Określa rzeczywistą minimalną wartość na axis. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```


Określa rzeczywistą główną jednostkę axis. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```


Określa rzeczywistą pomocniczą jednostkę axis. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```


Określa rzeczywistą skalę głównej jednostki axis. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```


Określa rzeczywistą skalę pomocniczej jednostki axis. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```


Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```


Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```


Określa maksymalną wartość na value axis. Odczyt/zapis double.

**Zwraca:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```


Określa maksymalną wartość na value axis. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```


Określa pomocnicze jednostki dla osi date lub value. Odczyt/zapis double.

**Zwraca:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```


Określa pomocnicze jednostki dla osi date lub value. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Wskazuje, czy jednostka pomocnicza osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Wskazuje, czy jednostka pomocnicza osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Reprezentuje jednostki główne dla osi daty lub wartości. Odczyt/zapis double.

**Zwraca:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Reprezentuje jednostki główne dla osi daty lub wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Reprezentuje minimalną wartość na osi wartości. Odczyt/zapis double.

**Zwraca:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Reprezentuje minimalną wartość na osi wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Reprezentuje, czy typ skali osi wartości jest logarytmiczny. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Reprezentuje, czy typ skali osi wartości jest logarytmiczny. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis double.

**Zwraca:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Reprezentuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Reprezentuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Reprezentuje, czy oś jest widoczna. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Reprezentuje, czy oś jest widoczna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Reprezentuje typ głównego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Zwraca:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Reprezentuje typ głównego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Reprezentuje typ pobocznego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Zwraca:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Reprezentuje typ pobocznego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Reprezentuje pozycję etykiet znaczników podziałki na określonej osi. Odczyt/zapis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Zwraca:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Reprezentuje pozycję etykiet znaczników podziałki na określonej osi. Odczyt/zapis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Reprezentuje format drobnych linii siatki na osi wykresu. Tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Reprezentuje format głównych linii siatki na osi wykresu. Tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Aby ukryć drobną linię siatki, ustaw MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Aby ukryć główną linię siatki, ustaw MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Reprezentuje format osi. Tylko do odczytu [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Zwraca:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Reprezentuje format tekstu. Tylko do odczytu [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Zwraca:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Pobiera tytuł osi. Tylko do odczytu [IChartTitle](../../com.aspose.slides/icharttitle).

**Zwraca:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Reprezentuje typ przecięcia na określonej osi, gdzie przecina się druga oś. Odczyt/zapis [CrossesType](../../com.aspose.slides/crossestype).

**Zwraca:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Reprezentuje typ przecięcia na określonej osi, gdzie przecina się druga oś. Odczyt/zapis [CrossesType](../../com.aspose.slides/crossestype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Reprezentuje pozycję osi. Odczyt/zapis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Reprezentuje pozycję osi. Odczyt/zapis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Określa, czy oś ma widoczny tytuł. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Określa, czy oś ma widoczny tytuł. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Reprezentuje ciąg formatu dla etykiet osi. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Reprezentuje ciąg formatu dla etykiet osi. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Wskazuje, czy format jest powiązany z danymi źródłowymi. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Wskazuje, czy format jest powiązany z danymi źródłowymi. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Reprezentuje kąt obrotu etykiet znaczników podziałki. Odczyt/zapis float.

**Zwraca:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Reprezentuje kąt obrotu etykiet znaczników podziałki. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Określa, ile etykiet znaczników podziałki pominąć pomiędzy rysowanymi etykietami. Stosowane dla osi kategorii lub serii. Odczyt/zapis long.

**Zwraca:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Określa, ile etykiet znaczników podziałki pominąć pomiędzy rysowanymi etykietami. Stosowane dla osi kategorii lub serii. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Określa automatyczną wartość odstępu etykiet znaczników podziałki. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Określa automatyczną wartość odstępu etykiet znaczników podziałki. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Określa, ile znaczników podziałki pominąć przed narysowaniem kolejnego. Stosowane dla osi kategorii lub serii. Odczyt/zapis int.

**Zwraca:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Określa, ile znaczników podziałki pominąć przed narysowaniem kolejnego. Stosowane dla osi kategorii lub serii. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Określa automatyczną wartość odstępu znaczników podziałki. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Określa automatyczną wartość odstępu znaczników podziałki. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Określa odległość etykiet od osi. Stosowane dla osi kategorii lub daty. Wartość musi wynosić od 0 % do 1000 %. Odczyt/zapis int.

**Zwraca:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Określa odległość etykiet od osi. Stosowane dla osi kategorii lub daty. Wartość musi wynosić od 0 % do 1000 %. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Zwraca:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Określa szerokość przedziału, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Zwraca:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Określa szerokość przedziału, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Określa liczbę przedziałów, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Zwraca:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Określa liczbę przedziałów, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Określa, czy zastosowano przedział przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość przedziału przepełnienia.

**Zwraca:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Określa, czy zastosowano przedział przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość przedziału przepełnienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Określa automatyczną wartość przedziału przepełnienia. Jeśli false: użyj właściwości OverflowBin.

**Zwraca:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Określa automatyczną wartość przedziału przepełnienia. Jeśli false: użyj właściwości OverflowBin.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Określa niestandardową wartość przedziału przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin ma wartość true.

**Zwraca:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Określa niestandardową wartość przedziału przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin ma wartość true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Określa, czy zastosowano przedział niedomiaru. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość przedziału niedomiaru.

**Zwraca:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Określa, czy zastosowano przedział niedomiaru. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość przedziału niedomiaru.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Określa automatyczną wartość przedziału niedomiaru. Jeśli false: użyj właściwości UnderflowBin.

**Zwraca:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Określa automatyczną wartość przedziału niedomiaru. Jeśli false: użyj właściwości UnderflowBin.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Określa niestandardową wartość przedziału niedomiaru. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin ma wartość true.

**Zwraca:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Określa niestandardową wartość przedziału niedomiaru. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin ma wartość true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny FillFormat. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną FillFormat. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)