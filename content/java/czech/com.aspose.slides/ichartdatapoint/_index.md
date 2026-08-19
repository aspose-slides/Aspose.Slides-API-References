---
title: IChartDataPoint
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje datový bod řady.
type: docs
url: /cs/com.aspose.slides/ichartdatapoint/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Reprezentuje datový bod řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [getXValue()](#getXValue--) | Vrací hodnotu x datového bodu grafu. |
| [getYValue()](#getYValue--) | Vrací hodnotu y datového bodu grafu. |
| [getBubbleSize()](#getBubbleSize--) | Vrací velikost bubliny datového bodu grafu. |
| [getValue()](#getValue--) | Vrací hodnotu datového bodu grafu. |
| [getSizeValue()](#getSizeValue--) | Vrací hodnotu velikosti datového bodu grafu. |
| [getColorValue()](#getColorValue--) | Vrací hodnotu barvy datového bodu grafu. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje hodnoty chybových pruhů řady v případě typu Custom. |
| [getLabel()](#getLabel--) | Reprezentuje popisek datového bodu grafu. |
| [isBubble3D()](#isBubble3D--) | Určuje, že bubliny mají aplikovaný 3-D efekt. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Určuje, že bubliny mají aplikovaný 3-D efekt. |
| [getExplosion()](#getExplosion--) | Určuje, o kolik má být datový bod posunut od středu koláče. |
| [setExplosion(int value)](#setExplosion-int-) | Určuje, o kolik má být datový bod posunut od středu koláče. |
| [getFormat()](#getFormat--) | Reprezentuje vlastnosti formátování. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje vlastnosti formátování. |
| [getMarker()](#getMarker--) | Určuje značku dat. |
| [remove()](#remove--) | Odstraňuje DataPoint ze série grafu. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Nastaví datový bod jako souhrnný. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Nastaví datový bod jako souhrnný. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že datový bod obrátí své barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že datový bod obrátí své barvy, pokud je hodnota záporná. |
| [getDataPointLevels()](#getDataPointLevels--) | Vrací kontejner úrovní datových bodů. |
| [getIndex()](#getIndex--) | Určuje, ke které kolekci podřízených prvků rodiče se tento datový bod vztahuje. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Vrací hodnotu x datového bodu grafu. Pouze ke čtení [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Vrací:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Vrací hodnotu y datového bodu grafu. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Vrací velikost bubliny datového bodu grafu. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Vrací hodnotu datového bodu grafu. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Vrací hodnotu velikosti datového bodu grafu. Používá se u grafů Treemap a Sunburst. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Vrací hodnotu barvy datového bodu grafu. Používá se u mapových grafů. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Reprezentuje hodnoty chybových pruhů řady v případě typu Custom. Pouze ke čtení [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Vrací:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Reprezentuje popisek datového bodu grafu. Pouze ke čtení [IDataLabel](../../com.aspose.slides/idatalabel).

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Určuje, že bubliny mají aplikovaný 3-D efekt. Čtení/zápis boolean.

**Vrací:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Určuje, že bubliny mají aplikovaný 3-D efekt. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Určuje, o kolik má být datový bod posunut od středu koláče. Čtení/zápis int.

**Vrací:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Určuje, o kolik má být datový bod posunut od středu koláče. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje vlastnosti formátování. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Reprezentuje vlastnosti formátování. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Určuje značku dat. Pouze ke čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Odstraňuje DataPoint ze série grafu.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva se použije jako výchozí, pokud FillType je rovno NotDefined.

**Vrací:**
java.awt.Color - Automatická barva datového bodu java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze ke čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Nastaví datový bod jako souhrnný. Používá se pouze pro typ řady Waterfall.

**Vrací:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Nastaví datový bod jako souhrnný. Používá se pouze pro typ řady Waterfall.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Určuje, že datový bod obrátí své barvy, pokud je hodnota záporná. Čtení/zápis boolean.

**Vrací:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Určuje, že datový bod obrátí své barvy, pokud je hodnota záporná. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Vrací kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů je nulové.

**Vrací:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Určuje, ke které kolekci podřízených prvků rodiče se tento datový bod vztahuje. Pouze ke čtení long.

**Vrací:**
long