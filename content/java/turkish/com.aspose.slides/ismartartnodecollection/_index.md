---
title: ISmartArtNodeCollection
second_title: Aspose.Slides for Java API Referansı
description: SmartArt düğümlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ismartartnodecollection/
---
**Tüm Gerçekleştirilen Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

SmartArt düğümlerinin bir koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndekse göre düğüm döndürür. |
| [addNode()](#addNode--) | Yeni düğüm veya alt düğüm ekle. |
| [removeNode(int index)](#removeNode-int-) | Düğümü veya alt düğümü indeksle kaldır. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Düğümü veya alt düğümü kaldır. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Düğüm koleksiyonunda seçilen konuma yeni düğüm ekle. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


İndekse göre düğüm döndürür. Salt okunur [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin sıfır tabanlı indeksi. |

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Yeni düğüm veya alt düğüm ekle.

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Düğümü veya alt düğümü indeksle kaldır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Düğümün sıfır tabanlı indeksi |
### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Düğümü veya alt düğümü kaldır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Kaldırılacak düğüm. |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Düğüm koleksiyonunda seçilen konuma yeni düğüm ekle.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | int | Düğümün sıfır tabanlı konumu. |

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm