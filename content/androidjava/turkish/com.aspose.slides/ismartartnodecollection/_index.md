---
title: ISmartArtNodeCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: SmartArt düğümlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ismartartnodecollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

SmartArt düğümlerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Düğümü dizine göre döndürür. |
| [addNode()](#addNode--) | Yeni düğüm veya alt düğüm ekler. |
| [removeNode(int index)](#removeNode-int-) | Düğümü veya alt düğümü dizine göre kaldırır. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Düğümü veya alt düğümü kaldırır. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Seçilen konumda düğüm koleksiyonuna yeni bir düğüm ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Düğümü dizine göre döndürür. Yalnızca okuma [ISmartArtNode](../../com.aspose.slides/ismartartnode)

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

Yeni düğüm veya alt düğüm ekler.

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Düğümü veya alt düğümü dizine göre kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Düğümün sıfır tabanlı indeksi |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Düğümü veya alt düğümü kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Kaldırılacak düğüm. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Seçilen konumda düğüm koleksiyonuna yeni bir düğüm ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | int | Sıfır tabanlı düğüm konumu. |

**Döndürür:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Eklenen düğüm