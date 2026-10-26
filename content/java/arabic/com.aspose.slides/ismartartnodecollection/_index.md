---
title: ISmartArtNodeCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: تمثل مجموعة من عقد SmartArt.
type: docs
url: /ar/com.aspose.slides/ismartartnodecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

تمثل مجموعة من عقد SmartArt.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع العقدة حسب الفهرس. |
| [addNode()](#addNode--) | إضافة عقدة جديدة أو عقدة فرعية. |
| [removeNode(int index)](#removeNode-int-) | إزالة عقدة أو عقدة فرعية حسب الفهرس. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | إزالة عقدة أو عقدة فرعية. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | إضافة عقدة جديدة في الموضع المحدد من مجموعة العقد. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


إرجاع العقدة حسب الفهرس. للقراءة فقط [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر. |

**القيمة المرجعة:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


إضافة عقدة جديدة أو عقدة فرعية.

**القيمة المرجعة:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - عقدة مضافة
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


إزالة عقدة أو عقدة فرعية حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعقدة |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


إزالة عقدة أو عقدة فرعية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | العقدة المراد إزالتها. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


إضافة عقدة جديدة في الموضع المحدد من مجموعة العقد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | موضع العقدة الصفري. |

**القيمة المرجعة:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - عقدة مضافة