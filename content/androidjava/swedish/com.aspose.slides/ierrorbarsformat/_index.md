---
title: IErrorBarsFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar felstaplar för diagramserier.
type: docs
url: /sv/com.aspose.slides/ierrorbarsformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Representerar felstaplar för diagramserie. ErrorBars anpassade värden finns i IChartDataPointCollection (i [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) egenskap).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Hämtar eller anger typ av felstaplar. |
| [setType(int value)](#setType-int-) | Hämtar eller anger typ av felstaplar. |
| [getValueType()](#getValueType--) | Representerar möjliga sätt att bestämma längden på felstaplarna. |
| [setValueType(int value)](#setValueType-int-) | Representerar möjliga sätt att bestämma längden på felstaplarna. |
| [hasEndCap()](#hasEndCap--) | Anger att en ändkopp inte ritas på felstaplarna. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Anger att en ändkopp inte ritas på felstaplarna. |
| [getValue()](#getValue--) | Hämtar eller anger värde som används med Fixed, Percentage och StandardDeviation värdetyper för att bestämma längden på felstaplarna. |
| [setValue(float value)](#setValue-float-) | Hämtar eller anger värde som används med Fixed, Percentage och StandardDeviation värdetyper för att bestämma längden på felstaplarna. |
| [getFormat()](#getFormat--) | Representerar formatet för felstaplarna. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representerar formatet för felstaplarna. |
| [isVisible()](#isVisible--) | Hämtar eller anger synlighet för Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger synlighet för Error Bars. |
### getType() {#getType--}
```
public abstract int getType()
```


Hämtar eller anger typ av felstaplar. Läs/skriv [ErrorBarType](../../com.aspose.slides/errorbartype).

**Returnerar:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Hämtar eller anger typ av felstaplar. Läs/skriv [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```


Representerar möjliga sätt att bestämma längden på felstaplarna. Vid anpassad värdetyp för att ange värde använd [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) egenskap för specifik datapunkt i DataPoints-samlingen för serien. Läs/skriv [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Returnerar:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```


Representerar möjliga sätt att bestämma längden på felstaplarna. Vid anpassad värdetyp för att ange värde använd [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) egenskap för specifik datapunkt i DataPoints-samlingen för serien. Läs/skriv [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```


Anger att en ändkopp inte ritas på felstaplarna. Läs/skriv boolean.

**Returnerar:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```


Anger att en ändkopp inte ritas på felstaplarna. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```


Hämtar eller anger värde som används med Fixed, Percentage och StandardDeviation värdetyper för att bestämma längden på felstaplarna. Läs/skriv float.

**Returnerar:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```


Hämtar eller anger värde som används med Fixed, Percentage och StandardDeviation värdetyper för att bestämma längden på felstaplarna. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Representerar formatet för felstaplarna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Representerar formatet för felstaplarna. Läs/skriv [IFormat](../../com.aspose.slides/iformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Hämtar eller anger synlighet för Error Bars. Läs/skriv boolean.

**Returnerar:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Hämtar eller anger synlighet för Error Bars. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |