---
title: SmartArtNodeCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من عقد SmartArt.
type: docs
url: /ar/com.aspose.slides/smartartnodecollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

يمثل مجموعة من عقد SmartArt.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع العقدة حسب الفهرس |
| [size()](#size--) | إرجاع عدد العقد في المجموعة للقراءة فقط int للقراءة فقط int . |
| [addNode()](#addNode--) | إضافة عقدة SmartArt جديدة أو عقدة فرعية. |
| [removeNode(int index)](#removeNode-int-) | إزالة عقدة أو عقدة فرعية حسب الفهرس |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | إزالة عقدة أو عقدة فرعية |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | إضافة عقدة جديدة في الموضع المحدد من مجموعة العقد |
| [iterator()](#iterator--) | إرجاع Enumerator يتجول في المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع Iterator جافا للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر التزامن. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

إرجاع العقدة حسب الفهرس

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر |

**الإرجاع:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - عقدة SmartArt
### size() {#size--}
```
public final int size()
```

إرجاع عدد العقد في المجموعة للقراءة فقط int للقراءة فقط int .

**الإرجاع:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

إضافة عقدة SmartArt جديدة أو عقدة فرعية.

**الإرجاع:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - العقدة المضافة
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

إزالة عقدة أو عقدة فرعية حسب الفهرس

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العقدة القائم على الصفر |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

إزالة عقدة أو عقدة فرعية

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | العقدة التي ستُزال |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

إضافة عقدة جديدة في الموضع المحدد من مجموعة العقد

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | موضع العقدة القائم على الصفر |

**الإرجاع:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - العقدة المضافة
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

إرجاع Enumerator يتجول في المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

إرجاع Iterator جافا للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). للقراءة فقط boolean .

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر التزامن. للقراءة فقط Object.

**الإرجاع:**
java.lang.Object