---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides for Java API Referansı
description: Ek renk şemalarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/extracolorschemecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Ek renk şemalarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki öğe sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | İndekse göre bir renk şeması döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Koleksiyon içinde dolaşan bir yineleyici döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyonun tüm öğelerini belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | ArrayList'e erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesne döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki öğe sayısını döndürür. Salt-okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

İndekse göre bir renk şeması döndürür. Salt-okunur [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

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

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Koleksiyon içinde dolaşan bir yineleyici döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyonun tüm öğelerini belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Dizideki başlangıç indeksi. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ArrayList'e erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesne döndürür. Salt-okunur Object.

Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object