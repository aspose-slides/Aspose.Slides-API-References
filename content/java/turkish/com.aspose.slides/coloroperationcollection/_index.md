---
title: ColorOperationCollection
second_title: Aspose.Slides for Java API Referansı
description: Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/coloroperationcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [size()](#size--) | Bir koleksiyondaki işlemlerin sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki işlemi döndürür veya ayarlar. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Belirtilen indeksteki işlemi döndürür veya ayarlar. |
| [add(int operation, float parameter)](#add-int-float-) | Yeni bir işlemi koleksiyonun sonuna ekler. |
| [add(int operation)](#add-int-) | Yeni bir işlemi koleksiyonun sonuna ekler. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Yeni işlemi bir koleksiyona ekler. |
| [insert(int position, int operation)](#insert-int-int-) | Yeni işlemi bir koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | Bir koleksiyondan renk işlemini kaldırır. |
| [clear()](#clear--) | Tüm renk işlemlerini kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator'ı döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (istek güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [deepClone()](#deepClone--) | bir ColorOperationCollection koleksiyonunun bir kopyasını oluşturur. |
| [cloneT()](#cloneT--) | Mevcut nesneyi klonlar |

### size() {#size--}
```
public final int size()
```

Bir koleksiyondaki işlemlerin sayısını döndürür. Salt okunur int.

**Döndürür:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Belirtilen indeksteki işlemi döndürür veya ayarlar. Okunur/Yazılabilir [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Belirtilen indeksteki işlemi döndürür veya ayarlar. Okunur/Yazılabilir [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Yeni bir işlemi koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| operation | int | İşlem türü. |
| parameter | float | İşlemin parametresi. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eklenen işlem.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Yeni bir işlemi koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| operation | int | İşlem türü. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eklenen işlem.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Yeni işlemi bir koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| position | int | İşlemin ekleneceği indeks. |
| operation | int | İşlem türü. |
| parameter | float | İşlemin parametresi. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ekleme yapılan işlem.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Yeni işlemi bir koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| position | int | İşlemin ekleneceği indeks. |
| operation | int | İşlem türü. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ekleme yapılan işlem.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Bir koleksiyondan renk işlemini kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak renk işleminin indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Tüm renk işlemlerini kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Koleksiyon içinde yineleme yapılabilen bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Tüm koleksiyon için bir java iterator'ı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Tüm koleksiyon için bir java.util.Iterator.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (istek güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Bir ColorOperationCollection koleksiyonunun bir kopyasını oluşturur.

**Döndürür:**
java.lang.Object - Yeni [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) koleksiyonu.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Mevcut nesneyi klonlar

**Döndürür:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Klon