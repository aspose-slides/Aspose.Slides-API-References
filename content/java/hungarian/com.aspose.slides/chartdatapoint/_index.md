---
title: ChartDataPoint
second_title: Aspose.Slides Java API-referencia
description: A sorozat adatpontját jelöli.
type: docs
url: /hu/com.aspose.slides/chartdatapoint/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

A sorozat adatpontját jelöli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Visszaadja a diagram adatpont méretértékét. |
| [getColorValue()](#getColorValue--) | Visszaadja a diagram adatpont színértékét. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | A sorozat hibasáv értékeit képviseli egyedi (Custom) értéktípus esetén. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Megadja, hogy a buborékok 3-D hatással rendelkeznek. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Megadja, hogy a buborékok 3-D hatással rendelkeznek. |
| [getExplosion()](#getExplosion--) | Megadja, hogy az adatpont mennyivel legyen eltolva a kör diagram középpontjától. |
| [setExplosion(int value)](#setExplosion-int-) | Megadja, hogy az adatpont mennyivel legyen eltolva a kör diagram középpontjától. |
| [getFormat()](#getFormat--) | A formázási tulajdonságokat jelöli. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A formázási tulajdonságokat jelöli. |
| [getMarker()](#getMarker--) | Megad egy adatjelölőt. |
| [getSetAsTotal()](#getSetAsTotal--) | Az adatpontot összegként állítja be. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Az adatpontot összegként állítja be. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A megfelelő jelmagyarázat bejegyzés tulajdonságai a következő listából származó diagramtípus esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Eltávolítja a DataPoint-ot a diagram sorozatból. |
| [getDataPointLevels()](#getDataPointLevels--) | Visszaadja az adatpont szintek tárolóját. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Visszaad egy automatikus színt az adatponthoz a sorozatindex, adatpontindex, ParentSeriesGroup.IsColorVaried tulajdonság és a diagramstílus alapján. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Megadja, hogy az adatpont megfordítja színeit, ha az érték negatív. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Megadja, hogy az adatpont megfordítja színeit, ha az érték negatív. |
| [getActualX()](#getActualX--) | Megadja a diagramelem tényleges x-helyzetét (bal) a diagram bal felső sarkához képest. |
| [getActualY()](#getActualY--) | Megadja a diagramelem tényleges felső pozícióját a diagram bal felső sarkához képest. |
| [getActualWidth()](#getActualWidth--) | Megadja a diagramelem tényleges szélességét. |
| [getActualHeight()](#getActualHeight--) | Megadja a diagramelem tényleges magasságát. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Csak olvasható [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Visszatér:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Visszaadja a diagram adatpont méretértékét. A Treemap és Sunburst diagramokhoz használható. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Visszaadja a diagram adatpont színértékét. Térképes diagramoknál használható. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


A sorozat hibasáv értékeit képviseli egyedi (Custom) értéktípus esetén. Csak olvasható [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Visszatér:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Csak olvasható [IDataLabel](../../com.aspose.slides/idatalabel).

**Visszatér:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Megadja, hogy a buborékok 3-D hatással rendelkeznek. Olvasható/írható boolean.

**Visszatér:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Megadja, hogy a buborékok 3-D hatással rendelkeznek. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Megadja, hogy az adatpont mennyivel legyen eltolva a kör diagram középpontjától. Olvasható/írható int.

**Visszatér:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Megadja, hogy az adatpont mennyivel legyen eltolva a kör diagram középpontjától. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


A formázási tulajdonságokat jelöli. Olvasható/írható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


A formázási tulajdonságokat jelöli. Olvasható/írható [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Megad egy adatjelölőt. Csak olvasható [IMarker](../../com.aspose.slides/imarker).

**Visszatér:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Az adatpontot összegként állítja be. Csak Waterfall sorozattípus esetén.

**Visszatér:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Az adatpontot összegként állítja be. Csak Waterfall sorozattípus esetén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


A megfelelő jelmagyarázat bejegyzés tulajdonságai a következő listából származó diagramtípus esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatér:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


Eltávolítja a DataPoint-ot a diagram sorozatból.
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Visszaadja az adatpont szintek tárolóját. A Treeamp és Sunburst sorozatoknál alkalmazható. Az adatpont szintek indexelése nullától kezdődik.

**Visszatér:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Visszatér:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```


Visszaad egy automatikus színt az adatponthoz a sorozatindex, adatpontindex, ParentSeriesGroup.IsColorVaried tulajdonság és a diagramstílus alapján. Ez a szín alapértelmezés szerint használatos, ha a FillType egyenlő a NotDefined értékkel.

**Visszatér:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Megadja, hogy az adatpont megfordítja színeit, ha az érték negatív. Olvasható/írható boolean.

**Visszatér:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Megadja, hogy az adatpont megfordítja színeit, ha az érték negatív. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Megadja a diagramelem tényleges x-helyzetét (bal) a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Megadja a diagramelem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Megadja a diagramelem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Megadja a diagramelem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float