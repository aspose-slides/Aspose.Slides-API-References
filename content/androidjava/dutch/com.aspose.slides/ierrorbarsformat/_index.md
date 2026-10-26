---
title: IErrorBarsFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt foutbalken van diagramreeksen voor.
type: docs
url: /nl/com.aspose.slides/ierrorbarsformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Vertegenwoordigt foutbalken van diagramreeksen. Aangepaste waarden van ErrorBars bevinden zich in IChartDataPointCollection (in eigenschap [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Verkrijgt of stelt het type van foutbalken in. |
| [setType(int value)](#setType-int-) | Verkrijgt of stelt het type van foutbalken in. |
| [getValueType()](#getValueType--) | Vertegenwoordigt mogelijke manieren om de lengte van de foutbalken te bepalen. |
| [setValueType(int value)](#setValueType-int-) | Vertegenwoordigt mogelijke manieren om de lengte van de foutbalken te bepalen. |
| [hasEndCap()](#hasEndCap--) | Geeft aan dat er geen eindkap op de foutbalken wordt getekend. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Geeft aan dat er geen eindkap op de foutbalken wordt getekend. |
| [getValue()](#getValue--) | Verkrijgt of stelt de waarde in die wordt gebruikt met de typen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. |
| [setValue(float value)](#setValue-float-) | Verkrijgt of stelt de waarde in die wordt gebruikt met de typen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. |
| [getFormat()](#getFormat--) | Vertegenwoordigt het formaat van de foutbalken. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Vertegenwoordigt het formaat van de foutbalken. |
| [isVisible()](#isVisible--) | Verkrijgt of stelt de zichtbaarheid van foutbalken in. |
| [setVisible(boolean value)](#setVisible-boolean-) | Verkrijgt of stelt de zichtbaarheid van foutbalken in. |

### getType() {#getType--}
```
public abstract int getType()
```

Verkrijgt of stelt het type van foutbalken in. Lezen/schrijven [ErrorBarType](../../com.aspose.slides/errorbartype).

**Retourwaarde:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Verkrijgt of stelt het type van foutbalken in. Lezen/schrijven [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Vertegenwoordigt mogelijke manieren om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype moet de waarde worden opgegeven via de eigenschap [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) van een specifiek gegevenspunt in de DataPoints-collectie van de reeks. Lezen/schrijven [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Retourwaarde:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Vertegenwoordigt mogelijke manieren om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype moet de waarde worden opgegeven via de eigenschap [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) van een specifiek gegevenspunt in de DataPoints-collectie van de reeks. Lezen/schrijven [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Geeft aan dat er geen eindkap op de foutbalken wordt getekend. Lezen/schrijven boolean.

**Retourwaarde:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Geeft aan dat er geen eindkap op de foutbalken wordt getekend. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Verkrijgt of stelt de waarde in die wordt gebruikt met de typen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. Lezen/schrijven float.

**Retourwaarde:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Verkrijgt of stelt de waarde in die wordt gebruikt met de typen Fixed, Percentage en StandardDeviation om de lengte van de foutbalken te bepalen. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vertegenwoordigt het formaat van de foutbalken. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Retourwaarde:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Vertegenwoordigt het formaat van de foutbalken. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Verkrijgt of stelt de zichtbaarheid van foutbalken in. Lezen/schrijven boolean.

**Retourwaarde:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Verkrijgt of stelt de zichtbaarheid van foutbalken in. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |