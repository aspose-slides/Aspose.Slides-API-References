---
title: Trendline
second_title: Aspose.Slides voor Android via Java API-referentie
description: Klasse stelt trendlijn van diagramreeks voor
type: docs
url: /nl/com.aspose.slides/trendline/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Klasse stelt trendlijn van diagramreeks voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Haalt de naam van de trendlijn op of stelt deze in. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Haalt de naam van de trendlijn op of stelt deze in. |
| [getTrendlineType()](#getTrendlineType--) | Haalt het type van de trendlijn op of stelt dit in. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Haalt het type van de trendlijn op of stelt dit in. |
| [getFormat()](#getFormat--) | Stelt het formaat van de trendlijn voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt het formaat van de trendlijn voor. |
| [getBackward()](#getBackward--) | Geeft het aantal categorieën (of eenheden op een spreidingsdiagram) op dat de trendlijn zich uitstrekt vóór de gegevens van de reeks die wordt getrende. |
| [setBackward(double value)](#setBackward-double-) | Geeft het aantal categorieën (of eenheden op een spreidingsdiagram) op dat de trendlijn zich uitstrekt vóór de gegevens van de reeks die wordt getrende. |
| [getForward()](#getForward--) | Geeft het aantal categorieën (of eenheden op een spreidingsdiagram) op dat de trendlijn zich uitstrekt na de gegevens van de reeks die wordt getrende. |
| [setForward(double value)](#setForward-double-) | Geeft het aantal categorieën (of eenheden op een spreidingsdiagram) op dat de trendlijn zich uitstrekt na de gegevens van de reeks die wordt getrende. |
| [getIntercept()](#getIntercept--) | Bepaalt de waarde waar de trendlijn de y-as kruist. |
| [setIntercept(double value)](#setIntercept-double-) | Bepaalt de waarde waar de trendlijn de y-as kruist. |
| [getDisplayEquation()](#getDisplayEquation--) | Bepaalt dat de vergelijking voor de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Bepaalt dat de vergelijking voor de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de Rsquaredvalue). |
| [getOrder()](#getOrder--) | Bepaalt de orde van de polynomiale trendlijn. |
| [setOrder(byte value)](#setOrder-byte-) | Bepaalt de orde van de polynomiale trendlijn. |
| [getPeriod()](#getPeriod--) | Bepaalt de periode van de trendlijn voor een voortschrijdend gemiddelde. |
| [setPeriod(byte value)](#setPeriod-byte-) | Bepaalt de periode van de trendlijn voor een voortschrijdend gemiddelde. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Bepaalt dat de R-kwadraat-waarde van de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de vergelijking). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Bepaalt dat de R-kwadraat-waarde van de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de vergelijking). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Vertegenwoordigt legende-item gerelateerd aan deze trendlijn Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialiseert TextFrameForOverriding met de tekst in parameter “text”. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Kan een rijk opgemaakte tekst bevatten. |
| [getTextFormat()](#getTextFormat--) | Retourt tekstformaat. |
| [getChart()](#getChart--) | Retourt het bovenliggende diagram. |
| [getSlide()](#getSlide--) | Retourt de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourt de bovenliggende presentatie van een FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Haalt de naam van de trendlijn op of stelt deze in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Stelt de naam van de trendlijn in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Haalt het type van de trendlijn op of stelt dit in. Lezen/Schrijven [TrendlineType](../../com.aspose.slides/trendlinetype).

**Retour:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Stelt het type van de trendlijn in. Lezen/Schrijven [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stelt het formaat van de trendlijn voor. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stelt het formaat van de trendlijn in. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Geeft het aantal categorieën (of eenheden op een spreidingsdiagram) op dat de trendlijn zich uitstrekt vóór de gegevens van de reeks die wordt getrende. Op spreidings- en niet-spreidingsdiagrammen mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Retour:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Stelt het aantal categorieën (of eenheden op een spreidingsdiagram) in dat de trendlijn zich uitstrekt vóór de gegevens van de reeks die wordt getrende. Op spreidings- en niet-spreidingsdiagrammen mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Geeft het aantal categorieën (of eenheden op een spreidingsdiagram) op dat de trendlijn zich uitstrekt na de gegevens van de reeks die wordt getrende. Op spreidings- en niet-spreidingsdiagrammen mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Retour:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Stelt het aantal categorieën (of eenheden op een spreidingsdiagram) in dat de trendlijn zich uitstrekt na de gegevens van de reeks die wordt getrende. Op spreidings- en niet-spreidingsdiagrammen mag de waarde elk niet-negatief getal zijn. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Bepaalt de waarde waar de trendlijn de y-as kruist. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, linear of poly is. Lezen/Schrijven double.

**Retour:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Stelt de waarde in waar de trendlijn de y-as kruist. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, linear of poly is. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Bepaalt dat de vergelijking voor de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de Rsquaredvalue). Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Stelt in dat de vergelijking voor de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de Rsquaredvalue). Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Bepaalt de orde van de polynomiale trendlijn. Wordt genegeerd voor andere trendlijntypen. De waarde moet tussen 2 en 6 liggen. Lezen/Schrijven byte.

**Retour:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Stelt de orde van de polynomiale trendlijn in. Wordt genegeerd voor andere trendlijntypen. De waarde moet tussen 2 en 6 liggen. Lezen/Schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Bepaalt de periode van de trendlijn voor een voortschrijdend gemiddelde. Wordt genegeerd voor andere varianten van trendlijnen. De waarde moet tussen 2 en 255 liggen. Lezen/Schrijven byte.

**Retour:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Stelt de periode van de trendlijn voor een voortschrijdend gemiddelde in. Wordt genegeerd voor andere varianten van trendlijnen. De waarde moet tussen 2 en 255 liggen. Lezen/Schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Bepaalt dat de R-kwadraat-waarde van de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de vergelijking). Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Stelt in dat de R-kwadraat-waarde van de trendlijn op het diagram wordt weergegeven (in hetzelfde label als de vergelijking). Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Vertegenwoordigt legende-item gerelateerd aan deze trendlijn Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retour:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialiseert TextFrameForOverriding met de tekst in parameter “text”. Als TextFrameForOverriding al is geïnitialiseerd, wordt de tekst simpelweg gewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst voor een nieuwe TextFrameForOverriding. |

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekst de automatisch gegenereerde tekst van gegevenslabel. Automatisch gegenereerde tekst van gegevenslabel betekent tekst die wordt beheerd door de eigenschappen ShowSeriesName, ShowValue, … en die wordt opgemaakt met de eigenschap TextFormatManager.TextFormat. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retourneert tekstformaat. Alleen-lezen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retour:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert het bovenliggende diagram. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retour:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)