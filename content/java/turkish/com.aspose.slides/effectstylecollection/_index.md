---
title: EffectStyleCollection
second_title: Aspose.Slides for Java API Referansı
description: Efekt stillerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/effectstylecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

Efekt stillerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen konumdaki bir öğeyi döndürür. |
| [iterator()](#iterator--) | Koleksiyon boyunca yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [size()](#size--) | Koleksiyondaki öğe sayısını döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

Belirtilen konumdaki bir öğeyi döndürür. Yalnızca okuma [EffectStyle](../../com.aspose.slides/effectstyle).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Öğenin konumu. |

**Dönen Değer:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - Belirtilen konumdaki öğe.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

Koleksiyon boyunca yineleme yapan bir enumerator döndürür.

**Dönen Değer:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Koleksiyon boyunca yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Dönen Değer:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Tüm koleksiyon için bir java.util.Iterator.
### size() {#size--}
```
public final int size()
```

Koleksiyondaki öğe sayısını döndürür. Yalnızca okuma int, Yalnızca okuma int.

**Dönen Değer:**
int
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

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma boolean.

**Dönen Değer:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okuma Object.

**Dönen Değer:**
java.lang.Object