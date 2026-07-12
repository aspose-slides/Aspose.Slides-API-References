---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Ayarlanabilir çizim kılavuzlarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Ayarlanabilir çizim kılavuzlarının bir koleksiyonunu temsil eder.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Çizim kılavuzunu indeksine göre döndürür. |
| [add(byte orientation, float position)](#add-byte-float-) | Çizim kılavuzunu koleksiyonun sonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki çizim kılavuzunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm öğelerin sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Çizim kılavuzunu indeksine göre döndürür. Yalnızca okunabilir [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Çizim kılavuzunu koleksiyonun sonuna ekler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientation | byte | Çizim kılavuzunun yönlendirmesi. |
| position | float | Çizim kılavuzunun noktalar cinsinden konumu. |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksdeki çizim kılavuzunu kaldırır.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Silinmesi gereken çizim kılavuzunun indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki tüm öğelerin sayısını alır. Yalnızca okunabilir int.

**Returns:**
int