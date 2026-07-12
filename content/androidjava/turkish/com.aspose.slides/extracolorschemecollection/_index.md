---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Ek renk şemalarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/extracolorschemecollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Ek renk şemalarının bir koleksiyonunu temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki öğe sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki bir renk şemasını döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | ArrayList erişiminin eşzamanlı (thread safe) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Koleksiyon erişimini eşzamanlamak için kullanılabilecek bir nesne döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki öğe sayısını döndürür. Yalnızca okuma int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Belirtilen indeksdeki bir renk şemasını döndürür. Yalnızca okuma [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Koleksiyon içinde yineleme için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Dizideki başlangıç indeksi. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ArrayList erişiminin eşzamanlı (thread safe) olup olmadığını belirten bir değer döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Koleksiyon erişimini eşzamanlamak için kullanılabilecek bir nesne döndürür. Yalnızca okuma Object.

Eşzamanlama kökünü döndürür. Yalnızca okuma Object.

**Döndürür:**
java.lang.Object