---
title: DrawingGuidesCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Ayarlanabilir çizim kılavuzlarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/drawingguidescollection/
---
**Kalıtım:**  
java.lang.Object

**Tüm Uygulanan Arayüzler:**  
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)  
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Ayarlanabilir çizim kılavuzlarının bir koleksiyonunu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki çizim kılavuzunu döndürür. |
| [add(byte orientation, float position)](#add-byte-float-) | Çizim kılavuzunu koleksiyonun sonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki çizim kılavuzunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getCount()](#getCount--) | Koleksiyondaki öğe sayısını döndürür. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |

### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Belirtilen indeksteki çizim kılavuzunu döndürür. Salt okunur [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**  
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Çizim kılavuzunu koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientation | byte | Çizim kılavuzunun yönelimi. |
| position | float | Çizim kılavuzunun noktalar cinsinden konumu. |

**Döndürür:**  
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indeksteki çizim kılavuzunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılması gereken çizim kılavuzunun indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Tüm koleksiyon için bir java.util.Iterator.

### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki öğe sayısını döndürür. Salt okunur int.

**Döndürür:**  
int

### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |