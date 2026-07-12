---
title: ColorOperationCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/coloroperationcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki işlem sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki işlemi döndürür veya ayarlar. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Belirtilen indeksdeki işlemi döndürür veya ayarlar. |
| [add(int operation, float parameter)](#add-int-float-) | Koleksiyonun sonuna yeni bir işlem ekler. |
| [add(int operation)](#add-int-) | Koleksiyonun sonuna yeni bir işlem ekler. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Yeni işlemi bir koleksiyona ekler. |
| [insert(int position, int operation)](#insert-int-int-) | Yeni işlemi bir koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | Renk işlemini bir koleksiyondan kaldırır. |
| [clear()](#clear--) | Tüm renk işlemlerini kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yinelemeye yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyon erişiminin eşzamanlı (thread-safe) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [deepClone()](#deepClone--) | Bir ColorOperationCollection koleksiyonunun bir kopyasını oluşturur. |
| [cloneT()](#cloneT--) | Mevcut nesneyi klonlar |

### size() {#size--}
```
public final int size()
```

Koleksiyondaki işlem sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Belirtilen indeksdeki işlemi döndürür veya ayarlar. Okunur/yazılabilir [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Belirtilen indeksdeki işlemi döndürür veya ayarlar. Okunur/yazılabilir [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Koleksiyonun sonuna yeni bir işlem ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operation | int | İşlem türü. |
| parameter | float | İşlemin parametresi. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eklenen işlem.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Koleksiyonun sonuna yeni bir işlem ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | int | İşlemin ekleneceği indeks. |
| operation | int | İşlem türü. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ekleme yapılan işlem.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Renk işlemini bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
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

Koleksiyon içinde yinelemeye yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Bir IGenericEnumerator koleksiyon içinde yinelemek için kullanılabilir.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Bir java.util.Iterator tüm koleksiyon için.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyon erişiminin eşzamanlı (thread-safe) olup olmadığını belirten bir değer döndürür. Salt okunur boolean.

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