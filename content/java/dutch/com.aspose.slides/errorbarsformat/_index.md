---
title: ErrorBarsFormat
second_title: Aspose.Slides voor Java API-referentie
description: Representeert foutbalken van een grafiekserie.
type: docs
url: /nl/com.aspose.slides/errorbarsformat/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Stelt foutbalken van een grafiekserie voor. Foutbalken aangepaste waarden bevinden zich in IChartDataPointCollection (in ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Haalt of stelt het type van foutbalken in. |
| [setType(int value)](#setType-int-) | Haalt of stelt het type van foutbalken in. |
| [getValueType()](#getValueType--) | Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. |
| [setValueType(int value)](#setValueType-int-) | Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. |
| [hasEndCap()](#hasEndCap--) | Geeft aan dat er geen eindkap op de foutbalken wordt getekend. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Geeft aan dat er geen eindkap op de foutbalken wordt getekend. |
| [getValue()](#getValue--) | Haalt of stelt een waarde in die wordt gebruikt met de waardetypen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. |
| [setValue(float value)](#setValue-float-) | Haalt of stelt een waarde in die wordt gebruikt met de waardetypen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. |
| [getFormat()](#getFormat--) | Stelt het formaat van de foutbalken voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt het formaat van de foutbalken voor. |
| [getChart()](#getChart--) | Retourneert de bovenliggende grafiek. |
| [isVisible()](#isVisible--) | Haalt of stelt Error Bars zichtbaarheid in. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt of stelt Error Bars zichtbaarheid in. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

Haalt of stelt het type van foutbalken in. Lezen/schrijven [ErrorBarType](../../com.aspose.slides/errorbartype).

**Retourneert:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Haalt of stelt het type van foutbalken in. Lezen/schrijven [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```

Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype om een waarde te specificeren, gebruik de ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap van een specifiek gegevenspunt in de DataPoints-collectie van de serie. In het geval van Fixed, Percentage of StandardDeviation waardetype gebruik je de Value eigenschap om de waarde te specificeren. Lezen/schrijven [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Retourneert:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype om een waarde te specificeren, gebruik de ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap van een specifiek gegevenspunt in de DataPoints-collectie van de serie. In het geval van Fixed, Percentage of StandardDeviation waardetype gebruik je de Value eigenschap om de waarde te specificeren. Lezen/schrijven [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Geeft aan dat er geen eindkap op de foutbalken wordt getekend. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Geeft aan dat er geen eindkap op de foutbalken wordt getekend. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```

Haalt of stelt een waarde in die wordt gebruikt met de waardetypen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. In alle andere gevallen wordt NaN geretourneerd. Lezen/schrijven float.

**Retourneert:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Haalt of stelt een waarde in die wordt gebruikt met de waardetypen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. In alle andere gevallen wordt NaN geretourneerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stelt het formaat van de foutbalken voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stelt het formaat van de foutbalken voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Haalt of stelt Error Bars zichtbaarheid in. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Haalt of stelt Error Bars zichtbaarheid in. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)