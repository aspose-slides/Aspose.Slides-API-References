---
title: IErrorBarsFormat
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje chybové pruhy řady grafu.
type: docs
url: /cs/com.aspose.slides/ierrorbarsformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property).

## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Získá nebo nastaví typ chybových pruhů. |
| [setType(int value)](#setType-int-) | Získá nebo nastaví typ chybových pruhů. |
| [getValueType()](#getValueType--) | Zobrazuje možné způsoby určení délky chybových pruhů. |
| [setValueType(int value)](#setValueType-int-) | Zobrazuje možné způsoby určení délky chybových pruhů. |
| [hasEndCap()](#hasEndCap--) | Určuje, že koncová čepka není vykreslena na chybových pruzích. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Určuje, že koncová čepka není vykreslena na chybových pruzích. |
| [getValue()](#getValue--) | Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation pro určení délky chybových pruhů. |
| [setValue(float value)](#setValue-float-) | Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation pro určení délky chybových pruhů. |
| [getFormat()](#getFormat--) | Zobrazuje formát chybových pruhů. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Zobrazuje formát chybových pruhů. |
| [isVisible()](#isVisible--) | Získá nebo nastaví viditelnost chybových pruhů. |
| [setVisible(boolean value)](#setVisible-boolean-) | Získá nebo nastaví viditelnost chybových pruhů. |

### getType() {#getType--}
```
public abstract int getType()
```

Získá nebo nastaví typ chybových pruhů. Čtení/zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Návratová hodnota:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Získá nebo nastaví typ chybových pruhů. Čtení/zápis [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Zobrazuje možné způsoby určení délky chybových pruhů. V případě vlastního typu hodnoty použijte vlastnost [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) konkrétního datového bodu v kolekci DataPoints série. Čtení/zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Návratová hodnota:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Zobrazuje možné způsoby určení délky chybových pruhů. V případě vlastního typu hodnoty použijte vlastnost [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) konkrétního datového bodu v kolekci DataPoints série. Čtení/zápis [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Určuje, že koncová čepka není vykreslena na chybových pruzích. Čtení/zápis boolean.

**Návratová hodnota:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Určuje, že koncová čepka není vykreslena na chybových pruzích. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation pro určení délky chybových pruhů. Čtení/zápis float.

**Návratová hodnota:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Získá nebo nastaví hodnotu, která se používá s typy hodnot Fixed, Percentage a StandardDeviation pro určení délky chybových pruhů. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Zobrazuje formát chybových pruhů. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Návratová hodnota:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Zobrazuje formát chybových pruhů. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Získá nebo nastaví viditelnost chybových pruhů. Čtení/zápis boolean.

**Návratová hodnota:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Získá nebo nastaví viditelnost chybových pruhů. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
