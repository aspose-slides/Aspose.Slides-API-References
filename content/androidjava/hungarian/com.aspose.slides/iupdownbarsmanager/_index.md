---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android Java API Referencia
description: Hozzáférést biztosít a vonal- vagy tőzsde-diagram up/down sávjaihoz.
type: docs
url: /hu/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Hozzáférést biztosít a vonal- vagy tőzsde-diagram up/down sávjaihoz.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Visszaadja az up sávok formátumát. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Visszaadja a down sávok formátumát. |
| [hasUpDownBars()](#hasUpDownBars--) | Megállapítja, hogy a diagram rendelkezik-e up/down sávokkal. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Megállapítja, hogy a diagram rendelkezik-e up/down sávokkal. |
| [getGapWidth()](#getGapWidth--) | Visszaadja vagy beállítja a hézag szélességét. |
| [setGapWidth(int value)](#setGapWidth-int-) | Visszaadja vagy beállítja a hézag szélességét. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Visszaadja az up sávok formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Visszaadja a down sávok formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Megállapítja, hogy a diagram rendelkezik-e up/down sávokkal. Olvasás/írás boolean.

**Visszatér:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Megállapítja, hogy a diagram rendelkezik-e up/down sávokkal. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Visszaadja vagy beállítja a hézag szélességét. Olvasás/írás int.

**Visszatér:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Visszaadja vagy beállítja a hézag szélességét. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |