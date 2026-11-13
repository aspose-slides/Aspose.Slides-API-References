---
title: IChartDataPoint
second_title: Aspose.Slides for Java API Referencia
description: A sorozat adatpontját jelenti.
type: docs
url: /hu/com.aspose.slides/ichartdatapoint/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

A sorozat adatpontját jelenti.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getXValue()](#getXValue--) | Lekéri a diagram adatpont x értékét. |
| [getYValue()](#getYValue--) | Lekéri a diagram adatpont y értékét. |
| [getBubbleSize()](#getBubbleSize--) | Lekéri a diagram adatpont buborékméretét. |
| [getValue()](#getValue--) | Lekéri a diagram adatpont értékét. |
| [getCachedXValue()](#getCachedXValue--) | Lekéri a diagram adatpont gyorsítótárazott X értékét. |
| [getCachedYValue()](#getCachedYValue--) | Lekéri a diagram adatpont gyorsítótárazott Y értékét. |
| [getCachedValue()](#getCachedValue--) | Lekéri a diagram adatpont gyorsítótárazott értékét. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Lekéri a diagram adatpont gyorsítótárazott buborékméretét. |
| [getSizeValue()](#getSizeValue--) | Lekéri a diagram adatpont méretértékét. |
| [getColorValue()](#getColorValue--) | Lekéri a diagram adatpont színértékét. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | A sorozat hibasáv értékeit reprezentálja egyéni (Custom) értéktípus esetén. |
| [getLabel()](#getLabel--) | A diagram adatpont címkéjét reprezentálja. |
| [isBubble3D()](#isBubble3D--) | Megadja, hogy a buborékok 3D hatással rendelkeznek. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Megadja, hogy a buborékok 3D hatással rendelkeznek. |
| [getExplosion()](#getExplosion--) | Megadja, hogy a diagram adatpont mennyivel kerüljön el a kör diagram középpontjától. |
| [setExplosion(int value)](#setExplosion-int-) | Megadja, hogy a diagram adatpont mennyivel kerüljön el a kör diagram középpontjától. |
| [getFormat()](#getFormat--) | A formázási tulajdonságokat reprezentálja. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A formázási tulajdonságokat reprezentálja. |
| [getMarker()](#getMarker--) | Megad egy adatjelölőt. |
| [remove()](#remove--) | Eltávolítja a DataPoint-ot a diagram sorozatból. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílusa alapján. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A megfelelő jelmagyarázat bejegyzés tulajdonságai az alábbi diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Beállítja az adatpontot összegként. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Beállítja az adatpontot összegként. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Megadja, hogy az adatpont fordítja színeit, ha az érték negatív. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Megadja, hogy az adatpont fordítja színeit, ha az érték negatív. |
| [getDataPointLevels()](#getDataPointLevels--) | Visszaadja az adatpont szintek tárolóját. |
| [getIndex()](#getIndex--) | Meghatározza, hogy a szülő gyermekgyűjteményének melyik elemére vonatkozik ez az adatpont. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Lekéri a diagram adatpont x értékét. Csak olvasható [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Visszatér:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Lekéri a diagram adatpont y értékét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Lekéri a diagram adatpont buborékméretét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Lekéri a diagram adatpont értékét. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

Lekéri a diagram adatpont gyorsítótárazott X értékét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Az összes gyorsítótárazott X érték kiírása a diagram sorozatból.
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
public abstract ICachedChartValue getCachedYValue()
```

Lekéri a diagram adatpont gyorsítótárazott Y értékét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // A diagram sorozat összes gyorsítótárazott Y értékének kiírása.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Lekéri a diagram adatpont gyorsítótárazott értékét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // A diagram sorozat összes gyorsítótárazott értékének kiírása.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

Lekéri a diagram adatpont gyorsítótárazott buborékméretét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // A diagram sorozat összes gyorsítótárazott buborékméret értékének kiírása.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Lekéri a diagram adatpont méretértékét. Treemap és Sunburst diagramoknál használt. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Lekéri a diagram adatpont színértékét. Map diagramoknál használt. Csak olvasható [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Visszatér:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

A sorozat hibasáv értékeit reprezentálja egyéni (Custom) értéktípus esetén. Csak olvasható [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Visszatér:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

A diagram adatpont címkéjét reprezentálja. Csak olvasható [IDataLabel](../../com.aspose.slides/idatalabel).

**Visszatér:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Megadja, hogy a buborékok 3D hatással rendelkeznek. Olvasható/írható boolean.

**Visszatér:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Megadja, hogy a buborékok 3D hatással rendelkeznek. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Megadja, hogy a diagram adatpont mennyivel kerüljön el a kör diagram középpontjától. Olvasható/írható int.

**Visszatér:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Megadja, hogy a diagram adatpont mennyivel kerüljön el a kör diagram középpontjától. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

A formázási tulajdonságokat reprezentálja. Olvasható/írható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

A formázási tulajdonságokat reprezentálja. Olvasható/írható [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Megad egy adatjelölőt. Csak olvasható [IMarker](../../com.aspose.slides/imarker).

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

Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílusa alapján. Ez a szín alapértelmezés szerint akkor használatos, ha a FillType értéke NotDefined.

**Visszatér:**
java.awt.Color - Automatikus szín a data point-hoz java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

A megfelelő jelmagyarázat bejegyzés tulajdonságai az alábbi diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatér:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Beállítja az adatpontot összegként. Csak vízesés (Waterfall) sorozattípusnál használható.

**Visszatér:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Beállítja az adatpontot összegként. Csak vízesés (Waterfall) sorozattípusnál használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Megadja, hogy az adatpont fordítja színeit, ha az érték negatív. Olvasható/írható boolean.

**Visszatér:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Megadja, hogy az adatpont fordítja színeit, ha az érték negatív. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Visszaadja az adatpont szintek tárolóját. TreeMap és Sunburst sorozatoknál használható. Az adatpont szintek indexelése nullával kezdődik.

**Visszatér:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Meghatározza, hogy a szülő gyermekgyűjteményének melyik elemére vonatkozik ez az adatpont. Olvasható long.

**Visszatér:**
long