---
title: ErrorBarsFormat
second_title: Aspose.Slides pro Java API Referenční příručka
description: Reprezentuje chybové pruhy řady grafu.
type: docs
url: /cs/com.aspose.slides/errorbarsformat/
---
**Dědičnost:**  
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**  
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Představuje chybové pruhy řady grafu. Vlastní hodnoty ErrorBars jsou v IChartDataPointCollection (ve vlastnosti ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Získá nebo nastaví typ chybových pruhů. |
| [setType(int value)](#setType-int-) | Získá nebo nastaví typ chybových pruhů. |
| [getValueType()](#getValueType--) | Zastupuje možné způsoby určení délky chybových pruhů. |
| [setValueType(int value)](#setValueType-int-) | Zastupuje možné způsoby určení délky chybových pruhů. |
| [hasEndCap()](#hasEndCap--) | Určuje, že na konci chybových pruhů není kreslen koncový čep. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Určuje, že na konci chybových pruhů není kreslen koncový čep. |
| [getValue()](#getValue--) | Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. |
| [setValue(float value)](#setValue-float-) | Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. |
| [getFormat()](#getFormat--) | Zastupuje formát chybových pruhů. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Zastupuje formát chybových pruhů. |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [isVisible()](#isVisible--) | Získá nebo nastaví viditelnost chybových pruhů. |
| [setVisible(boolean value)](#setVisible-boolean-) | Získá nebo nastaví viditelnost chybových pruhů. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Získá nebo nastaví typ chybových pruhů. Čtení/Zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Vrací:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Získá nebo nastaví typ chybových pruhů. Čtení/Zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Zastupuje možné způsoby určení délky chybových pruhů. V případě vlastního typu hodnoty použijte vlastnost ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) konkrétního datového bodu ve sbírce DataPoints řady. V případě typů hodnot Fixed, Percentage nebo StandardDeviation použijte vlastnost Value k určení hodnoty. Čtení/Zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Vrací:**  
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Zastupuje možné způsoby určení délky chybových pruhů. V případě vlastního typu hodnoty použijte vlastnost ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) konkrétního datového bodu ve sbírce DataPoints řady. V případě typů hodnot Fixed, Percentage nebo StandardDeviation použijte vlastnost Value k určení hodnoty. Čtení/Zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Určuje, že na konci chybových pruhů není kreslen čep. Čtení/Zápis boolean.

**Vrací:**  
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Určuje, že na konci chybových pruhů není kreslen čep. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. V jiných případech vrátí NaN. Čtení/Zápis float.

**Vrací:**  
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. V jiných případech vrátí NaN. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Zastupuje formát chybových pruhů. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Zastupuje formát chybových pruhů. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze ke čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**  
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Získá nebo nastaví viditelnost chybových pruhů. Čtení/Zápis boolean.

**Vrací:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Získá nebo nastaví viditelnost chybových pruhů. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze ke čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**  
[IPresentation](../../com.aspose.slides/ipresentation)