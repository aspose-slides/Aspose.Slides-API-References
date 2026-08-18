---
title: MotionPath
second_title: Aspose.Slides dla Java - Referencja API
description: Reprezentuje ścieżkę ruchu.
type: docs
url: /pl/com.aspose.slides/motionpath/
---
**Dziedziczenie:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Reprezentuje ścieżkę ruchu.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Dodaj nową komendę do ścieżki |
| [getCount()](#getCount--) | Zwraca liczbę ścieżek w kolekcji. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Wstaw nową komendę do ścieżki |
| [clear()](#clear--) | Usuwa wszystkie komendy z kolekcji. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Usuwa określone komendy z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa komendę pod określonym indeksem. |
| [get_Item(int index)](#get-Item-int-) | Zwraca komendę pod określonym indeksem. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Dodaj nową komendę do ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Tablica punktów |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wartość logiczna określająca współrzędne względne |

**Zwraca:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Zwraca liczbę ścieżek w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Wstaw nową komendę do ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zaczynający się od zera, pod którym element ma zostać wstawiony. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Tablica punktów |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wartość logiczna określająca współrzędne względne |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie komendy z kolekcji.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Usuwa określone komendy z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Ścieżka ruchu do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa komendę pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks komendy, która powinna zostać usunięta. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Zwraca komendę pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Obiekt [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Enumerator IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java.util.Iterator dla całej kolekcji.