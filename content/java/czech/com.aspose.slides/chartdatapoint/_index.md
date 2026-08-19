---
title: ChartDataPoint
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje datový bod série.
type: docs
url: /cs/com.aspose.slides/chartdatapoint/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Reprezentuje datový bod série.
## Metody

| Metoda | Popis |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Vrací hodnotu velikosti datového bodu grafu. |
| [getColorValue()](#getColorValue--) | Vrací hodnotu barvy datového bodu grafu. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje hodnoty chybových pruhů série v případě typu Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Určuje, že bubliny mají aplikovaný 3-D efekt. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Určuje, že bubliny mají aplikovaný 3-D efekt. |
| [getExplosion()](#getExplosion--) | Určuje množství, o které má být datový bod posunut od středu výseče. |
| [setExplosion(int value)](#setExplosion-int-) | Určuje množství, o které má být datový bod posunut od středu výseče. |
| [getFormat()](#getFormat--) | Reprezentuje vlastnosti formátování. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje vlastnosti formátování. |
| [getMarker()](#getMarker--) | Určuje datový marker. |
| [getSetAsTotal()](#getSetAsTotal--) | Nastavuje datový bod jako celkový. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Nastavuje datový bod jako celkový. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Odstraňuje DataPoint ze série grafu. |
| [getDataPointLevels()](#getDataPointLevels--) | Vrací kontejner úrovní datových bodů. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Vrací automatickou barvu datového bodu na základě indexu série, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. |
| [getActualX()](#getActualX--) | Určuje aktuální x-souřadnici (levá) grafického prvku relativně k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje aktuální horní část grafického prvku relativně k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje aktuální šířku grafického prvku. |
| [getActualHeight()](#getActualHeight--) | Určuje aktuální výšku grafického prvku. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Pouze pro čtení [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Vrací:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Vrací hodnotu velikosti datového bodu grafu. Používá se u grafů Treemap a Sunburst. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Vrací hodnotu barvy datového bodu grafu. Používá se u mapových grafů. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Reprezentuje hodnoty chybových pruhů série v případě typu Custom. Pouze pro čtení [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Vrací:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Pouze pro čtení [IDataLabel](../../com.aspose.slides/idatalabel).

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Určuje, že bubliny mají aplikovaný 3-D efekt. Čtení/zápis boolean.

**Vrací:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Určuje, že bubliny mají aplikovaný 3-D efekt. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Určuje množství, o které má být datový bod posunut od středu výseče. Čtení/zápis int.

**Vrací:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Určuje množství, o které má být datový bod posunut od středu výseče. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje vlastnosti formátování. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Reprezentuje vlastnosti formátování. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Určuje datový marker. Pouze pro čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Nastavuje datový bod jako celkový. Používá se pouze pro typ řady Waterfall.

**Vrací:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Nastavuje datový bod jako celkový. Používá se pouze pro typ řady Waterfall.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Odstraňuje DataPoint ze série grafu.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Vrací kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů je nulové.

**Vrací:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**Vrací:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Vrací automatickou barvu datového bodu na základě indexu série, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva se používá jako výchozí, pokud FillType equals NotDefined.

**Vrací:**
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. Čtení/zápis boolean.

**Vrací:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. Čtení/zápí boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Určuje aktuální x-souřadnici (levá) grafického prvku relativně k levému hornímu rohu grafu. Před získáním aktuálních hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze pro čtení float.

**Vrací:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Určuje aktuální horní část grafického prvku relativně k levému hornímu rohu grafu. Před získáním aktuálních hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze pro čtení float.

**Vrací:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Určuje aktuální šířku grafického prvku. Před získáním aktuálních hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze pro čtení float.

**Vrací:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Určuje aktuální výšku grafického prvku. Před získáním aktuálních hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze pro čtení float.

**Vrací:**
float