---
title: IErrorBarsFormat
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt foutbalken van een diagramreeks.
type: docs
url: /nl/com.aspose.slides/ierrorbarsformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Stelt foutbalken van een diagramreeks voor. Aangepaste waarden van ErrorBars bevinden zich in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) eigenschap).

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Haalt of stelt het type van foutbalken in. |
| [setType(int value)](#setType-int-) | Haalt of stelt het type van foutbalken in. |
| [getValueType()](#getValueType--) | Stelt de mogelijke manieren voor om de lengte van de foutbalken te bepalen. |
| [setValueType(int value)](#setValueType-int-) | Stelt de mogelijke manieren voor om de lengte van de foutbalken te bepalen. |
| [hasEndCap()](#hasEndCap--) | Geeft aan dat er geen eindkap wordt getekend op de foutbalken. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Geeft aan dat er geen eindkap wordt getekend op de foutbalken. |
| [getValue()](#getValue--) | Haalt of stelt de waarde in die wordt gebruikt met de Fixed-, Percentage- en StandardDeviation-waardetypen om de lengte van de foutbalken te bepalen. |
| [setValue(float value)](#setValue-float-) | Haalt of stelt de waarde in die wordt gebruikt met de Fixed-, Percentage- en StandardDeviation-waardetypen om de lengte van de foutbalken te bepalen. |
| [getFormat()](#getFormat--) | Stelt het formaat van de foutbalken voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt het formaat van de foutbalken voor. |
| [isVisible()](#isVisible--) | Haalt of stelt de zichtbaarheid van foutbalken in. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt of stelt de zichtbaarheid van foutbalken in. |

### getType() {#getType--}
```
public abstract int getType()
```

Haalt of stelt het type van foutbalken in. Lezen/schrijven [ErrorBarType](../../com.aspose.slides/errorbartype).

**Retour:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Haalt of stelt het type van foutbalken in. Lezen/schrijven [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Stelt de mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype gebruik je de [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) eigenschap van het specifieke gegevenspunt in de DataPoints-verzameling van de reeks. Lezen/schrijven [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Retour:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Stelt de mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype gebruik je de [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) eigenschap van het specifieke gegevenspunt in de DataPoints-verzameling van de reeks. Lezen/schrijven [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Geeft aan dat er geen eindkap wordt getekend op de foutbalken. Lezen/schrijven boolean.

**Retour:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Geeft aan dat er geen eindkap wordt getekend op de foutbalken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Haalt of stelt de waarde in die wordt gebruikt met de Fixed-, Percentage- en StandardDeviation-waardetypen om de lengte van de foutbalken te bepalen. Lezen/schrijven float.

**Retour:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Haalt of stelt de waarde in die wordt gebruikt met de Fixed-, Percentage- en StandardDeviation-waardetypen om de lengte van de foutbalken te bepalen. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stelt het formaat van de foutbalken voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Stelt het formaat van de foutbalken voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Haalt of stelt de zichtbaarheid van foutbalken in. Lezen/schrijven boolean.

**Retour:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Haalt of stelt de zichtbaarheid van foutbalken in. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |