---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Fornisce l'accesso alle barre su/giù di un grafico a linee o a barre.
type: docs
url: /it/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Fornisce l'accesso alle barre su/giù di un grafico a linee o a barre.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Restituisce il formato delle barre su. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Restituisce il formato delle barre giù. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina se il grafico ha barre su/giù. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Determina se il grafico ha barre su/giù. |
| [getGapWidth()](#getGapWidth--) | Restituisce o imposta la larghezza dello spazio. |
| [setGapWidth(int value)](#setGapWidth-int-) | Restituisce o imposta la larghezza dello spazio. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Restituisce il formato delle barre su. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Restituisce il formato delle barre giù. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Determina se il grafico ha barre su/giù. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Determina se il grafico ha barre su/giù. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Restituisce o imposta la larghezza dello spazio. Lettura/scrittura int.

**Restituisce:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Restituisce o imposta la larghezza dello spazio. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |