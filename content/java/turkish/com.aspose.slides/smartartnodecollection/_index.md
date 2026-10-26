---
title: SmartArtNodeCollection
second_title: Aspose.Slides for Java API Referansı
description: SmartArt düğümlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/smartartnodecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

SmartArt düğümlerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndekse göre düğüm döndürür |
| [size()](#size--) | Koleksiyondaki düğüm sayısını döndürür. Salt okunur int Salt okunur int . |
| [addNode()](#addNode--) | Yeni bir smart art düğümü veya alt düğüm ekler. |
| [removeNode(int index)](#removeNode-int-) | İndekse göre düğüm veya alt düğüm kaldırır |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Düğüm veya alt düğümü kaldırır |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Düğümler koleksiyonunda seçilen konuma yeni bir düğüm ekler |
| [iterator()](#iterator--) | Koleksiyonun içinde yineleme yapan bir numaralandırıcı döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


İndekse göre düğüm döndürür

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Öğenin sıfır tabanlı indeksi |

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt düğümü
### size() {#size--}
```
public final int size()
```


Koleksiyondaki düğüm sayısını döndürür. Salt okunur int Salt okunur int .

**Döndürür:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


Yeni bir smart art düğümü veya alt düğüm ekler.

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


İndekse göre düğüm veya alt düğüm kaldırır

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Düğümün sıfır tabanlı indeksi |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


Düğüm veya alt düğüm kaldırır

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Kaldırılacak düğüm |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


Düğümler koleksiyonunda seçilen konuma yeni bir düğüm ekler

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Sıfır tabanlı düğüm konumu |

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


Koleksiyonun içinde yineleme yapan bir numaralandırıcı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Koleksiyonun içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. Salt okunur boolean .

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object