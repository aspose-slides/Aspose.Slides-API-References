---
title: Trendline
second_title: Aspose.Slides för Android via Java API-referens
description: Klassen representerar trendlinjen för diagramserie
type: docs
url: /sv/com.aspose.slides/trendline/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Klassen representerar trendlinjen för diagramserie
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Hämtar eller anger namn på trendlinjen. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Hämtar eller anger namn på trendlinjen. |
| [getTrendlineType()](#getTrendlineType--) | Hämtar eller anger typ av trendlinje. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Hämtar eller anger typ av trendlinje. |
| [getFormat()](#getFormat--) | Representerar formatet för trendlinjen. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representerar formatet för trendlinjen. |
| [getBackward()](#getBackward--) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig innan data för serien som trenderas. |
| [setBackward(double value)](#setBackward-double-) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig innan data för serien som trenderas. |
| [getForward()](#getForward--) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för serien som trenderas. |
| [setForward(double value)](#setForward-double-) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för serien som trenderas. |
| [getIntercept()](#getIntercept--) | Anger värdet där trendlinjen ska korsar y-axeln. |
| [setIntercept(double value)](#setIntercept-double-) | Anger värdet där trendlinjen ska korsar y-axeln. |
| [getDisplayEquation()](#getDisplayEquation--) | Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). |
| [getOrder()](#getOrder--) | Anger ordningen för den polynoma trendlinjen. |
| [setOrder(byte value)](#setOrder-byte-) | Anger ordningen för den polynoma trendlinjen. |
| [getPeriod()](#getPeriod--) | Anger perioden för trendlinjen för ett glidande medelvärde. |
| [setPeriod(byte value)](#setPeriod-byte-) | Anger perioden för trendlinjen för ett glidande medelvärde. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Anger att R-squared-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Anger att R-squared-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representerar legendelementet relaterat till denna trendlinje Läs-endast [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initierar TextFrameForOverriding med texten i parametern "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan innehålla en rik formaterad text. |
| [getTextFormat()](#getTextFormat--) | Returnerar textformat. |
| [getChart()](#getChart--) | Returnerar överordnat diagram. |
| [getSlide()](#getSlide--) | Returnerar överordnad bild för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar överordnad presentation för ett FillFormat. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Hämtar eller anger namn på trendlinjen. Läs-skriv String.

**Returnerar:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Hämtar eller anger namn på trendlinjen. Läs-skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Hämtar eller anger typ av trendlinje. Läs-skriv [TrendlineType](../../com.aspose.slides/trendlinetype).

**Returnerar:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Hämtar eller anger typ av trendlinje. Läs-skriv [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representerar formatet för trendlinjen. Läs-skriv [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Representerar formatet för trendlinjen. Läs-skriv [IFormat](../../com.aspose.slides/iformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig innan data för serien som trenderas. På spridnings- och icke-spridningsdiagram får värdet vara vilket icke-negativt tal som helst. Läs-skriv double.

**Returnerar:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig innan data för serien som trenderas. På spridnings- och icke-spridningsdiagram får värdet vara vilket icke-negativt tal som helst. Läs-skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för serien som trenderas. På spridnings- och icke-spridningsdiagram får värdet vara vilket icke-negativt tal som helst. Läs-skriv double.

**Returnerar:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för serien som trenderas. På spridnings- och icke-spridningsdiagram får värdet vara vilket icke-negativt tal som helst. Läs-skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Anger värdet där trendlinjen ska korsar y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, linear eller poly. Läs-skriv double.

**Returnerar:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Anger värdet där trendlinjen ska korsar y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, linear eller poly. Läs-skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). Läs-skriv boolean.

**Returnerar:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). Läs-skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Anger ordningen för den polynoma trendlinjen. Ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Läs-skriv byte.

**Returnerar:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Anger ordningen för den polynoma trendlinjen. Ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Läs-skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Anger perioden för trendlinjen för ett glidande medelvärde. Ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Läs-skriv byte.

**Returnerar:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Anger perioden för trendlinjen för ett glidande medelvärde. Ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Läs-skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Anger att R-squared-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). Läs-skriv boolean.

**Returnerar:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Anger att R-squared-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). Läs-skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representerar legendelementet relaterat till denna trendlinje Läs-endast [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initierar TextFrameForOverriding med texten i parametern "text". Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text för ett nytt TextFrameForOverriding. |

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kan innehålla en rik formaterad text. Om denna egenskap inte är null, så åsidosätter detta formaterade textvärde automatiskt genererad text för datamärket. Automatiskt genererad text för datamärket betyder text som hanteras av ShowSeriesName, ShowValue, ...-egenskaper och som formateras med TextFormatManager.TextFormat-egenskapen. Läs-endå…[ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Returnerar textformat. Läs-endå…[IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returnerar:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar överordnat diagram. Läs-endå…[IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar överordnad bild för ett FillFormat. Läs-endå…[BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar överordnad presentation för ett FillFormat. Läs-endå…[IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)