---
title: IMotionPath
second_title: Aspose.Slides dla Androida poprzez Java API Reference
description: Reprezentuje ścieżkę ruchu.
type: docs
url: /pl/com.aspose.slides/imotionpath/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Reprezentuje ścieżkę ruchu.
## Metody

| Metoda | Opis |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Dodaj nową komendę do ścieżki |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Wstaw nową komendę do ścieżki |
| [clear()](#clear--) | Removes all commands from the collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Removes specified commans from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a command at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Returns a command at the specified index. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Dodaj nową komendę do ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ komendy dla zachowania efektu ruchu animacji [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tablica punktów android.graphics.PointF[] |
| ptsType | int | Typ punktów w ścieżce ruchu animacji [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wskazuje, czy używać współrzędnych względnych czy nie boolean |

**Zwraca:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Komenda ścieżki [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Zwraca liczbę ścieżek w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Wstaw nową komendę do ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks dla wstawiania komendy int |
| type | int | Typ komendy dla zachowania efektu ruchu animacji [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tablica punktów android.graphics.PointF[] |
| ptsType | int | Typ punktów w ścieżce ruchu animacji [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Wskazuje, czy używać współrzędnych względnych czy nie boolean |
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Ścieżka ruchu do usunięcia [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa komendę o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks dla usunięcia komendy int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Zwraca komendę o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Komenda o podanym indeksie [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)