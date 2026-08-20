---
title: CellInvalidReferenceException
second_title: مرجع API لـ Aspose.Slides للغة Java
description: الاستثناء الذي يُرمى عندما يتم اكتشاف مرجع خلية غير صالح.
type: docs
url: /ar/com.aspose.slides/cellinvalidreferenceexception/
---
**الوراثة:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

الاستثناء الذي يُرمى عندما يتم العثور على مرجع خلية غير صالح.
## البناء

| البناء | الوصف |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | يقوم بإنشاء مثيل جديد من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | يقوم بإنشاء مثيل جديد من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | يقوم بإنشاء مثيل جديد من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي سبب هذا الاستثناء. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | يقوم بإنشاء مثيل جديد من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة ومرجع خلية غير صالح. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getReference()](#getReference--) | يحصل على مرجع خلية غير صالح. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

يقوم بإنشاء مثيل جديد من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

يقوم بإنشاء مثيل جديد من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

يقوم بإنشاء مثيل جديد من الفئة [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي سبب هذا الاستثناء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

يقوم بإنشاء مثيل جديد من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة ومرجع خلية غير صالح.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| reference | java.lang.String | مرجع خلية غير صالح. |

### getReference() {#getReference--}
```
public final String getReference()
```

يحصل على مرجع خلية غير صالح.

**الإرجاع:**
java.lang.String