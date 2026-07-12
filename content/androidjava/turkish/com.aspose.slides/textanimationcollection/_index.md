---
title: TextAnimationCollection
second_title: Aspose.Slides for Android Java API Referansı
description: Metin animasyonlarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/textanimationcollection/
---
**Miras:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Metin animasyonlarının bir koleksiyonunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki öğelerin sayısını döndürür. |
| [add()](#add--) | Koleksiyona yeni bir metin animasyonu ekler. |
| [get_Item(int index)](#get-Item-int-) | İndeksle öğeyi döndürür. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Tüm öğeleri döndürür |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


Koleksiyondaki öğelerin sayısını döndürür. Salt-okunur int.

**Döndürür:**
int
### add() {#add--}
```
public final TextAnimation add()
```


Koleksiyona yeni bir metin animasyonu ekler.

**Döndürür:**
[TextAnimation](../../com.aspose.slides/textanimation) - Eklendi [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


İndeksle öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


Tüm öğeleri döndürür

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) kaldırmak için. |

**Döndürür:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) dizisi
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


Koleksiyonu yineleyen bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Koleksiyonu yinelemek için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doldurulacak dizi. |
| index | int | Hedef dizideki başlangıç konumu. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object