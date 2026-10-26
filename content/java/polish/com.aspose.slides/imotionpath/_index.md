---
title: IMotionPath
second_title: Aspose.Slides dla Java – referencja API
description: Reprezentuje ścieżkę ruchu.
type: docs
url: /pl/com.aspose.slides/imotionpath/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Reprezentuje ścieżkę ruchu.
## Metody

| Metoda | Opis |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Dodaje nową komendę do ścieżki |
| [getCount()](#getCount--) | Zwraca liczbę ścieżek w kolekcji. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Wstawia nową komendę do ścieżki |
| [clear()](#clear--) | Usuwa wszystkie komendy z kolekcji. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Usuwa określone komendy z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa komendę pod podanym indeksem. |
| [get_Item(int index)](#get-Item-int-) | Zwraca komendę pod podanym indeksem. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Dodaje nową komendę do ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Typ komendy dla zachowania efektu animacji ruchu [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Tablica punktów java.awt.geom.Point2D.Float[] |
| ptsType | int | Typ punktów w ścieżce ruchu animacji [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wskazuje, czy używać współrzędnych względnych, czy nie boolean |

**Zwraca:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Komenda ścieżki [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Zwraca liczbę ścieżek w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Wstawia nową komendę do ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks do wstawienia komendy int |
| type | int | Typ komendy dla zachowania efektu animacji ruchu [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Tablica punktów java.awt.geom.Point2D.Float[] |
| ptsType | int | Typ punktów w ścieżce ruchu animacji [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wskazuje, czy używać współrzędnych względnych, czy nie boolean |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie komendy z kolekcji.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Usuwa określone komendy z kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Ścieżka ruchu do usunięcia [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa komendę pod podanym indeksem.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks do usunięcia komendy int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Zwraca komendę pod podanym indeksem.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Komenda pod podanym indeksem [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)