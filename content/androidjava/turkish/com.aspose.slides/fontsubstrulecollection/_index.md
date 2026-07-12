---
title: FontSubstRuleCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Yazı tipi değiştirme koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/fontsubstrulecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

Yazı tipi değiştirme koleksiyonunu temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekten bulunan elemanların sayısını alır. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | Yeni yazı tipi değiştirme kuralını koleksiyona ekler |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator'ı döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |

### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekten bulunan elemanların sayısını alır. Salt okunur int.

**Döndürür:**
int

### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```

Yeni yazı tipi değiştirme kuralını koleksiyona ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```

Belirli bir nesnenin koleksiyondaki ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Kaldırılacak yazı tipi değiştirme kuralı. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```

Koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Bir IGenericEnumerator, koleksiyon içinde yineleme için kullanılabilir.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

Tüm koleksiyon için bir java iterator'ı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Tüm koleksiyon için bir java.util.Iterator.

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

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object