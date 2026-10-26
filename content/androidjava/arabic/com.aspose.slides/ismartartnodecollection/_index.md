---
title: ISmartArtNodeCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من عقد SmartArt.
type: docs
url: /ar/com.aspose.slides/ismartartnodecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

يمثل مجموعة من عقد SmartArt.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع العقدة بحسب الفهرس. |
| [addNode()](#addNode--) | أضف عقدة جديدة أو عقدة فرعية. |
| [removeNode(int index)](#removeNode-int-) | أزل العقدة أو العقدة الفرعية بحسب الفهرس. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | أزل العقدة أو العقدة الفرعية. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | أضف عقدة جديدة في الموضع المحدد لمجموعة العقد. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

يرجع العقدة بحسب الفهرس. قراءة فقط [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر يبدأ من الصفر. |

**الإرجاع:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

أضف عقدة جديدة أو عقدة فرعية.

**الإرجاع:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - العقدة المضافة
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

أزل العقدة أو العقدة الفرعية بحسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العقدة يبدأ من الصفر. |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

أزل العقدة أو العقدة الفرعية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | العقدة لإزالتها. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

أضف عقدة جديدة في الموضع المحدد لمجموعة العقد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | موضع العقدة يبدأ من الصفر. |

**الإرجاع:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - العقدة المضافة