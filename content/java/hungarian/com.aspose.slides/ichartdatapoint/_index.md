---
title: IChartDataPoint
second_title: Aspose.Slides Java API hivatkozás
description: Sorozat adatpontot képvisel.
type: docs
url: /hu/com.aspose.slides/ichartdatapoint/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Sorozat adatpontot képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getXValue()](#getXValue--) | Visszaadja a diagram adatpont x értékét. |
| [getYValue()](#getYValue--) | Visszaadja a diagram adatpont y értékét. |
| [getBubbleSize()](#getBubbleSize--) | Visszaadja a diagram adatpont buborék méretét. |
| [getValue()](#getValue--) | Visszaadja a diagram adatpont értékét. |
| [getSizeValue()](#getSizeValue--) | Visszaadja a diagram adatpont méretértékét. |
| [getColorValue()](#getColorValue--) | Visszaadja a diagram adatpont színértékét. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Sorozat hibaoszlop értékeket képvisel egyéni (Custom) értéktípus esetén. |
| [getLabel()](#getLabel--) | A diagram adatpont címkéjét képviseli. |
| [isBubble3D()](#isBubble3D--) | Azt határozza meg, hogy a buborékok 3-D hatással rendelkeznek. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Azt határozza meg, hogy a buborékok 3-D hatással rendelkeznek. |
| [getExplosion()](#getExplosion--) | Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kördiagram középpontjától. |
| [setExplosion(int value)](#setExplosion-int-) | Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kördiagram középpontjától. |
| [getFormat()](#getFormat--) | A formázási tulajdonságokat képviseli. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A formázási tulajdonságokat képviseli. |
| [getMarker()](#getMarker--) | Adatjelölőt határoz meg. |
| [remove()](#remove--) | Eltávolítja a DataPoint-ot a diagram sorozatból. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílus alapján. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A megfelelő jelmagyarázat bejegyzés tulajdonságai a következő diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | A data point-ot összegként állítja be. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | A data point-ot összegként állítja be. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Megadja, hogy a data point negatív érték esetén invertálja a színeit. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Megadja, hogy a data point negatív érték esetén invertálja a színeit. |
| [getDataPointLevels()](#getDataPointLevels--) | Visszaadja a data point szintek konténerét. |
| [getIndex()](#getIndex--) | Meghatározza, hogy a szülő gyerekgyűjteményének melyik elemére vonatkozik ez a data point. |
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

Visszaadja a diagram adatpont buborék méretét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

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

Visszaadja a diagram adatpont méretértékét. Treemap és Sunburst diagramoknál használatos. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Visszaadja a diagram adatpont színértékét. Map diagramoknál használatos. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Sorozat hibaoszlop értékeket képvisel egyéni (Custom) értéktípus esetén. Csak olvasható [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Visszatér:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

A diagram adatpont címkéjét képviseli. Csak olvasható [IDataLabel](../../com.aspose.slides/idatalabel).

**Visszatér:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Azt határozza meg, hogy a buborékok 3-D hatással rendelkeznek. Olvasás/írás boolean.

**Visszatér:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Azt határozza meg, hogy a buborékok 3-D hatással rendelkeznek. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kördiagram középpontjától. Olvasás/írás int.

**Visszatér:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Megadja, hogy a diagram adatpont mennyivel legyen eltolva a kördiagram középpontjától. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

A formázási tulajdonságokat képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

A formázási tulajdonságokat képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Adatjelölőt határoz meg. Csak olvasható [IMarker](../../com.aspose.slides/imarker).

**Visszatér:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a DataPoint-ot a diagram sorozatból.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílus alapján. Ez a szín alapértelmezésként használatos, ha a FillType egyenlő NotDefined.

**Visszatér:**
java.awt.Color - Automatic color of data point java.awt.Color
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

A data point-ot összegként állítja be. Csak Waterfall sorozattípusnál alkalmazható.

**Visszatér:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

A data point-ot összegként állítja be. Csak Waterfall sorozattípusnál alkalmazható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Megadja, hogy a data point negatív érték esetén invertálja a színeit. Olvasás/írás boolean.

**Visszatér:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Megadja, hogy a data point negatív érték esetén invertálja a színeit. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Visszaadja a data point szintek konténerét. Treeamp és Sunburst sorozatoknál alkalmazható. A data point szintek indexelése nulláral kezdődik.

**Visszatér:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Meghatározza, hogy a szülő gyerekgyűjteményének melyik elemére vonatkozik ez a data point. Olvasás long.

**Visszatér:**
long