---
title: CellCircularReferenceException
second_title: مرجع API لـ Aspose.Slides للغة Java
description: الاستثناء الذي يُرمى عندما يتم اكتشاف إشارة دائرية واحدة أو أكثر حيث تُشير صيغة إلى خلية نفسها مباشرةً أو بشكل غير مباشر.
type: docs
url: /ar/com.aspose.slides/cellcircularreferenceexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

الاستثناء الذي يُرمى عندما يتم اكتشاف إشارة دائرية واحدة أو أكثر حيث تُشير صيغة إلى خلية نفسها مباشرةً أو بشكل غير مباشر.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة ومرجع خلية دائري. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getReference()](#getReference--) | يحصل على مرجع خلية دائري. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

إنشاء نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة ومرجع خلية دائري.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| reference | java.lang.String | مرجع خلية دائري. |

### getReference() {#getReference--}
```
public final String getReference()
```

يحصل على مرجع خلية دائري.

**القيمة المرتجعة:**
java.lang.String