---
title: IErrorBarsFormat
second_title: Aspose.Slides for Java API referenciája
description: A diagram sorozat hibasávjait reprezentálja.
type: docs
url: /hu/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

A diagram sorozat hibasávjait reprezentálja. Az ErrorBars egyéni értékei az IChartDataPointCollection-ben vannak (a [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonságban).
## Metódusok

| Metódus | Leírás |
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
| [isVisible()](#isVisible--) | Gets or sets Error Bars visibility. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets Error Bars visibility. |
### getType() {#getType--}
```
public abstract int getType()
```


A hibasáv típusát kapja meg vagy állítja be. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Visszatérési érték:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


A hibasáv típusát kapja meg vagy állítja be. Olvasás/írás [ErrorBarType](../../com.aspose.slides/errorbartype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```


A hibasávok hosszának meghatározásának lehetséges módjait reprezentálja. Egyéni értéktípus esetén az érték megadásához a sorozat DataPoints gyűjteményének adott adatpontjának [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonságát használja. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Visszatérési érték:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```


A hibasávok hosszának meghatározásának lehetséges módjait reprezentálja. Egyéni értéktípus esetén az érték megadásához a sorozat DataPoints gyűjteményének adott adatpontjának [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonságát használja. Olvasás/írás [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```


Megadja, hogy a hibasávokon nincs végelem. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```


Megadja, hogy a hibasávokon nincs végelem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```


A hibasávok hosszának meghatározásához a Fixed, Percentage és StandardDeviation értéktípusokkal használt értéket kapja meg vagy állítja be. Olvasás/írás float.

**Visszatérési érték:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```


A hibasávok hosszának meghatározásához a Fixed, Percentage és StandardDeviation értéktípusokkal használt értéket kapja meg vagy állítja be. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


A hibasávok formátumát reprezentálja. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


A hibasávok formátumát reprezentálja. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


A hibasáv láthatóságát kapja meg vagy állítja be. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


A hibasáv láthatóságát kapja meg vagy állítja be. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |