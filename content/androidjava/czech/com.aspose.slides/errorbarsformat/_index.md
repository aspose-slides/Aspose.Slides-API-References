---
title: ErrorBarsFormat
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje chybové pruhy řady grafu.
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

Představuje chybové pruhy řady grafu. Vlastní hodnoty ErrorBars jsou v IChartDataPointCollection (v ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) vlastnosti).
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Získá nebo nastaví typ chybových pruhů. |
| [setType(int value)](#setType-int-) | Získá nebo nastaví typ chybových pruhů. |
| [getValueType()](#getValueType--) | Představuje možné způsoby určení délky chybových pruhů. |
| [setValueType(int value)](#setValueType-int-) | Představuje možné způsoby určení délky chybových pruhů. |
| [hasEndCap()](#hasEndCap--) | Určuje, že koncová čepka není vykreslena na chybových pruzích. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Určuje, že koncová čepka není vykreslena na chybových pruzích. |
| [getValue()](#getValue--) | Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. |
| [setValue(float value)](#setValue-float-) | Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. |
| [getFormat()](#getFormat--) | Představuje formát chybových pruhů. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Představuje formát chybových pruhů. |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [isVisible()](#isVisible--) | Získá nebo nastaví viditelnost chybových pruhů. |
| [setVisible(boolean value)](#setVisible-boolean-) | Získá nebo nastaví viditelnost chybových pruhů. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |
### getType() {#getType--}
```
public final int getType()
```


Získá nebo nastaví typ chybových pruhů. Čtení/zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Návratová hodnota:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Získá nebo nastaví typ chybových pruhů. Čtení/zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```


Představuje možné způsoby určení délky chybových pruhů. V případě vlastního typu hodnoty pro zadání hodnoty použijte vlastnost ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) konkrétního datového bodu ve sbírce DataPoints řady. V případě typů hodnot Fixed, Percentage nebo StandardDeviation použijte vlastnost Value pro zadání hodnoty. Čtení/zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Návratová hodnota:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```


Představuje možné způsoby určení délky chybových pruhů. V případě vlastního typu hodnoty pro zadání hodnoty použijte vlastnost ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) konkrétního datového bodu ve sbírce DataPoints řady. V případě typů hodnot Fixed, Percentage nebo StandardDeviation použijte vlastnost Value pro zadání hodnoty. Čtení/zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```


Určuje, že koncová čepka není vykreslena na chybových pruzích. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```


Určuje, že koncová čepka není vykreslena na chybových pruzích. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```


Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. V ostatních případech vrátí NaN. Čtení/zápis float.

**Návratová hodnota:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```


Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových pruhů. V ostatních případech vrátí NaN. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Představuje formát chybových pruhů. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Návratová hodnota:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Představuje formát chybových pruhů. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Vrací nadřazený graf. Pouze ke čtení [IChart](../../com.aspose.slides/ichart).

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Získá nebo nastaví viditelnost chybových pruhů. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Získá nebo nastaví viditelnost chybových pruhů. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Vrací nadřazený snímek objektu FillFormat. Pouze ke čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Návratová hodnota:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Vrací nadřazenou prezentaci objektu FillFormat. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation)