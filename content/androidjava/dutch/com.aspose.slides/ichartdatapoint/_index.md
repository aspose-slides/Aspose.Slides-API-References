---
title: IChartDataPoint
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt seriedatapunt.
type: docs
url: /nl/com.aspose.slides/ichartdatapoint/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Vertegenwoordigt seriedatapunt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXValue()](#getXValue--) | Geeft de x-waarde van het grafiekdatapunt terug. |
| [getYValue()](#getYValue--) | Geeft de y-waarde van het grafiekdatapunt terug. |
| [getBubbleSize()](#getBubbleSize--) | Geeft de bubbelgrootte van het grafiekdatapunt terug. |
| [getValue()](#getValue--) | Geeft de waarde van het grafiekdatapunt terug. |
| [getSizeValue()](#getSizeValue--) | Geeft de groottewaarde van het grafiekdatapunt terug. |
| [getColorValue()](#getColorValue--) | Geeft de kleurwaarde van het grafiekdatapunt terug. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Vertegenwoordigt seriefoutbalkwaarden in het geval van Custom waarde-type. |
| [getLabel()](#getLabel--) | Vertegenwoordigt het label van het grafiekdatapunt. |
| [isBubble3D()](#isBubble3D--) | Specificeert dat de bubbels een 3-D-effect hebben. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specificeert dat de bubbels een 3-D-effect hebben. |
| [getExplosion()](#getExplosion--) | Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. |
| [setExplosion(int value)](#setExplosion-int-) | Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. |
| [getFormat()](#getFormat--) | Vertegenwoordigt de opmaak-eigenschappen. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Vertegenwoordigt de opmaak-eigenschappen. |
| [getMarker()](#getMarker--) | Specificeert een datamarker. |
| [remove()](#remove--) | Verwijdert DataPoint uit de grafiekseries. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Geeft een automatische kleur van het datapunt terug op basis van de reeks-index, datapunt-index, ParentSeriesGroup.IsColorVaried eigenschap en grafiekstijl. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschappen van het overeenkomende legende-item in het geval van graafoortype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Stelt datapunt in als totaal. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Stelt datapunt in als totaal. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. |
| [getDataPointLevels()](#getDataPointLevels--) | Geeft de container van datapunt-niveaus terug. |
| [getIndex()](#getIndex--) | Bepaalt op welke van de kindcollecties van de ouder dit datapunt van toepassing is. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Geeft de x-waarde van het grafiekdatapunt terug. Alleen-lezen [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retourneert:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Geeft de y-waarde van het grafiekdatapunt terug. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Geeft de bubbelgrootte van het grafiekdatapunt terug. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Geeft de waarde van het grafiekdatapunt terug. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Geeft de groottewaarde van het grafiekdatapunt terug. Wordt gebruikt met Treemap- en Sunburst-grafieken. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Geeft de kleurwaarde van het grafiekdatapunt terug. Wordt gebruikt met Map-grafieken. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Vertegenwoordigt seriefoutbalkwaarden in het geval van Custom waarde-type. Alleen-lezen [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retourneert:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Vertegenwoordigt het label van het grafiekdatapunt. Alleen-lezen [IDataLabel](../../com.aspose.slides/idatalabel).

**Retourneert:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Specificeert dat de bubbels een 3-D-effect hebben. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Specificeert dat de bubbels een 3-D-effect hebben. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. Lezen/Schrijven int.

**Retourneert:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vertegenwoordigt de opmaak-eigenschappen. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Vertegenwoordigt de opmaak-eigenschappen. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Specificeert een datamarker. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retourneert:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert DataPoint uit de grafiekseries.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Geeft een automatische kleur van het datapunt terug op basis van de reeks-index, datapunt-index, ParentSeriesGroup.IsColorVaried eigenschap en grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retourneert:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschappen van het overeenkomende legende-item in het geval van graafoortype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retourneert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Stelt datapunt in als totaal. Toegepast alleen voor Waterfall-reeks.

**Retourneert:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Stelt datapunt in als totaal. Toegepast alleen voor Waterfall-reeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Geeft de container van datapunt-niveaus terug. Toegepast voor Treeamp- en Sunburst-reeksen. Indexering van datapunt-niveaus is nulgebaseerd.

**Retourneert:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bepaalt op welke van de kindcollecties van de ouder dit datapunt van toepassing is. Alleen-lezen long.

**Retourneert:**
long