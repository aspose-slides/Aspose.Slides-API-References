---
title: ITrendline
second_title: Aspose.Slides für Java API-Referenz
description: Klasse repräsentiert die Trendlinie einer Diagrammreihe
type: docs
url: /de/com.aspose.slides/itrendline/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Klasse repräsentiert die Trendlinie einer Diagrammreihe
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Liest oder setzt den Namen der Trendlinie. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Liest oder setzt den Namen der Trendlinie. |
| [getTrendlineType()](#getTrendlineType--) | Liest oder setzt den Typ der Trendlinie. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Liest oder setzt den Typ der Trendlinie. |
| [getFormat()](#getFormat--) | Stellt das Format der Trendlinie dar. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stellt das Format der Trendlinie dar. |
| [getBackward()](#getBackward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der Trendreihe erweitert. |
| [setBackward(double value)](#setBackward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der Trendreihe erweitert. |
| [getForward()](#getForward--) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der Trendreihe erweitert. |
| [setForward(double value)](#setForward-double-) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der Trendreihe erweitert. |
| [getIntercept()](#getIntercept--) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [setIntercept(double value)](#setIntercept-double-) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. |
| [getDisplayEquation()](#getDisplayEquation--) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). |
| [getOrder()](#getOrder--) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [setOrder(byte value)](#setOrder-byte-) | Gibt die Ordnung der polynomialen Trendlinie an. |
| [getPeriod()](#getPeriod--) | Gibt den Zeitraum der Trendlinie für eine gleitende Mittelwert-Trendlinie an. |
| [setPeriod(byte value)](#setPeriod-byte-) | Gibt den Zeitraum der Trendlinie für eine gleitende Mittelwert-Trendlinie an. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt den Legendeneintrag dar, der mit dieser Trendlinie verknüpft ist, Nur Lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```


Liest oder setzt den Namen der Trendlinie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```


Liest oder setzt den Namen der Trendlinie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```


Liest odersetzt den Typ der Trendlinie. Lesen/Schreiben [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Rückgabe:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```


Liest oder setzt den Typ der Trendlinie. Lesen/Schreiben [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Stellt das Format der Trendlinie dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Stellt das Format der Trendlinie dar. Lesen/Schreiben [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```


Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der Trendreihe erweitert. Bei Streu- und Nicht-Streudiagrammen muss der Wert ein nichtnegativer Wert sein. Lesen/Schreiben double.

**Rückgabe:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```


Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der Trendreihe erweitert. Bei Streu- und Nicht-Streudiagrammen muss der Wert ein nichtnegativer Wert sein. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```


Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der Trendreihe erweitert. Bei Streu- und Nicht-Streudiagrammen muss der Wert ein nichtnegativer Wert sein. Lesen/Schreiben double.

**Rückgabe:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```


Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der Trendreihe erweitert. Bei Streu- und Nicht-Streudiagrammen muss der Wert ein nichtnegativer Wert sein. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```


Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lesen/Schreiben double.

**Rückgabe:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```


Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```


Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```


Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```


Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lesen/Schreiben byte.

**Rückgabe:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```


Gibt die Ordnung der polynomialen Trendlinie an. Sie wird für andere Trendlinientypen ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lesen/Schreiben byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```


Gibt den Zeitraum der Trendlinie für eine gleitende Mittelwert-Trendlinie an. Sie wird für andere Trendlinienvarianten ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lesen/Schreiben byte.

**Rückgabe:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```


Gibt den Zeitraum der Trendlinie für eine gleitende Mittelwert-Trendlinie an. Sie wird für andere Trendlinienvarianten ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lesen/Schreiben byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```


Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```


Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Stellt den Legendeneintrag dar, der mit dieser Trendlinie verknüpft ist, Nur Lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)