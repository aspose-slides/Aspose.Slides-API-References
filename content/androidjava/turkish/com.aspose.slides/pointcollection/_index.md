---
title: PointCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Animasyon noktalarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/pointcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Animasyon noktalarının koleksiyonunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyondaki nokta sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki bir noktayı döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki nokta sayısını döndürür. Yalnızca okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

Belirtilen dizindeki bir noktayı döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Elemanın dizini. |

**Döndürür:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) nesnesi.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Tüm koleksiyon için bir java.util.Iterator.