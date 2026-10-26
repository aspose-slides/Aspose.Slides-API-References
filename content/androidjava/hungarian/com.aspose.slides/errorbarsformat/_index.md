---
title: ErrorBarsFormat
second_title: Aspose.Slides Android számára a Java API hivatkozás
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

A diagram sorozat hibasávjait képviseli. Az ErrorBars egyéni értékei az IChartDataPointCollection-ben találhatók (a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonságban).
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Lekérdezi vagy beállítja a hibasávok típusát. |
| [setType(int value)](#setType-int-) | Lekérdezi vagy beállítja a hibasávok típusát. |
| [getValueType()](#getValueType--) | A hibasávok hosszának meghatározásának lehetséges módjait képviseli. |
| [setValueType(int value)](#setValueType-int-) | A hibasávok hosszának meghatározásának lehetséges módjait képviseli. |
| [hasEndCap()](#hasEndCap--) | Megadja, hogy a hibasávok végén nincs kupak. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Megadja, hogy a hibasávok végén nincs kupak. |
| [getValue()](#getValue--) | Lekérdezi vagy beállítja azt az értéket, amelyet a Fixed, Percentage és StandardDeviation értéktípusokkal a hibasávok hosszának meghatározásához használnak. |
| [setValue(float value)](#setValue-float-) | Lekérdezi vagy beállítja azt az értéket, amelyet a Fixed, Percentage és StandardDeviation értéktípusokkal a hibasávok hosszának meghatározásához használnak. |
| [getFormat()](#getFormat--) | A hibasávok formátumát képviseli. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A hibasávok formátumát képviseli. |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [isVisible()](#isVisible--) | Lekérdezi vagy beállítja a hibasávok láthatóságát . |
| [setVisible(boolean value)](#setVisible-boolean-) | Lekérdezi vagy beállítja a hibasávok láthatóságát . |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülődiát. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülőprezentációját. |
### getType() {#getType--}
```
public final int getType()
```

Lekérdezi vagy beállítja a hibasávok típusát. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Visszatér:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Lekérdezi vagy beállítja a hibasávok típusát. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```

A hibasávok hosszának meghatározásának lehetséges módjait képviseli. Egyedi értéktípus esetén az érték megadásához használd a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonságot a sorozat DataPoints gyűjteményének adott adatpontján. Fixed, Percentage vagy StandardDeviation értéktípus esetén az érték megadásához használd a Value tulajdonságot. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Visszatér:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

A hibasávok hosszának meghatározásának lehetséges módjait képviseli. Egyedi értéktípus esetén az érték megadásához használd a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonságot a sorozat DataPoints gyűjteményének adott adatpontján. Fixed, Percentage vagy StandardDeviation értéktípus esetén az érték megadásához használd a Value tulajdonságot. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Megadja, hogy a hibasávok végén nincs kupak. Olvasás/írás boolean.

**Visszatér:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Megadja, hogy a hibasávok végén nincs kupak. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```

Lekérdezi vagy beállítja azt az értéket, amelyet a Fixed, Percentage és StandardDeviation értéktípusokkal a hibasávok hosszának meghatározásához használnak. Minden más esetben NaN-t ad vissza. Olvasás/írás float.

**Visszatér:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Lekérdezi vagy beállítja azt az értéket, amelyet a Fixed, Percentage és StandardDeviation értéktípusokkal a hibasávok hosszának meghatározásához használnak. Minden más esetben NaN-t ad vissza. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

A hibasávok formátumát képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

A hibasávok formátumát képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

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

Lekérdezi vagy beállítja a hibasávok láthatóságát . Olvasás/írás boolean.

**Visszatér:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Lekérdezi vagy beállítja a hibasávok láthatóságát . Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülődiát. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülőprezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)