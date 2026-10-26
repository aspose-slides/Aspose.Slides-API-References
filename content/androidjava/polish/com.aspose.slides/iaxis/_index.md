---
title: IAxis
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Enkapsuluje obiekt, który reprezentuje oś wykresu.
type: docs
url: /pl/com.aspose.slides/iaxis/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Enkapsuluje obiekt reprezentujący oś wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami. |
| [getCrossAt()](#getCrossAt--) | Określa punkt na osi, w którym przecina ją oś prostopadła. |
| [setCrossAt(float value)](#setCrossAt-float-) | Określa punkt na osi, w którym przecina ją oś prostopadła. |
| [getDisplayUnit()](#getDisplayUnit--) | Określa wartość skalowania jednostek wyświetlania dla osi wartości. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Określa wartość skalowania jednostek wyświetlania dla osi wartości. |
| [getActualMaxValue()](#getActualMaxValue--) | Określa rzeczywistą maksymalną wartość na osi. |
| [getActualMinValue()](#getActualMinValue--) | Określa rzeczywistą minimalną wartość na osi. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Określa rzeczywistą jednostkę główną osi. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Określa rzeczywistą jednostkę podrzędną osi. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Określa rzeczywistą skalę jednostki głównej na osi. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Określa rzeczywistą skalę jednostki podrzędnej na osi. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. |
| [getMaxValue()](#getMaxValue--) | Określa maksymalną wartość na osi wartości. |
| [setMaxValue(double value)](#setMaxValue-double-) | Określa maksymalną wartość na osi wartości. |
| [getMinorUnit()](#getMinorUnit--) | Określa jednostki mniejsze dla osi daty lub wartości. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Określa jednostki mniejsze dla osi daty lub wartości. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie. |
| [getMajorUnit()](#getMajorUnit--) | Określa jednostki główne dla osi daty lub wartości. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Określa jednostki główne dla osi daty lub wartości. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. |
| [getMinValue()](#getMinValue--) | Określa minimalną wartość na osi wartości. |
| [setMinValue(double value)](#setMinValue-double-) | Określa minimalną wartość na osi wartości. |
| [isLogarithmic()](#isLogarithmic--) | Określa, czy typ skali osi wartości jest logarytmiczny. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Określa, czy typ skali osi wartości jest logarytmiczny. |
| [getLogBase()](#getLogBase--) | Określa podstawę logarytmu. |
| [setLogBase(double value)](#setLogBase-double-) | Określa podstawę logarytmu. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. |
| [isVisible()](#isVisible--) | Określa, czy oś jest widoczna. |
| [setVisible(boolean value)](#setVisible-boolean-) | Określa, czy oś jest widoczna. |
| [getMajorTickMark()](#getMajorTickMark--) | Określa typ głównego znacznika kreski dla określonej osi. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Określa typ głównego znacznika kreski dla określonej osi. |
| [getMinorTickMark()](#getMinorTickMark--) | Określa typ podrzędnego znacznika kreski dla określonej osi. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Określa typ podrzędnego znacznika kreski dla określonej osi. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Określa pozycję etykiet znaczników kreski na określonej osi. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Określa pozycję etykiet znaczników kreski na określonej osi. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Określa skalę jednostki głównej na osi daty. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Określa skalę jednostki głównej na osi daty. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Określa skalę jednostki głównej na osi daty. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Określa skalę jednostki głównej na osi daty. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Określa format linii siatki podrzędnej na osi wykresu. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Określa format linii siatki głównej na osi wykresu. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Określa, czy wyświetlone są linie siatki podrzędnej. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Określa, czy wyświetlone są linie siatki głównej. |
| [getFormat()](#getFormat--) | Określa format osi. |
| [getTitle()](#getTitle--) | Pobiera tytuł osi. |
| [getCrossType()](#getCrossType--) | Określa CrossType na określonej osi, w której druga oś ją przecina. |
| [setCrossType(int value)](#setCrossType-int-) | Określa CrossType na określonej osi, w której druga oś ją przecina. |
| [getPosition()](#getPosition--) | Określa pozycję osi. |
| [setPosition(int value)](#setPosition-int-) | Określa pozycję osi. |
| [hasTitle()](#hasTitle--) | Określa, czy oś ma widoczny tytuł. |
| [setTitle(boolean value)](#setTitle-boolean-) | Określa, czy oś ma widoczny tytuł. |
| [getNumberFormat()](#getNumberFormat--) | Określa ciąg formatu dla etykiet osi. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Określa ciąg formatu dla etykiet osi. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Wskazuje, czy format jest powiązany z danymi źródłowymi. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Wskazuje, czy format jest powiązany z danymi źródłowymi. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Określa kąt obrotu etykiet kreski. Odczyt/zapis float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Określa kąt obrotu etykiet kreski. Odczyt/zapis float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Określa, ile etykiet kreski pominąć pomiędzy wyświetlanymi etykietami. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Określa, ile etykiet kreski pominąć pomiędzy wyświetlanymi etykietami. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Określa automatyczną wartość odstępu etykiet kreski. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Określa automatyczną wartość odstępu etykiet kreski. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Określa, ile znaczników kreski pominąć przed narysowaniem kolejnego. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Określa, ile znaczników kreski pominąć przed narysowaniem kolejnego. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Określa automatyczną wartość odstępu znaczników kreski. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Określa automatyczną wartość odstępu znaczników kreski. |
| [getLabelOffset()](#getLabelOffset--) | Określa odległość etykiet od osi. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Określa odległość etykiet od osi. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Określa typ osi kategorii. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Określa typ osi kategorii. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Ustawia właściwość IAxis.CategoryAxisType na wartość automatycznie określoną na podstawie danych osi. |
| [getAggregationType()](#getAggregationType--) | Określa typ agregacji osi kategorii (grupowanie w koszyki). |
| [setAggregationType(int value)](#setAggregationType-int-) | Określa typ agregacji osi kategorii (grupowanie w koszyki). |
| [getBinWidth()](#getBinWidth--) | Określa szerokość koszyka, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Określa szerokość koszyka, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Określa liczbę koszyków, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Określa liczbę koszyków, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Określa, czy zastosowano koszyk przepełnienia. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Określa, czy zastosowano koszyk przepełnienia. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Określa automatyczną wartość koszyka przepełnienia. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Określa automatyczną wartość koszyka przepełnienia. |
| [getOverflowBin()](#getOverflowBin--) | Określa niestandardową wartość koszyka przepełnienia. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Określa niestandardową wartość koszyka przepełnienia. |
| [isUnderflowBin()](#isUnderflowBin--) | Określa, czy zastosowano koszyk podprzepływu. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Określa, czy zastosowano koszyk podprzepływu. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Określa automatyczną wartość koszyka podprzepływu. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Określa automatyczną wartość koszyka podprzepływu. |
| [getUnderflowBin()](#getUnderflowBin--) | Określa niestandardową wartość koszyka podprzepływu. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Określa niestandardową wartość koszyka podprzepływu. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Ta właściwość ma zastosowanie wyłącznie do osi kategorii i nie ma zastosowania do wykresów 3-D. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Ta właściwość ma zastosowanie wyłącznie do osi kategorii i nie ma zastosowania do wykresów 3-D. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Określa punkt na osi, w którym przecina ją oś prostopadła. Odczyt/zapis float.

**Zwraca:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Określa punkt na osi, w którym przecina ją oś prostopadła. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Określa wartość skalowania jednostek wyświetlania dla osi wartości. Odczyt/zapis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Zwraca:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Określa wartość skalowania jednostek wyświetlania dla osi wartości. Odczyt/zapis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Określa rzeczywistą maksymalną wartość na osi. Przed wywołaniem należy wykonać metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Określa rzeczywistą minimalną wartość na osi. Przed wywołaniem należy wykonać metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Określa rzeczywistą jednostkę główną na osi. Przed wywołaniem należy wykonać metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Określa rzeczywistą jednostkę podrzędną na osi. Przed wywołaniem należy wykonać metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Określa rzeczywistą skalę jednostki głównej na osi. Przed wywołaniem należy wykonać metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość.

**Zwraca:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Określa rzeczywistą skalę jednostki podrzędnej na osi. Przed wywołaniem należy wykonać metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość.

**Zwraca:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Określa maksymalną wartość na osi wartości. Odczyt/zapis double.

**Zwraca:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Określa maksymalną wartość na osi wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Określa jednostki mniejsze dla osi daty lub wartości. Odczyt/zapis double.

**Zwraca:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Określa jednostki mniejsze dla osi daty lub wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Określa jednostki główne dla osi daty lub wartości. Odczyt/zapis double.

**Zwraca:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Określa jednostki główne dla osi daty lub wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Określa minimalną wartość na osi wartości. Odczyt/zapis double.

**Zwraca:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Określa minimalną wartość na osi wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Określa, czy typ skali osi wartości jest logarytmiczny. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Określa, czy typ skali osi wartości jest logarytmiczny. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Określa podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis double.

**Zwraca:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Określa podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Określa, czy oś jest widoczna. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Określa, czy oś jest widoczna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Określa typ głównego znacznika kreski dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Zwraca:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Określa typ głównego znacznika kreski dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Określa typ podrzędnego znacznika kreski dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Zwraca:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Określa typ podrzędnego znacznika kreski dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Określa pozycję etykiet znaczników kreski na określonej osi. Odczyt/zapis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Zwraca:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Określa pozycję etykiet znaczników kreski na określonej osi. Odczyt/zapis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Określa skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Określa skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Określa skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Określa skalę jednostki głównej dla osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Określa format linii siatki podrzędnej na osi wykresu. Tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Określa format linii siatki głównej na osi wykresu. Tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Określa, czy wyświetlone są linie siatki podrzędnej. Tylko do odczytu boolean.

**Zwraca:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Określa, czy wyświetlone są linie siatki głównej. Tylko do odczytu boolean.

**Zwraca:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Określa format osi. Tylko do odczytu [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Zwraca:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Pobiera tytuł osi. Tylko do odczytu [IChartTitle](../../com.aspose.slides/icharttitle).

**Zwraca:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Określa CrossType na określonej osi, w której druga oś ją przecina. Odczyt/zapis [CrossesType](../../com.aspose.slides/crossestype).

**Zwraca:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Określa CrossType na określonej osi, w której druga oś ją przecina. Odczyt/zapis [CrossesType](../../com.aspose.slides/crossestype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Określa pozycję osi. Odczyt/zapis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Zwraca:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Określa pozycję osi. Odczyt/zapis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Określa, czy oś ma widoczny tytuł. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Określa, czy oś ma widoczny tytuł. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Określa ciąg formatu dla etykiet osi. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Określa ciąg formatu dla etykiet osi. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Wskazuje, czy format jest powiązany z danymi źródłowymi. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Wskazuje, czy format jest powiązany z danymi źródłowymi. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Określa kąt obrotu etykiet kreski. Odczyt/zapis float.

**Zwraca:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Określa kąt obrotu etykiet kreski. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Określa, ile etykiet kreski pominąć pomiędzy wyświetlanymi etykietami. Odczyt/zapis long.

**Zwraca:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Określa, ile etykiet kreski pominąć pomiędzy wyświetlanymi etykietami. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Określa automatyczną wartość odstępu etykiet kreski. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Określa automatyczną wartość odstępu etykiet kreski. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Określa, ile znaczników kreski pominąć przed narysowaniem kolejnego. Stosowane do osi kategorii lub serii. Odczyt/zapis int.

**Zwraca:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Określa, ile znaczników kreski pominąć przed narysowaniem kolejnego. Stosowane do osi kategorii lub serii. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Określa automatyczną wartość odstępu znaczników kreski. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Określa automatyczną wartość odstępu znaczników kreski. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi wynosić od 0% do 1000%. Odczyt/zapis int.

**Zwraca:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi wynosić od 0% do 1000%. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Określa typ osi kategorii. Odczyt/zapis [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Zwraca:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Określa typ osi kategorii. Odczyt/zapis [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Ustawia właściwość IAxis.CategoryAxisType na wartość automatycznie określoną na podstawie danych osi.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Określa typ agregacji osi kategorii (grupowanie w koszyki). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Zwraca:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Określa typ agregacji osi kategorii (grupowanie w koszyki). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Określa szerokość koszyka, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByBinWidth. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Zwraca:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Określa szerokość koszyka, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByBinWidth. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Określa liczbę koszyków, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Zwraca:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Określa liczbę koszyków, gdy wartość właściwości AggregationType ustawiona jest na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Określa, czy zastosowano koszyk przepełnienia. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Zwraca:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Określa, czy zastosowano koszyk przepełnienia. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Określa automatyczną wartość koszyka przepełnienia. Jeśli false: użyj właściwości OverflowBin.

**Zwraca:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Określa automatyczną wartość koszyka przepełnienia. Jeśli false: użyj właściwości OverflowBin.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Określa niestandardową wartość koszyka przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i IsOverflowBin jest true.

**Zwraca:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Określa niestandardową wartość koszyka przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i IsOverflowBin jest true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Określa, czy zastosowano koszyk podprzepływu. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Zwraca:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Określa, czy zastosowano koszyk podprzepływu. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Określa automatyczną wartość koszyka podprzepływu. Jeśli false: użyj właściwości UnderflowBin.

**Zwraca:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
`````
public abstract void setAutomaticUnderflowBin(boolean value)
```

Określa automatyczną wartość koszyka podprzepływu. Jeśli false: użyj właściwości UnderflowBin.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Określa niestandardową wartość koszyka podprzepływu. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i IsUnderflowBin jest true.

**Zwraca:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Określa niestandardową wartość koszyka podprzepływu. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i IsUnderflowBin jest true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |