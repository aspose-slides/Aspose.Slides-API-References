---
title: SmartArtNodeCollection
second_title: Aspose.Slides for Android via Java API Referansı
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

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndeks ile düğümü döndürür |
| [size()](#size--) | Koleksiyondaki düğümlerin sayısını döndürür Yalnızca okuma int Yalnızca okuma int |
| [addNode()](#addNode--) | Yeni bir akıllı sanat düğümü veya alt düğüm ekler. |
| [removeNode(int index)](#removeNode-int-) | Düğümü veya alt düğümü indeksle kaldırır |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Düğümü veya alt düğümü kaldırır |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Düğümler koleksiyonunda seçilen konuma yeni bir düğüm ekler |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

İndeks ile düğümü döndürür

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Ögenin sıfır tabanlı indeksi |

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt düğümü

### size() {#size--}
```
public final int size()
```

Koleksiyondaki düğümlerin sayısını döndürür Yalnızca okuma int Yalnızca okuma int.

**Döndürür:**
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Yeni bir akıllı sanat düğümü veya alt düğüm ekler.

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm

### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Düğümü veya alt düğümü indeksle kaldırır

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Düğümün sıfır tabanlı indeksi |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Düğümü veya alt düğümü kaldırır

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Kaldırılacak düğüm |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Düğümler koleksiyonunda seçilen konuma yeni bir düğüm ekler

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| position | int | Düğümün sıfır tabanlı konumu |

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Tüm koleksiyon için bir java.util.Iterator

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

Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okuma Object.

**Döndürür:**
java.lang.Object