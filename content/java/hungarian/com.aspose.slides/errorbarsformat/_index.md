---
title: ErrorBarsFormat
second_title: Aspose.Slides Java API Referencia
description: A diagram sorozat hibasávjait képviseli.
type: docs
url: /hu/com.aspose.slides/errorbarsformat/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

A diagram sorozat hibasávjait képviseli. Az ErrorBars egyéni értékei az IChartDataPointCollection (a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonságban) találhatók.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Gets or sets type of error bars. |
| [setType(int value)](#setType-int-) | Gets or sets type of error bars. |
| [getValueType()](#getValueType--) | Represents possible ways to determine the length of the error bars. |
| [setValueType(int value)](#setValueType-int-) | Represents possible ways to determine the length of the error bars. |
| [hasEndCap()](#hasEndCap--) | Specifies an end cap is not drawn on the error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifies an end cap is not drawn on the error bars. |
| [getValue()](#getValue--) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [setValue(float value)](#setValue-float-) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [getFormat()](#getFormat--) | Represents the format of the error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the format of the error bars. |
| [getChart()](#getChart--) | Returns the parent chart. |
| [isVisible()](#isVisible--) | Gets or sets Error Bars visibility . |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets Error Bars visibility . |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

A hibasáv típusát adja vissza vagy állítja be. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Visszatér:**  
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

A hibasáv típusát adja vissza vagy állítja be. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```

A hibasáv hosszának meghatározásának lehetséges módjait képviseli. Egyéni érték típusa esetén az érték megadásához a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonságot kell használni a sorozat DataPoints gyűjteményében lévő adott adatponthoz. Fix, Percentage vagy StandardDeviation érték típusa esetén a Value tulajdonságot kell használni az érték megadásához. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Visszatér:**  
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

A hibasáv hosszának meghatározásának lehetséges módjait képviseli. Egyéni érték típusa esetén az érték megadásához a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonságot kell használni a sorozat DataPoints gyűjteményében lévő adott adatponthoz. Fix, Percentage vagy StandardDeviation érték típusa esetén a Value tulajdonságot kell használni az érték megadásához. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Megadja, hogy a hibasávok végén nincs kapocs rajzolva. Olvasás/írás boolean.

**Visszatér:**  
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Megadja, hogy a hibasávok végén nincs kapocs rajzolva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```

Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float.

**Visszatér:**  
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

A hibasáv formátumát képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**  
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

A hibasáv formátumát képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülő diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**  
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

A hibasávok láthatóságát adja vissza vagy állítja be. Olvasás/írás boolean.

**Visszatér:**  
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

A hibasávok láthatóságát adja vissza vagy állítja be. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diát. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő prezentációt. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation)