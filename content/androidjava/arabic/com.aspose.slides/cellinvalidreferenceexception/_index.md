---
title: CellInvalidReferenceException
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: الاستثناء الذي يُرمى عندما يتم اكتشاف إشارة خلية غير صالحة.
type: docs
url: /ar/com.aspose.slides/cellinvalidreferenceexception/
---
**الوراثة:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

الاستثناء الذي يُرمى عندما يتم العثور على إشارة خلية غير صالحة.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | تهيء نسخة جديدة من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | تهيء نسخة جديدة من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | تهيء نسخة جديدة من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي سبب هذا الاستثناء. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | تهيء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة وإشارة خلية غير صالحة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getReference()](#getReference--) | يحصل على إشارة خلية غير صالحة. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

تهيء نسخة جديدة من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

تهيء نسخة جديدة من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | نص يصف الخطأ. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

تهيء نسخة جديدة من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي سبب هذا الاستثناء.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | نص يصف الخطأ. |
| innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

تهيء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة وإشارة خلية غير صالحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | نص يصف الخطأ. |
| reference | java.lang.String | إشارة خلية غير صالحة. |

### getReference() {#getReference--}
```
public final String getReference()
```

يحصل على إشارة خلية غير صالحة.

**القيمة المرجعة:**
java.lang.String