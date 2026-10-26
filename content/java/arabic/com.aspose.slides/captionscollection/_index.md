---
title: CaptionsCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من الترجمات المغلقة.
type: docs
url: /ar/com.aspose.slides/captionscollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)  
```
public final class CaptionsCollection implements ICaptionsCollection
```

يمثل مجموعة من الترجمة المغلقة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد الترجمات المغلقة عند الفهرس المحدد. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة من تدفق. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | يزيل الترجمات المغلقة المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل الترجمات المغلقة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع الترجمات المغلقة من المجموعة. |
| [getCount()](#getCount--) | يعيد عدد العناصر في المجموعة. |
| [iterator()](#iterator--) | يعيد عدّادًا يتنقل عبر المجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

يعيد الترجمات المغلقة عند الفهرس المحدد. للقراءة فقط [ICaptions](../../com.aspose.slides/icaptions).

**المعلمة:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[ICaptions](../../com.aspose.slides/icaptions)

### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة.

**المعلمة:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | علامة الترجمات المغلقة. |
| filePath | java.lang.String | المسار إلى ملف WebVTT. |

**الإرجاع:**  
[ICaptions](../../com.aspose.slides/icaptions) - النسخة [ICaptions](../../com.aspose.slides/icaptions) المضافة.

### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

يضيف ترجمات WebVTT المغلقة إلى نهاية المجموعة من تدفق.

**المعلمة:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | java.lang.String | علامة الترجمات المغلقة. |
| stream | java.io.InputStream | تدفق الإدخال الذي يحتوي على بيانات بتنسيق WebVTT. |

**الإرجاع:**  
[ICaptions](../../com.aspose.slides/icaptions) - النسخة [ICaptions](../../com.aspose.slides/icaptions) المضافة.

### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

يزيل الترجمات المغلقة المحددة من المجموعة.

**المعلمة:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | الترجمات المغلقة لإزالتها. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل الترجمات المغلقة عند الفهرس المحدد.

**المعلمة:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس للترجمات المغلقة التي سيتم إزالتها. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع الترجمات المغلقة من المجموعة.

### getCount() {#getCount--}
```
public final int getCount()
```

يعيد عدد العناصر في المجموعة. للقراءة فقط  int .

**الإرجاع:**  
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

يعيد عدّادًا يمكن استخدامه للتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  يمكن استخدامه للتنقل عبر المجموعة.