---
title: IChartDataPoint
second_title: Aspose.Slides Androidhoz Java API referencia
description: A sorozat adatpontját jelöli.
type: docs
url: /hu/com.aspose.slides/ichartdatapoint/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

A sorozat adatpontját jelöli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getXValue()](#getXValue--) | Visszaadja a diagram adatpont x értékét. |
| [getYValue()](#getYValue--) | Visszaadja a diagram adatpont y értékét. |
| [getBubbleSize()](#getBubbleSize--) | Visszaadja a diagram adatpont buborékméretét. |
| [getValue()](#getValue--) | Visszaadja a diagram adatpont értékét. |
| [getSizeValue()](#getSizeValue--) | Visszaadja a diagram adatpont méretértékét. |
| [getColorValue()](#getColorValue--) | Visszaadja a diagram adatpont színértékét. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | A sorozat hibasáv értékeit jelöli egyéni értéktípus esetén. |
| [getLabel()](#getLabel--) | A diagram adatpont címkéjét jelöli. |
| [isBubble3D()](#isBubble3D--) | Azt határozza meg, hogy a buborékokra 3D hatás legyen alkalmazva. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Azt határozza meg, hogy a buborékokra 3D hatás legyen alkalmazva. |
| [getExplosion()](#getExplosion--) | Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kör középpontjától. |
| [setExplosion(int value)](#setExplosion-int-) | Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kör középpontjától. |
| [getFormat()](#getFormat--) | A formázási tulajdonságokat jelöli. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A formázási tulajdonságokat jelöli. |
| [getMarker()](#getMarker--) | Adatjelzőt határoz meg. |
| [remove()](#remove--) | Eltávolítja az adatpontot a diagram sorozatból. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és diagram stílus alapján. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A megfelelő jelmagyarázat bejegyzés tulajdonságai a következő diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Az adatpontot totalként állítja be. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Az adatpontot totalként állítja be. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Azt határozza meg, hogy az adatpont megfordítsa a színeket, ha az érték negatív. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Azt határozza meg, hogy az adatpont megfordítsa a színeket, ha az érték negatív. |
| [getDataPointLevels()](#getDataPointLevels--) | Visszaadja az adatpont szintek tárolóját. |
| [getIndex()](#getIndex--) | Megállapítja, hogy a szülő gyerekgyűjteményének melyik részére vonatkozik ez az adatpont. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Visszaadja a diagram adatpont x értékét. Csak olvasható [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Visszatér:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Visszaadja a diagram adatpont y értékét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Visszaadja a diagram adatpont buborékméretét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Visszaadja a diagram adatpont értékét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

A Treemap és Sunburst diagramoknál használatos. Visszaadja a diagram adatpont méretértékét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Térkép diagramoknál használatos. Visszaadja a diagram adatpont színértékét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

A sorozat hibasáv értékeit jelöli egyéni értéktípus esetén. Csak olvasható [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Visszatér:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

A diagram adatpont címkéjét jelöli. Csak olvasható [IDataLabel](../../com.aspose.slides/idatalabel).

**Visszatér:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Azt határozza meg, hogy a buborékokra 3D hatás legyen alkalmazva. Olvasás/írás boolean.

**Visszatér:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Azt határozza meg, hogy a buborékokra 3D hatás legyen alkalmazva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kör középpontjától. Olvasás/írás int.

**Visszatér:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kör középpontjától. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

A formázási tulajdonságokat jelöli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

A formázási tulajdonságokat jelöli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Adatjelzőt határoz meg. Csak olvasható [IMarker](../../com.aspose.slides/imarker).

**Visszatér:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja az adatpontot a diagram sorozatból.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és diagram stílus alapján. Ez a szín alapértelmezés szerint használatos, ha a FillType értéke NotDefined.

**Visszatér:**
java.lang.Integer - Az adatpont automatikus színe java.lang.Integer

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

A megfelelő jelmagyarázat bejegyzés tulajdonságai a következő diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatér:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Az adatpontot összegként állítja be. Csak a Waterfall sorozattípusra alkalmazható.

**Visszatér:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Az adatpontot összegként állítja be. Csak a Waterfall sorozattípusra alkalmazható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Azt határozza meg, hogy az adatpont megfordítsa a színeket, ha az érték negatív. Olvasás/írás boolean.

**Visszatér:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Azt határozza meg, hogy az adatpont megfordítsa a színeket, ha az érték negatív. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Visszaadja az adatpont szintek tárolóját. A TreeMap és Sunburst sorozatokhoz alkalmazott adatpont szint tárolót ad vissza. Az adatpont szintek indexelése nulláról indul.

**Visszatér:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Megállapítja, hogy a szülő gyerekgyűjteményének melyik részére vonatkozik ez az adatpont. Csak olvasható long.

**Visszatér:**
long