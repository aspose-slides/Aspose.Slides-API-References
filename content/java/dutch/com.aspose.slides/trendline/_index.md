---
title: Trendline
second_title: Aspose.Slides voor Java API-referentie
description: Klasse vertegenwoordigt trendlijn van grafiekreeks
type: docs
url: /nl/com.aspose.slides/trendline/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Klasse vertegenwoordigt trendlijn van grafiekreeks
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Verkrijgt of stelt de naam van de trendlijn in. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Verkrijgt of stelt de naam van de trendlijn in. |
| [getTrendlineType()](#getTrendlineType--) | Verkrijgt of stelt type van trendlijn in. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Verkrijgt of stelt type van trendlijn in. |
| [getFormat()](#getFormat--) | Vertegenwoordigt het formaat van de trendlijn. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Vertegenwoordigt het formaat van de trendlijn. |
| [getBackward()](#getBackward--) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. |
| [setBackward(double value)](#setBackward-double-) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. |
| [getForward()](#getForward--) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. |
| [setForward(double value)](#setForward-double-) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. |
| [getIntercept()](#getIntercept--) | Specificeert de waarde waar de trendlijn de y-as moet kruisen. |
| [setIntercept(double value)](#setIntercept-double-) | Specificeert de waarde waar de trendlijn de y-as moet kruisen. |
| [getDisplayEquation()](#getDisplayEquation--) | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredvalue). |
| [getOrder()](#getOrder--) | Specificeert de orde van de polynomiale trendlijn. |
| [setOrder(byte value)](#setOrder-byte-) | Specificeert de orde van de polynomiale trendlijn. |
| [getPeriod()](#getPeriod--) | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde. |
| [setPeriod(byte value)](#setPeriod-byte-) | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Vertegenwoordigt legende-item gerelateerd aan deze trendlijn Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialiseer TextFrameForOverriding met de tekst in parameter "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan een rijk opgemaakte tekst bevatten. |
| [getTextFormat()](#getTextFormat--) | Retourneert tekstopmaak. |
| [getChart()](#getChart--) | Retourneert het bovenliggende diagram. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Verkrijgt of stelt de naam van de trendlijn in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Verkrijgt of stelt de naam van de trendlijn in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Verkrijgt of stelt type van trendlijn in. Lezen/Schrijven [TrendlineType](../../com.aspose.slides/trendlinetype).

**Retourneert:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Verkrijgt of stelt type van trendlijn in. Lezen/Schrijven [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Vertegenwoordigt het formaat van de trendlijn. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Vertegenwoordigt het formaat van de trendlijn. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Retourneert:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Retourneert:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Specificeert de waarde waar de trendlijn de y-as moet kruisen. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, linear of poly is. Lezen/Schrijven double.

**Retourneert:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Specificeert de waarde waar de trendlijn de y-as moet kruisen. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, linear of poly is. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredvalue). Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredvalue). Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Specificeert de orde van de polynomiale trendlijn. Deze wordt genegeerd voor andere trendlijntypen. Waarde moet tussen 2 en 6 liggen. Lezen/Schrijven byte.

**Retourneert:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Specificeert de orde van de polynomiale trendlijn. Deze wordt genegeerd voor andere trendlijntypen. Waarde moet tussen 2 en 6 liggen. Lezen/Schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde. Deze wordt genegeerd voor andere trendlijnvarianten. Waarde moet tussen 2 en 255 liggen. Lezen/Schrijven byte.

**Retourneert:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde. Deze wordt genegeerd voor andere trendlijnvarianten. Waarde moet tussen 2 en 255 liggen. Lezen/Schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Vertegenwoordigt legende-item gerelateerd aan deze trendlijn Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retourneert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialiseer TextFrameForOverriding met de tekst in parameter "text". Als TextFrameForOverriding al is geïnitialiseerd, wordt de tekst eenvoudigweg gewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst voor een nieuw TextFrameForOverriding. |

**Retourneert:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst van het gegevenslabel. Automatisch gegenereerde tekst van het gegevenslabel betekent tekst die wordt beheerd door de eigenschappen ShowSeriesName, ShowValue, … en wordt opgemaakt met de TextFormatManager.TextFormat eigenschap. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retourneert:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retourneert tekstopmaak. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retourneert:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert het bovenliggende diagram. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)

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