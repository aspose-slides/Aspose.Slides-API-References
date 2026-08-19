---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Fornisce l'accesso alle barre ascendenti/descendenti di un grafico a linee o a candele.
type: docs
url: /it/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Fornisce l'accesso alle barre ascendenti/descendenti di Line- o Stock-chart.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Restituisce il formato delle barre ascendenti. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Restituisce il formato delle barre discendenti. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina se il grafico ha barre ascendenti/descendenti. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Determina se il grafico ha barre ascendenti/descendenti. |
| [getGapWidth()](#getGapWidth--) | Restituisce o imposta la larghezza del gap. |
| [setGapWidth(int value)](#setGapWidth-int-) | Restituisce o imposta la larghezza del gap. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Restituisce il formato delle barre ascendenti. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Restituisce il formato delle barre discendenti. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Determina se il grafico ha barre ascendenti/descendenti. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Determina se il grafico ha barre ascendenti/descendenti. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Restituisce o imposta la larghezza del gap. Lettura/Scrittura int.

**Restituisce:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Restituisce o imposta la larghezza del gap. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |