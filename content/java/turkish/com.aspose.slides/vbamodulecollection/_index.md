---
title: VbaModuleCollection
second_title: Aspose.Slides için Java API Referansı
description: VBA Projesi modüllerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/vbamodulecollection/
---
**Kalıtım:**  
java.lang.Object

**Uygulanan Tüm Arayüzler:**  
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

VBA Projesi modüllerinin bir koleksiyonunu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekten bulunan öğelerin sayısını alır. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA Projesine yeni boş bir modül ekler. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki öğeyi alır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratör döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekten bulunan öğelerin sayısını alır. **Salt-okunur** int.

**Döndürür:**  
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Koleksiyondan kaldırılacak modül. |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

VBA Projesine yeni boş bir modül ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Modülün adı |

**Döndürür:**  
[IVbaModule](../../com.aspose.slides/ivbamodule) - Eklenen modül.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

Belirtilen indeksdeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**  
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

Koleksiyon içinde yineleme yapan bir enumeratör döndürür.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Tüm koleksiyon için bir java.util.Iterator.
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

Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. **Salt-okunur** boolean.

**Döndürür:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. **Salt-okunur** Object.

**Döndürür:**  
java.lang.Object