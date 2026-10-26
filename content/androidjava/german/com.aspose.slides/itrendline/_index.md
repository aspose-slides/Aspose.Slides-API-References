---
title: ITrendline
second_title: Aspose.Slides für Android über Java API-Referenz
description: Klasse stellt die Trendlinie einer Diagrammreihe dar
type: docs
url: /de/com.aspose.slides/itrendline/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Klasse stellt die Trendlinie einer Diagrammreihe dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Liest oder setzt den Namen der Trendlinie. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Liest oder setzt den Namen der Trendlinie. |
| [getTrendlineType()](#getTrendlineType--) | Liest oder setzt den Typ der Trendlinie. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Liest oder setzt den Typ der Trendlinie. |
| [getFormat()](#getFormat--) | Stellt das Format der Trendlinie dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt das Format der Trendlinie dar. |
| [getBackward()](#getBackward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie vor den Daten der trendenden Serie erweitert wird. |
| [setBackward(double value)](#setBackward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie vor den Daten der trendenden Serie erweitert wird. |
| [getForward()](#getForward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie nach den Daten der trendenden Serie erweitert wird. |
| [setForward(double value)](#setForward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie nach den Daten der trendenden Serie erweitert wird. |
| [getIntercept()](#getIntercept--) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [setIntercept(double value)](#setIntercept-double-) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [getDisplayEquation()](#getDisplayEquation--) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). |
| [getOrder()](#getOrder--) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [setOrder(byte value)](#setOrder-byte-) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [getPeriod()](#getPeriod--) | Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. |
| [setPeriod(byte value)](#setPeriod-byte-) | Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt den Legendeeintrag dar, der mit dieser Trendlinie verbunden ist. Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Liest oder setzt den Namen der Trendlinie. Lese-/Schreibzugriff String.

**Rückgabewert:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Liest oder setzt den Namen der Trendlinie. Lese-/Schreibzugriff String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Liest oder setzt den Typ der Trendlinie. Lese-/Schreibzugriff [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Rückgabewert:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Liest oder setzt den Typ der Trendlinie. Lese-/Schreibzugriff [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stellt das Format der Trendlinie dar. Lese-/Schreibzugriff [IFormat](../../com.aspose.slides/iformat).

**Rückgabewert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Stellt das Format der Trendlinie dar. Lese-/Schreibzugriff [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie vor den Daten der trendenden Serie erweitert wird. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lese-/Schreibzugriff double.

**Rückgabewert:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie vor den Daten der trendenden Serie erweitert wird. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie nach den Daten der trendenden Serie erweitert wird. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lese-/Schreibzugriff double.

**Rückgabewert:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, um die die Trendlinie nach den Daten der trendenden Serie erweitert wird. Auf Streu- und Nicht-Streu-Diagrammen darf der Wert jeder nichtnegative Wert sein. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lese-/Schreibzugriff double.

**Rückgabewert:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lese-/Schreibzugriff double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). Lese-/Schreibzugriff boolean.

**Rückgabewert:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). Lese-/Schreibzugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lese-/Schreibzugriff byte.

**Rückgabewert:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lese-/Schreibzugriff byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. Sie wird für andere Trendlinienvarianten ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lese-/Schreibzugriff byte.

**Rückgabewert:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnittstrendlinie an. Sie wird für andere Trendlinienvarianten ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lese-/Schreibzugriff byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lese-/Schreibzugriff boolean.

**Rückgabewert:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lese-/Schreibzugriff boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Stellt den Legendeeintrag dar, der mit dieser Trendlinie verbunden ist. Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabewert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)