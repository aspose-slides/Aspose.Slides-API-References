---
title: ITrendline
second_title: Aspose.Slides voor Android via Java API-referentie
description: Klasse vertegenwoordigt trendlijn van grafiekreeks
type: docs
url: /nl/com.aspose.slides/itrendline/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Klasse vertegenwoordigt trendlijn van grafiekreeks
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Haalt de naam van de trendlijn op of stelt deze in. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Haalt de naam van de trendlijn op of stelt deze in. |
| [getTrendlineType()](#getTrendlineType--) | Haalt het type van de trendlijn op of stelt dit in. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Haalt het type van de trendlijn op of stelt dit in. |
| [getFormat()](#getFormat--) | Stelt het formaat van de trendlijn voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt het formaat van de trendlijn voor. |
| [getBackward()](#getBackward--) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. |
| [setBackward(double value)](#setBackward-double-) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. |
| [getForward()](#getForward--) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. |
| [setForward(double value)](#setForward-double-) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. |
| [getIntercept()](#getIntercept--) | Specificeert de waarde waarop de trendlijn de y-as snijdt. |
| [setIntercept(double value)](#setIntercept-double-) | Specificeert de waarde waarop de trendlijn de y-as snijdt. |
| [getDisplayEquation()](#getDisplayEquation--) | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredwaarde). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredwaarde). |
| [getOrder()](#getOrder--) | Specificeert de orde van de polynomiale trendlijn. |
| [setOrder(byte value)](#setOrder-byte-) | Specificeert de orde van de polynomiale trendlijn. |
| [getPeriod()](#getPeriod--) | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde trendlijn. |
| [setPeriod(byte value)](#setPeriod-byte-) | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde trendlijn. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stelt legende-item gerelateerd aan deze trendlijn voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Haalt de naam van de trendlijn op of stelt deze in. Alleen-lezen String.

**Returns:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Haalt de naam van de trendlijn op of stelt deze in. Alleen-lezen String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Haalt het type van de trendlijn op of stelt dit in. Lees/schrijf [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Returns:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Haalt het type van de trendlijn op of stelt dit in. Lees/schrijf [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stelt het formaat van de trendlijn voor. Lees/schrijf [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Stelt het formaat van de trendlijn voor. Lees/schrijf [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lees/schrijf double.

**Returns:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lees/schrijf double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lees/schrijf double.

**Returns:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrendeerd. Op spreidings- en niet-spreidingsgrafieken mag de waarde elk niet-negatief getal zijn. Lees/schrijf double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Specificeert de waarde waarop de trendlijn de y-as snijdt. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, linear of poly is. Lees/schrijf double.

**Returns:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Specificeert de waarde waarop de trendlijn de y-as snijdt. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, linear of poly is. Lees/schrijf double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredwaarde). Lees/schrijf boolean.

**Returns:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredwaarde). Lees/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Specificeert de orde van de polynomiale trendlijn. Wordt genegeerd voor andere trendlijntypen. Waarde moet tussen 2 en 6 liggen. Lees/schrijf byte.

**Returns:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Specificeert de orde van de polynomiale trendlijn. Wordt genegeerd voor andere trendlijntypen. Waarde moet tussen 2 en 6 liggen. Lees/schrijf byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde trendlijn. Wordt genegeerd voor andere trendlijnvarianten. Waarde moet tussen 2 en 255 liggen. Lees/schrijf byte.

**Returns:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde trendlijn. Wordt genegeerd voor andere trendlijnvarianten. Waarde moet tussen 2 en 255 liggen. Lees/schrijf byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). Lees/schrijf boolean.

**Returns:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). Lees/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Stelt legende-item gerelateerd aan deze trendlijn voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)