---
title: ErrorBarsFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar felstaplar för diagramserie.
type: docs
url: /sv/com.aspose.slides/errorbarsformat/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Representerar felstaplar för diagramserie. Anpassade värden för ErrorBars finns i IChartDataPointCollection (i egenskapen ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Hämtar eller anger typ av felstaplar. |
| [setType(int value)](#setType-int-) | Hämtar eller anger typ av felstaplar. |
| [getValueType()](#getValueType--) | Representerar möjliga sätt att bestämma längden på felstaplarna. |
| [setValueType(int value)](#setValueType-int-) | Representerar möjliga sätt att bestämma längden på felstaplarna. |
| [hasEndCap()](#hasEndCap--) | Anger att en ändkappa inte ritas på felstaplarna. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Anger att en ändkappa inte ritas på felstaplarna. |
| [getValue()](#getValue--) | Hämtar eller anger värde som används med Fixed-, Percentage- och StandardDeviation-värdetyper för att bestämma längden på felstaplarna. |
| [setValue(float value)](#setValue-float-) | Hämtar eller anger värde som används med Fixed-, Percentage- och StandardDeviation-värdetyper för att bestämma längden på felstaplarna. |
| [getFormat()](#getFormat--) | Representerar formatet för felstaplarna. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representerar formatet för felstaplarna. |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [isVisible()](#isVisible--) | Hämtar eller anger synlighet för Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger synlighet för Error Bars. |
| [getSlide()](#getSlide--) | Returnerar den överordnade sliden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Hämtar eller anger typ av felstaplar. Läs/skriv [ErrorBarType](../../com.aspose.slides/errorbartype).

**Returnerar:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Hämtar eller anger typ av felstaplar. Läs/skriv [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Representerar möjliga sätt att bestämma längden på felstaplarna. Vid anpassad värdetyp, ange värdet med egenskapen ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) för ett specifikt datapunkt i DataPoints-samlingen för serien. Vid Fixed-, Percentage- eller StandardDeviation-värdetyp, använd Value-egenskapen för att ange värdet. Läs/skriv [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Returnerar:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Representerar möjliga sätt att bestämma längden på felstaplarna. Vid anpassad värdetyp, ange värdet med egenskapen ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) för ett specifikt datapunkt i DataPoints-samlingen för serien. Vid Fixed-, Percentage- eller StandardDeviation-värdetyp, använd Value-egenskapen för att ange värdet. Läs/skriv [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Anger att en ändkappa inte ritas på felstaplarna. Läs/skriv boolean.

**Returnerar:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Anger att en ändkappa inte ritas på felstaplarna. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Hämtar eller anger värde som används med Fixed-, Percentage- och StandardDeviation-värdetyper för att bestämma längden på felstaplarna. I alla andra fall returneras NaN. Läs/skriv float.

**Returnerar:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Hämtar eller anger värde som används med Fixed-, Percentage- och StandardDeviation-värdetyper för att bestämma längden på felstaplarna. I alla andra fall returneras NaN. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representerar formatet för felstaplarna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Representerar formatet för felstaplarna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar det överordnade diagrammet. Endast läsning [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Hämtar eller anger synlighet för Error Bars. Läs/skriv boolean.

**Returnerar:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Hämtar eller anger synlighet för Error Bars. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade sliden för ett FillFormat. Endast läsning [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för ett FillFormat. Endast läsning [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)