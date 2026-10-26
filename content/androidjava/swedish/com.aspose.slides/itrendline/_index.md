---
title: ITrendline
second_title: Aspose.Slides för Android via Java API-referens
description: Klassen representerar trendlinjen för diagramserie
type: docs
url: /sv/com.aspose.slides/itrendline/
---
**All Implemented Interfaces:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Klassen representerar trendlinjen för diagramserie

## Metoder

| Method | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Hämtar eller anger namn på trendlinjen. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Hämtar eller anger namn på trendlinjen. |
| [getTrendlineType()](#getTrendlineType--) | Hämtar eller anger typ av trendlinje. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Hämtar eller anger typ av trendlinje. |
| [getFormat()](#getFormat--) | Representerar formatet för trendlinjen. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representerar formatet för trendlinjen. |
| [getBackward()](#getBackward--) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig före data för den serie som trenderas. |
| [setBackward(double value)](#setBackward-double-) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig före data för den serie som trenderas. |
| [getForward()](#getForward--) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. |
| [setForward(double value)](#setForward-double-) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. |
| [getIntercept()](#getIntercept--) | Anger värdet där trendlinjen ska korsa y-axeln. |
| [setIntercept(double value)](#setIntercept-double-) | Anger värdet där trendlinjen ska korsa y-axeln. |
| [getDisplayEquation()](#getDisplayEquation--) | Anger att ekvationen för trendlinjen visas i diagrammet (i samma etikett som Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Anger att ekvationen för trendlinjen visas i diagrammet (i samma etikett som Rsquaredvalue). |
| [getOrder()](#getOrder--) | Anger ordningen för den polynomiska trendlinjen. |
| [setOrder(byte value)](#setOrder-byte-) | Anger ordningen för den polynomiska trendlinjen. |
| [getPeriod()](#getPeriod--) | Anger perioden för trendlinjen för ett glidande medelvärde. |
| [setPeriod(byte value)](#setPeriod-byte-) | Anger perioden för trendlinjen för ett glidande medelvärde. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Anger att R-squared-värdet för trendlinjen visas i diagrammet (i samma etikett som ekvationen). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Anger att R-squared-värdet för trendlinjen visas i diagrammet (i samma etikett som ekvationen). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representerar legendpost relaterad till denna trendlinje Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Hämtar eller anger namn på trendlinjen. Läs/skriv String.

**Returnerar:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Hämtar eller anger namn på trendlinjen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Hämtar eller anger typ av trendlinje. Läs/skriv [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Returnerar:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Hämtar eller anger typ av trendlinje. Läs/skriv [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representerar formatet för trendlinjen. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representerar formatet för trendlinjen. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig före data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Läs/skriv double.

**Returnerar:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig före data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Läs/skriv double.

**Returnerar:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Anger värdet där trendlinjen ska korsa y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, linear eller poly. Läs/skriv double.

**Returnerar:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Anger värdet där trendlinjen ska korsa y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, linear eller poly. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Anger att ekvationen för trendlinjen visas i diagrammet (i samma etikett som Rsquaredvalue). Läs/skriv boolean.

**Returnerar:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Anger att ekvationen för trendlinjen visas i diagrammet (i samma etikett med Rsquaredvalue). Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Anger ordningen för den polynomiska trendlinjen. Ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Läs/skriv byte.

**Returnerar:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Anger ordningen för den polynomiska trendlinjen. Ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Anger perioden för trendlinjen för ett glidande medelvärde. Ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Läs/skriv byte.

**Returnerar:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Anger perioden för trendlinjen för ett glidande medelvärde. Ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Anger att R-squared-värdet för trendlinjen visas i diagrammet (i samma etikett som ekvationen). Läs/skriv boolean.

**Returnerar:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Anger att R-squared-värdet för trendlinjen visas i diagrammet (i samma etikett som ekvationen). Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Representerar legendpost relaterad till denna trendlinje Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)