---
title: ICaptionsCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة من التعليقات المغلقة.
type: docs
url: /ar/com.aspose.slides/icaptionscollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

يمثل مجموعة من التعليقات المغلقة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد التعليقات المغلقة في الفهرس المحدد. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة من تدفق. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | يزيل التعليقات المغلقة المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل التعليقات المغلقة في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع التعليقات المغلقة من المجموعة. |
| [getCount()](#getCount--) | يعيد عدد العناصر في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

يعيد التعليقات المغلقة في الفهرس المحدد. قراءة فقط [ICaptions](../../com.aspose.slides/icaptions).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | التسمية للتعليقات المغلقة. |
| filePath | java.lang.String | المسار إلى ملف WebVTT. |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions) - المثيل [ICaptions](../../com.aspose.slides/icaptions) المضاف.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

يضيف تعليقات WebVTT المغلقة إلى نهاية المجموعة من تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | التسمية للتعليقات المغلقة. |
| stream | java.io.InputStream | تدفق الإدخال الذي يحتوي على بيانات بصيغة WebVTT. |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions) - المثيل [ICaptions](../../com.aspose.slides/icaptions) المضاف.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

يزيل التعليقات المغلقة المحددة من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | التعليقات المغلقة لإزالتها. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل التعليقات المغلقة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الخاص بالتعليقات المغلقة التي سيتم إزالتها. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع التعليقات المغلقة من المجموعة.

### getCount() {#getCount--}
```
public abstract int getCount()
```

يعيد عدد العناصر في المجموعة. قراءة فقط  int .

**القيمة المرجعة:**
int