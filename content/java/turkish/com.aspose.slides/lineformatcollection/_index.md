---
title: LineFormatCollection
second_title: Aspose.Slides for Java API Referansı
description: Satır stillerinin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/lineformatcollection/
---
**Kalıtım:**  
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**  
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)  
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

Satır stillerinin koleksiyonunu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir numaralandırıcı döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
| [size()](#size--) | Koleksiyonda gerçekten bulunan öğe sayısını alır. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm öğeleri koleksiyondan belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |

### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```

Belirtilen dizindeki öğeyi alır. Yalnızca okunabilir [ILineFormat](../../com.aspose.slides/ilineformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```

Koleksiyonu yineleyen bir numaralandırıcı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```

Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - Tüm koleksiyon için bir java.util.Iterator.

### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekten bulunan öğe sayısını alır. Yalnızca okunabilir int.

**Döndürür:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Tüm öğeleri koleksiyondan belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç dizini. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

**Döndürür:**
java.lang.Object