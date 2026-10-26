---
title: SmartArtNodeCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
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

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع العقدة حسب الفهرس |
| [size()](#size--) | إرجاع عدد العقد في المجموعة للقراءة فقط int للقراءة فقط int . |
| [addNode()](#addNode--) | إضافة عقدة SmartArt جديدة أو عقدة فرعية. |
| [removeNode(int index)](#removeNode-int-) | إزالة العقدة أو العقدة الفرعية حسب الفهرس |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | إزالة العقدة أو العقدة الفرعية |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | إضافة عقدة جديدة في الموضع المحدد في مجموعة العقد |
| [iterator()](#iterator--) | إرجاع مؤّزر يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرّر java للمجموعة الكاملة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذـر التزامن. |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

إرجاع العقدة حسب الفهرس

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر |

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

إزالة العقدة أو العقدة الفرعية حسب الفهرس

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعقدة |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

إزالة العقدة أو العقدة الفرعية

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | العقدة لإزالتها |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

إضافة عقدة جديدة في الموضع المحدد في مجموعة العقد

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | موضع العقدة الصفري |

**الإرجاع:**  
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - العقدة المضافة  

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

إرجاع مؤّزر يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - مؤّزر IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.  

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

إرجاع مكرّر java للمجموعة الكاملة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator للمجموعة الكاملة.  

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة المستهدفة. |
| index | int | الفهرس الابتدائي في المصفوفة المستهدفة. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (thread-safe). للقراءة فقط boolean .

**الإرجاع:**  
boolean  

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذـر التزامن. للقراءة فقط Object.

**الإرجاع:**  
java.lang.Object