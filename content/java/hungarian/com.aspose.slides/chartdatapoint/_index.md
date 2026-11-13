---
title: ChartDataPoint
second_title: Aspose.Slides Java API hivatkozás
description: A sorozat adatpontját képviseli.
type: docs
url: /hu/com.aspose.slides/chartdatapoint/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

A sorozat adatpontját képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Visszaadja a diagram adatpont méretértékét. |
| [getColorValue()](#getColorValue--) | Visszaadja a diagram adatpont színértékét. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | A sorozat hibasáv értékeket képviseli egyéni értéktípus esetén. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Megadja, hogy a buborékok 3-D hatással rendelkeznek. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Megadja, hogy a buborékok 3-D hatással rendelkeznek. |
| [getExplosion()](#getExplosion--) | Megadja, hogy mennyivel kerül a adatpont a kör középpontjából. |
| [setExplosion(int value)](#setExplosion-int-) | Megadja, hogy mennyivel kerül a adatpont a kör középpontjából. |
| [getFormat()](#getFormat--) | A formázási tulajdonságokat képviseli. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A formázási tulajdonságokat képviseli. |
| [getMarker()](#getMarker--) | Megad egy adatjelölőt. |
| [getSetAsTotal()](#getSetAsTotal--) | Az adatpontot összegként állítja be. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Az adatpontot összegként állítja be. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A megfelelő jelmagyarázat bejegyzés tulajdonságai a következő listából származó diagramtípus esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Eltávolítja a DataPoint-ot a diagram sorozatból. |
| [getDataPointLevels()](#getDataPointLevels--) | Visszaadja az adatpont szintek tárolóját. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílusa alapján. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Megadja, hogy az adatpont megfordítja a színeket, ha az érték negatív. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Megadja, hogy az adatpont megfordítja a színeket, ha az érték negatív. |
| [getCachedValue()](#getCachedValue--) | Lekéri egy diagram adatpont gyorsítótárazott értékét. |
| [getCachedXValue()](#getCachedXValue--) | Lekéri egy diagram adatpont gyorsítótárazott X értékét. |
| [getCachedYValue()](#getCachedYValue--) | Lekéri egy diagram adatpont gyorsítótárazott Y értékét. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Lekéri egy diagram adatpont gyorsítótárazott buborékméretét. |
| [getActualX()](#getActualX--) | Megadja a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest. |
| [getActualY()](#getActualY--) | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. |
| [getActualWidth()](#getActualWidth--) | Megadja a diagram elem tényleges szélességét. |
| [getActualHeight()](#getActualHeight--) | Megadja a diagram elem tényleges magasságát. |

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

Visszaadja a diagram adatpont méretértékét. Treemap és Sunburst diagramoknál használható. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Visszaadja a diagram adatpont színértékét. Map diagramoknál használható. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

A sorozat hibasáv értékeket képviseli egyéni értéktípus esetén. Csak olvasható [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

Megadja, hogy mennyivel kerül a adatpont a kör középpontjából. Olvasható/írható int.

**Visszatér:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Megadja, hogy mennyivel kerül a adatpont a kör középpontjából. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

A formázási tulajdonságokat képviseli. Olvasható/írható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

A formázási tulajdonságokat képviseli. Olvasható/írható [IFormat](../../com.aspose.slides/iformat).

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

Az adatpontot összegként állítja be. Csak Waterfall sorozattípusra alkalmazható.

**Visszatér:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Az adatpontot összegként állítja be. Csak Waterfall sorozattípusra alkalmazható.

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

Visszaadja az adatpont szintek tárolóját. Treeamp és Sunburst sorozatoknál alkalmazható. A szintek indexelése 0-tól indul.

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

Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílusa alapján. Ez a szín alapértelmezés szerint használatos, ha a FillType NotDefined.

**Visszatér:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Megadja, hogy az adatpont megfordítja a színeket, ha az érték negatív. Olvasható/írható boolean.

**Visszatér:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Megadja, hogy az adatpont megfordítja a színeket, ha az érték negatív. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Lekéri egy diagram adatpont gyorsítótárazott értékét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Írja ki a diagram sorozat összes gyorsítótárazott értékét.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Lekéri egy diagram adatpont gyorsítótárazott X értékét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Írja ki a diagram sorozat összes gyorsítótárazott X értékét.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

Lekéri egy diagram adatpont gyorsítótárazott Y értékét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Írja ki a diagram sorozat összes gyorsítótárazott Y értékét.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Lekéri egy diagram adatpont gyorsítótárazott buborékméretét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Írja ki a diagram sorozat összes gyorsítótárazott buborékméret értékét.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Megadja a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Megadja a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Megadja a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float