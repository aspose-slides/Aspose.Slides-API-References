---
title: ICaptionsCollection
second_title: مرجع API ل Aspose.Slides للـ Java
description: يمثل مجموعة من الترجمات المغلقة.
type: docs
url: /ar/com.aspose.slides/icaptionscollection/
---
**كل الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

يمثل مجموعة من الترجمات المغلقة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعود الترجمات المغلقة عند الفهرس المحدد. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة من تدفق. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | يزيل الترجمات المغلقة المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل الترجمات المغلقة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع الترجمات المغلقة من المجموعة. |
| [getCount()](#getCount--) | يعيد عدد العناصر في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

يعود الترجمات المغلقة عند الفهرس المحدد. للقراءة فقط [ICaptions](../../com.aspose.slides/icaptions).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | التسمية الخاصة بالترجمات المغلقة. |
| filePath | java.lang.String | المسار إلى ملف WebVTT. |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions) - الكائن [ICaptions](../../com.aspose.slides/icaptions) المضاف.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة من تدفق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | التسمية الخاصة بالترجمات المغلقة. |
| stream | java.io.InputStream | تدفق الإدخال الذي يحتوي على بيانات بتنسيق WebVTT. |

**القيمة المرجعة:**
[ICaptions](../../com.aspose.slides/icaptions) - الكائن [ICaptions](../../com.aspose.slides/icaptions) المضاف.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

يزيل الترجمات المغلقة المحددة من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | الترجمات المغلقة لإزالتها. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل الترجمات المغلقة عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس للترجمات المغلقة التي سيتم إزالتها. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع الترجمات المغلقة من المجموعة.

### getCount() {#getCount--}
```
public abstract int getCount()
```

يعيد عدد العناصر في المجموعة. للقراءة فقط int .

**القيمة المرجعة:**
int