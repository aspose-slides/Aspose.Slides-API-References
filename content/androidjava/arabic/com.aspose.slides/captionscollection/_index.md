---
title: CaptionsCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يمثل مجموعة من التعليقات المغلقة.
type: docs
url: /ar/com.aspose.slides/captionscollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

يمثل مجموعة من التعليقات المغلقة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد التعليقات المغلقة عند الفهرس المحدد. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة من تدفق. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | يزيل التعليقات المغلقة المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل التعليقات المغلقة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع التعليقات المغلقة من المجموعة. |
| [getCount()](#getCount--) | يعيد عدد العناصر في المجموعة. |
| [iterator()](#iterator--) | يعيد عدادًا يتنقل عبر المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

يعيد التعليقات المغلقة عند الفهرس المحدد. للقراءة فقط [ICaptions](../../com.aspose.slides/icaptions).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | علامة التعليقات المغلقة. |
| filePath | java.lang.String | المسار إلى ملف WebVTT. |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions) - المثيل [ICaptions](../../com.aspose.slides/icaptions) المضاف.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة من تدفق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | علامة التعليقات المغلقة. |
| stream | java.io.InputStream | تدفق الإدخال الذي يحتوي على بيانات بصيغة WebVTT. |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions) - المثيل [ICaptions](../../com.aspose.slides/icaptions) المضاف.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

يزيل التعليقات المغلقة المحددة من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | التعليقات المغلقة التي سيتم إزالتها. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل التعليقات المغلقة عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس التعليقات المغلقة التي سيتم إزالتها. |
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع التعليقات المغلقة من المجموعة.
### getCount() {#getCount--}
```
public final int getCount()
```

يعيد عدد العناصر في المجموعة. للقراءة فقط int .

**القيمة المرجعة:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

يعيد عدادًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - منشئ System.Collections.Generic.IEnumerator1 يمكن استخدامه للتنقل عبر المجموعة.