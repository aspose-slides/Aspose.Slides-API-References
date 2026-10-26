---
title: IAxis
second_title: Odwołanie API Aspose.Slides dla Javy
description: Enkapsuluje obiekt, który reprezentuje oś wykresu.
type: docs
url: /pl/com.aspose.slides/iaxis/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Enkapsuluje obiekt, który reprezentuje oś wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. |
| [getCrossAt()](#getCrossAt--) | Reprezentuje punkt na osi, w którym prostopadła oś ją przecina. |
| [setCrossAt(float value)](#setCrossAt-float-) | Reprezentuje punkt na osi, w którym prostopadła oś ją przecina. |
| [getDisplayUnit()](#getDisplayUnit--) | Określa wartość skalowania jednostek wyświetlania dla osi wartości. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Określa wartość skalowania jednostek wyświetlania dla osi wartości. |
| [getActualMaxValue()](#getActualMaxValue--) | Określa rzeczywistą maksymalną wartość na osi. |
| [getActualMinValue()](#getActualMinValue--) | Określa rzeczywistą minimalną wartość na osi. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Określa rzeczywistą główną jednostkę osi. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Określa rzeczywistą poboczną jednostkę osi. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Określa rzeczywistą skalę głównej jednostki osi. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Określa rzeczywistą skalę pobocznej jednostki osi. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. |
| [getMaxValue()](#getMaxValue--) | Reprezentuje maksymalną wartość na osi wartości. |
| [setMaxValue(double value)](#setMaxValue-double-) | Reprezentuje maksymalną wartość na osi wartości. |
| [getMinorUnit()](#getMinorUnit--) | Reprezentuje jednostki poboczne dla osi daty lub wartości. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Reprezentuje jednostki poboczne dla osi daty lub wartości. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Wskazuje, czy poboczna jednostka osi jest przypisywana automatycznie. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Wskazuje, czy poboczna jednostka osi jest przypisywana automatycznie. |
| [getMajorUnit()](#getMajorUnit--) | Reprezentuje jednostki główne dla osi daty lub wartości. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Reprezentuje jednostki główne dla osi daty lub wartości. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Wskazuje, czy główna jednostka osi jest przypisywana automatycznie. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Wskazuje, czy główna jednostka osi jest przypisywana automatycznie. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. |
| [getMinValue()](#getMinValue--) | Reprezentuje minimalną wartość na osi wartości. |
| [setMinValue(double value)](#setMinValue-double-) | Reprezentuje minimalną wartość na osi wartości. |
| [isLogarithmic()](#isLogarithmic--) | Reprezentuje, czy typ skali osi wartości jest logarytmiczny. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Reprezentuje, czy typ skali osi wartości jest logarytmiczny. |
| [getLogBase()](#getLogBase--) | Reprezentuje podstawę logarytmu. |
| [setLogBase(double value)](#setLogBase-double-) | Reprezentuje podstawę logarytmu. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Reprezentuje, czy MS PowerPoint rysuje punkty danych od końca do początku. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Reprezentuje, czy MS PowerPoint rysuje punkty danych od końca do początku. |
| [isVisible()](#isVisible--) | Reprezentuje, czy oś jest widoczna. |
| [setVisible(boolean value)](#setVisible-boolean-) | Reprezentuje, czy oś jest widoczna. |
| [getMajorTickMark()](#getMajorTickMark--) | Reprezentuje typ głównego znacznika podziałki dla określonej osi. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Reprezentuje typ głównego znacznika podziałki dla określonej osi. |
| [getMinorTickMark()](#getMinorTickMark--) | Reprezentuje typ pobocznego znacznika podziałki dla określonej osi. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Reprezentuje typ pobocznego znacznika podziałki dla określonej osi. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Reprezentuje położenie etykiet znaczników podziałek na określonej osi. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Reprezentuje położenie etykiet znaczników podziałek na określonej osi. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Reprezentuje skalę jednostki głównej dla osi daty. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Reprezentuje skalę jednostki głównej dla osi daty. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Reprezentuje skalę jednostki głównej dla osi daty. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Reprezentuje skalę jednostki głównej dla osi daty. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Określa najmniejszą jednostkę czasu, która jest reprezentowana na osi daty. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Określa najmniejszą jednostkę czasu, która jest reprezentowana na osi daty. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Reprezentuje format linii siatki pobocznej na osi wykresu. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Reprezentuje format linii siatki głównej na osi wykresu. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Reprezentuje, czy linie siatki pobocznej są wyświetlane. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Reprezentuje, czy linie siatki głównej są wyświetlane. |
| [getFormat()](#getFormat--) | Reprezentuje format osi. |
| [getTitle()](#getTitle--) | Pobiera tytuł osi. |
| [getCrossType()](#getCrossType--) | Reprezentuje CrossType na określonej osi, gdzie przecina ją druga oś. |
| [setCrossType(int value)](#setCrossType-int-) | Reprezentuje CrossType na określonej osi, gdzie przecina ją druga oś. |
| [getPosition()](#getPosition--) | Reprezentuje pozycję osi. |
| [setPosition(int value)](#setPosition-int-) | Reprezentuje pozycję osi. |
| [hasTitle()](#hasTitle--) | Określa, czy oś ma widoczny tytuł. |
| [setTitle(boolean value)](#setTitle-boolean-) | Określa, czy oś ma widoczny tytuł. |
| [getNumberFormat()](#getNumberFormat--) | Reprezentuje ciąg formatu dla etykiet osi. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Reprezentuje ciąg formatu dla etykiet osi. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Wskazuje, czy format jest powiązany z danymi źródłowymi. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Wskazuje, czy format jest powiązany z danymi źródłowymi. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Reprezentuje kąt obrotu etykiet podziałek Odczyt/zapis float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Reprezentuje kąt obrotu etykiet podziałek Odczyt/zapis float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Określa, ile etykiet podziałek pomijać między etykietą, która jest rysowana. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Określa, ile etykiet podziałek pomijać między etykietą, która jest rysowana. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Określa automatyczną wartość odstępu etykiet podziałek. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Określa automatyczną wartość odstępu etykiet podziałek. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Określa, ile znaczników podziałki należy pominąć przed narysowaniem kolejnego. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Określa, ile znaczników podziałki należy pominąć przed narysowaniem kolejnego. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Określa automatyczną wartość odstępu znaczników podziałek. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Określa automatyczną wartość odstępu znaczników podziałek. |
| [getLabelOffset()](#getLabelOffset--) | Określa odległość etykiet od osi. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Określa odległość etykiet od osi. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Określa typ osi kategorii. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Określa typ osi kategorii. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Ustawia właściwość IAxis.CategoryAxisType na wartość automatycznie określoną na podstawie danych osi. |
| [getAggregationType()](#getAggregationType--) | Reprezentuje typ agregacji osi kategorii (grupowanie). |
| [setAggregationType(int value)](#setAggregationType-int-) | Reprezentuje typ agregacji osi kategorii (grupowanie). |
| [getBinWidth()](#getBinWidth--) | Określa szerokość przedziału, gdy właściwość AggregationType ma wartość AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Określa szerokość przedziału, gdy właściwość AggregationType ma wartość AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Określa liczbę przedziałów, gdy właściwość AggregationType ma wartość AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Określa liczbę przedziałów, gdy właściwość AggregationType ma wartość AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Określa, czy zastosowano przedział przepełnienia. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Określa, czy zastosowano przedział przepełnienia. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Określa automatyczną wartość przedziału przepełnienia. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Określa automatyczną wartość przedziału przepełnienia. |
| [getOverflowBin()](#getOverflowBin--) | Określa niestandardową wartość przedziału przepełnienia. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Określa niestandardową wartość przedziału przepełnienia. |
| [isUnderflowBin()](#isUnderflowBin--) | Określa, czy zastosowano przedział niedomiaru. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Określa, czy zastosowano przedział niedomiaru. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Określa automatyczną wartość przedziału niedomiaru. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Określa automatyczną wartość przedziału niedomiaru. |
| [getUnderflowBin()](#getUnderflowBin--) | Określa niestandardową wartość przedziału niedomiaru. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Określa niestandardową wartość przedziału niedomiaru. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Właściwość ma zastosowanie tylko do osi kategorii i nie ma zastosowania do wykresów 3-D. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Właściwość ma zastosowanie tylko do osi kategorii i nie ma zastosowania do wykresów 3-D. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Reprezentuje punkt na osi, w którym prostopadła oś ją przecina. Odczyt/zapis float.

**Zwraca:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Reprezentuje punkt na osi, w którym prostopadła oś ją przecina. Odczyt/zapis float.

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

Określa rzeczywistą maksymalną wartość na osi. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Określa rzeczywistą minimalną wartość na osi. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Określa rzeczywistą główną jednostkę osi. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Określa rzeczywistą poboczną jednostkę osi. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Określa rzeczywistą skalę głównej jednostki osi. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

**Zwraca:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Określa rzeczywistą skalę pobocznej jednostki osi. Wywołaj metodę IChart.ValidateChartLayout() wcześniej, aby uzyskać rzeczywistą wartość.

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

Reprezentuje maksymalną wartość na osi wartości. Odczyt/zapis double.

**Zwraca:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Reprezentuje maksymalną wartość na osi wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Reprezentuje jednostki poboczne dla osi daty lub wartości. Odczyt/zapis double.

**Zwraca:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Reprezentuje jednostki poboczne dla osi daty lub wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Wskazuje, czy poboczna jednostka osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Wskazuje, czy poboczna jednostka osi jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Reprezentuje jednostki główne dla osi daty lub wartości. Odczyt/zapis double.

**Zwraca:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Reprezentuje jednostki główne dla osi daty lub wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Wskazuje, czy główna jednostka osi jest przypisywana automatycznie. Odczyt/zapis boolean.

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

Wskazuje, czy wartość minimalna jest przypisywana automatycznie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Wskazuje, czy wartość minimalna jest przypisywana automatycznie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Reprezentuje minimalną wartość na osi wartości. Odczyt/zapis double.

**Zwraca:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Reprezentuje minimalną wartość na osi wartości. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Reprezentuje, czy typ skali osi wartości jest logarytmiczny, czy nie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Reprezentuje, czy typ skali osi wartości jest logarytmiczny, czy nie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis double.

**Zwraca:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Reprezentuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Reprezentuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Reprezentuje, czy oś jest widoczna. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Reprezentuje, czy oś jest widoczna. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Reprezentuje typ głównego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Zwraca:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Reprezentuje typ głównego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Reprezentuje typ pobocznego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Zwraca:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Reprezentuje typ pobocznego znacznika podziałki dla określonej osi. Odczyt/zapis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Reprezentuje pozycję etykiet znaczników na określonej osi. Odczyt/zapis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Zwraca:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Reprezentuje pozycję etykiet znaczników na określonej osi. Odczyt/zapis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Reprezentuje skalę jednostki głównej dla osi dat. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Reprezentuje skalę jednostki głównej dla osi dat. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Reprezentuje skalę jednostki głównej dla osi dat. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Reprezentuje skalę jednostki głównej dla osi dat. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Określa najmniejszą jednostkę czasu reprezentowaną na osi dat. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Zwraca:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Określa najmniejszą jednostkę czasu reprezentowaną na osi dat. Odczyt/zapis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Reprezentuje format linii siatki pobocznej na osi wykresu. Tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Reprezentuje format linii siatki głównej na osi wykresu. Tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Reprezentuje, czy linie siatki pobocznej są wyświetlane. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Reprezentuje, czy linie siatki głównej są wyświetlane. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Reprezentuje format osi. Tylko do odczytu [IAxisFormat](../../com.aspose.slides/iaxisformat).

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

Reprezentuje CrossType na określonej osi, w którym inna oś się przecina. Odczyt/zapis [CrossesType](../../com.aspose.slides/crossestype).

**Zwraca:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Reprezentuje CrossType na określonej osi, w którym inna oś się przecina. Odczyt/zapis [CrossesType](../../com.aspose.slides/crossestype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Reprezentuje pozycję osi. Odczyt/zapis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Reprezentuje pozycję osi. Odczyt/zapis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Określa, czy oś posiada widoczny tytuł. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Określa, czy oś posiada widoczny tytuł. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Reprezentuje ciąg formatu dla etykiet osi. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Reprezentuje ciąg formatu dla etykiet osi. Odczyt/zapis String.

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

Reprezentuje kąt obrotu etykiet znaczników. Odczyt/zapis float.

**Zwraca:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Reprezentuje kąt obrotu etykiet znaczników. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Określa, ile etykiet znaczników pomijać pomiędzy rysowanymi etykietami. Odczyt/zapis long.

**Zwraca:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Określa, ile etykiet znaczników pomijać pomiędzy rysowanymi etykietami. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Określa automatyczną wartość odstępu etykiet znaczników. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Określa automatyczną wartość odstępu etykiet znaczników. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Określa, ile znaczników podziałki pomijać przed narysowaniem kolejnego. Stosowane dla osi kategorii lub serii. Odczyt/zapis int.

**Zwraca:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Określa, ile znaczników podziałki pomijać przed narysowaniem kolejnego. Stosowane dla osi kategorii lub serii. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Określa automatyczną wartość odstępu znaczników podziałki. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Określa automatyczną wartość odstępu znaczników podziałki. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Określa odległość etykiet od osi. Stosowane dla osi kategorii lub daty. Wartość musi mieścić się w przedziale od 0 % do 1000 %. Odczyt/zapis int.

**Zwraca:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Określa odległość etykiet od osi. Stosowane dla osi kategorii lub daty. Wartość musi mieścić się w przedziale od 0 % do 1000 %. Odczyt/zapis int.

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

Ustawia właściwość IAxis.CategoryAxisType na wartość określaną automatycznie na podstawie danych osi.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane dla kategorii. Używane wyłącznie w seriach Histogram lub HistogramPareto.

**Zwraca:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane dla kategorii. Używane wyłącznie w seriach Histogram lub HistogramPareto.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Określa szerokość wiadra, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. Stosowane do osi kategorialnych. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Returns:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Określa szerokość wiadra, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. Stosowane do osi kategorialnych. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Określa liczbę wiader, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorialnych. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Returns:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Określa liczbę wiader, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorialnych. Używane wyłącznie z seriami Histogram lub HistogramPareto.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Określa, czy zastosowano wiadro przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość wiadra przepełnienia.

**Returns:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Określa, czy zastosowano wiadro przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość wiadra przepełnienia.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Określa automatyczną wartość wiadra przepełnienia. Jeśli false: użyj właściwości OverflowBin.

**Returns:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Określa automatyczną wartość wiadra przepełnienia. Jeśli false: użyj właściwości OverflowBin.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Określa niestandardową wartość wiadra przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin ma wartość true.

**Returns:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Określa niestandardową wartość wiadra przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin ma wartość true.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Określa, czy zastosowano wiadro niedomiaru. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość wiadra niedomiaru.

**Returns:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Określa, czy zastosowano wiadro niedomiaru. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość wiadra niedomiaru.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Określa automatyczną wartość wiadra niedomiaru. Jeśli false: użyj właściwości UnderflowBin.

**Returns:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Określa automatyczną wartość wiadra niedomiaru. Jeśli false: użyj właściwości UnderflowBin.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Określa niestandardową wartość wiadra niedomiaru. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin ma wartość true.

**Returns:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Określa niestandardową wartość wiadra niedomiaru. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin ma wartość true.

**Parameters:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |