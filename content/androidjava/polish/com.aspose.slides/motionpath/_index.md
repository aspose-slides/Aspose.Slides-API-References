---
title: MotionPath
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje ścieżkę ruchu.
type: docs
url: /pl/com.aspose.slides/motionpath/
---
**Dziedziczenie:**  
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**  
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
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Dodaje nowe polecenie do ścieżki |
| [getCount()](#getCount--) | Zwraca liczbę ścieżek w kolekcji. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Wstawia nowe polecenie do ścieżki |
| [clear()](#clear--) | Usuwa wszystkie polecenia z kolekcji. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Usuwa określone polecenia z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa polecenie o podanym indeksie. |
| [get_Item(int index)](#get-Item-int-) | Zwraca polecenie o podanym indeksie. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Dodaje nowe polecenie do ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tablica punktów |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wartość logiczna określająca względne współrzędne |

**Zwraca:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

Zwraca liczbę ścieżek w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Wstawia nowe polecenie do ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym element ma zostać wstawiony. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tablica punktów |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wartość logiczna określająca względne współrzędne |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie polecenia z kolekcji.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

Usuwa określone polecenia z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Ścieżka ruchu do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa polecenie o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks polecenia, które ma zostać usunięte. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

Zwraca polecenie o podanym indeksie.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java.util.Iterator dla całej kolekcji.