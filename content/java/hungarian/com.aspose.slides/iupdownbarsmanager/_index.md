---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Hozzáférést biztosít a vonal- vagy részvény-diagram fel/le sávjaihoz.
type: docs
url: /hu/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Hozzáférést biztosít a vonal- vagy részvény-diagram fel/le sávjaihoz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Visszaadja a fel sávok formátumát. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Visszaadja a le sávok formátumát. |
| [hasUpDownBars()](#hasUpDownBars--) | Megállapítja, hogy a diagram rendelkezik-e fel/le sávokkal. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Megállapítja, hogy a diagram rendelkezik-e fel/le sávokkal. |
| [getGapWidth()](#getGapWidth--) | Visszaadja vagy beállítja a részes szélességet. |
| [setGapWidth(int value)](#setGapWidth-int-) | Visszaadja vagy beállítja a részes szélességet. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Visszaadja a fel sávok formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Visszaadja a le sávok formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Megállapítja, hogy a diagram rendelkezik-e fel/le sávokkal. Olvasható/írható boolean.

**Visszatér:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Megállapítja, hogy a diagram rendelkezik-e fel/le sávokkal. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Visszaadja vagy beállítja a részes szélességet. Olvasható/írható int.

**Visszatér:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Visszaadja vagy beállítja a részes szélességet. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |