---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Poskytuje přístup k horním/dolním pruhům čárového nebo akciového grafu.
type: docs
url: /cs/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Poskytuje přístup k horním/dolním pruhům čárového nebo akciového grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Vrací formát horních pruhů. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Vrací formát dolních pruhů. |
| [hasUpDownBars()](#hasUpDownBars--) | Určuje, zda graf obsahuje horní/dolní pruhy. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Určuje, zda graf obsahuje horní/dolní pruhy. |
| [getGapWidth()](#getGapWidth--) | Vrací nebo nastavuje šířku mezery. |
| [setGapWidth(int value)](#setGapWidth-int-) | Vrací nebo nastavuje šířku mezery. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Vrací formát horních pruhů. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Vrací formát dolních pruhů. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Určuje, zda graf obsahuje horní/dolní pruhy. Čtení/zápis boolean.

**Vrací:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Určuje, zda graf obsahuje horní/dolní pruhy. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Vrací nebo nastavuje šířku mezery. Čtení/zápis int.

**Vrací:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Vrací nebo nastavuje šířku mezery. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |