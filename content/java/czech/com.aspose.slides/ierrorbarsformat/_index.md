---
title: IErrorBarsFormat
second_title: Aspose.Slides pro Java API Reference
description: Představuje chybové úsečky řady grafu.
type: docs
url: /cs/com.aspose.slides/ierrorbarsformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Představuje chybové úsečky řady grafu. Vlastní hodnoty ErrorBars jsou v IChartDataPointCollection (v vlastnosti [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Získává nebo nastavuje typ chybových úseček. |
| [setType(int value)](#setType-int-) | Získává nebo nastavuje typ chybových úseček. |
| [getValueType()](#getValueType--) | Představuje možné způsoby určení délky chybových úseček. |
| [setValueType(int value)](#setValueType-int-) | Představuje možné způsoby určení délky chybových úseček. |
| [hasEndCap()](#hasEndCap--) | Určuje, že na koncích chybových úseček není kreslen koncový prvek. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Určuje, že na koncích chybových úseček není kreslen koncový prvek. |
| [getValue()](#getValue--) | Získává nebo nastavuje hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových úseček. |
| [setValue(float value)](#setValue-float-) | Získává nebo nastavuje hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových úseček. |
| [getFormat()](#getFormat--) | Představuje formát chybových úseček. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Představuje formát chybových úseček. |
| [isVisible()](#isVisible--) | Získává nebo nastavuje viditelnost chybových úseček. |
| [setVisible(boolean value)](#setVisible-boolean-) | Získává nebo nastavuje viditelnost chybových úseček. |

### getType() {#getType--}
```
public abstract int getType()
```

Získává nebo nastavuje typ chybových úseček. Čtení/Zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Vrací:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Získává nebo nastavuje typ chybových úseček. Čtení/Zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Představuje možné způsoby určení délky chybových úseček. V případě vlastního typu hodnoty použijte vlastnost [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) konkrétního datového bodu v kolekci DataPoints řady. Čtení/Zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Vrací:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Představuje možné způsoby určení délky chybových úseček. V případě vlastního typu hodnoty použijte vlastnost [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) konkrétního datového bodu v kolekci DataPoints řady. Čtení/Zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Určuje, že na koncích chybových úseček není kreslen koncový prvek. Čtení/Zápis boolean.

**Vrací:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Určuje, že na koncích chybových úseček není kreslen koncový prvek. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Získává nebo nastavuje hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových úseček. Čtení/Zápis float.

**Vrací:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Získává nebo nastavuje hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation k určení délky chybových úseček. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Představuje formát chybových úseček. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Představuje formát chybových úseček. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Získává nebo nastavuje viditelnost chybových úseček. Čtení/Zápis boolean.

**Vrací:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Získává nebo nastavuje viditelnost chybových úseček. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |