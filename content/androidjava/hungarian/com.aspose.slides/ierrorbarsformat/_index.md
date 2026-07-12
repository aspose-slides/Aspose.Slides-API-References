---
title: IErrorBarsFormat
second_title: Aspose.Slides Android számára Java API hivatkozás
description: A diagram sorozat hibasávjait reprezentálja.
type: docs
url: /hu/com.aspose.slides/ierrorbarsformat/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

A diagram sorozat hibasávjait reprezentálja. Az ErrorBars egyéni értékei az IChartDataPointCollection-ben találhatók (a [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonságban).

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Lekérdezi vagy beállítja a hibasáv típusát. |
| [setType(int value)](#setType-int-) | Lekérdezi vagy beállítja a hibasáv típusát. |
| [getValueType()](#getValueType--) | Képviseli a hibasáv hosszának meghatározásának lehetséges módjait. |
| [setValueType(int value)](#setValueType-int-) | Képviseli a hibasáv hosszának meghatározásának lehetséges módjait. |
| [hasEndCap()](#hasEndCap--) | Megadja, hogy a hibasávokon nem rajzolódik végkapocs. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Megadja, hogy a hibasávokon nem rajzolódik végkapocs. |
| [getValue()](#getValue--) | Lekérdezi vagy beállítja az értéket, amely a Fixed, Percentage és StandardDeviation értéktípusokkal együtt a hibasávok hosszának meghatározásához használatos. |
| [setValue(float value)](#setValue-float-) | Lekérdezi vagy beállítja az értéket, amely a Fixed, Percentage és StandardDeviation értéktípusokkal együtt a hibasávok hosszának meghatározásához használatos. |
| [getFormat()](#getFormat--) | Képviseli a hibasávok formátumát. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Képviseli a hibasávok formátumát. |
| [isVisible()](#isVisible--) | Lekérdezi vagy beállítja a hibasávok láthatóságát. |
| [setVisible(boolean value)](#setVisible-boolean-) | Lekérdezi vagy beállítja a hibasávok láthatóságát. |

### getType() {#getType--}
```
public abstract int getType()
```

Lekérdezi vagy beállítja a hibasáv típusát. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Visszatér:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Lekérdezi vagy beállítja a hibasáv típusát. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Képviseli a hibasáv hosszának meghatározásának lehetséges módjait. Egyedi értéktípus esetén a sorozat DataPoints gyűjteményének adott adatpontjának [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonságával adható meg az érték. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Visszatér:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Képviseli a hibasáv hosszának meghatározásának lehetséges módjait. Egyedi értéktípus esetén a sorozat DataPoints gyűjteményének adott adatpontjának [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonságával adható meg az érték. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Megadja, hogy a hibasávokon nem rajzolódik végkapocs. Olvasás/írás boolean.

**Visszatér:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Megadja, hogy a hibasávokon nem rajzolódik végkapocs. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Lekérdezi vagy beállítja az értéket, amely a Fixed, Percentage és StandardDeviation értéktípusokkal együtt a hibasávok hosszának meghatározásához használatos. Olvasás/írás float.

**Visszatér:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Lekérdezi vagy beállítja az értéket, amely a Fixed, Percentage és StandardDeviation értéktípusokkal együtt a hibasávok hosszának meghatározásához használatos. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Képviseli a hibasávok formátumát. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Képviseli a hibasávok formátumát. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Lekérdezi vagy beállítja a hibasávok láthatóságát. Olvasás/írás boolean.

**Visszatér:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Lekérdezi vagy beállítja a hibasávok láthatóságát. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |