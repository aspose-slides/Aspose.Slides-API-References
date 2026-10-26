---
title: CellCircularReferenceException
second_title: مرجع API لجافا لـ Aspose.Slides لنظام Android
description: الاستثناء الذي يُرمى عندما يتم اكتشاف مرجع واحد أو أكثر دائري حيث تشير الصيغة إلى خلية نفسها إما مباشرة أو بشكل غير مباشر.
type: docs
url: /ar/com.aspose.slides/cellcircularreferenceexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

الاستثناء الذي يُرمى عندما يتم اكتشاف مرجع دائري أو أكثر حيث تشير الصيغة إلى خلية نفسها إما مباشرة أو بشكل غير مباشر.
## Constructors

| Constructor | Description |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة ومرجع خلية دائري. |
## Methods

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | يحصل على مرجع خلية دائري. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

يتهيئ نسخة جديدة من الفئة [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) مع رسالة خطأ محددة ومرجع خلية دائري.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| reference | java.lang.String | مرجع خلية دائري. |

### getReference() {#getReference--}
```
public final String getReference()
```

يُعيد مرجع خلية دائري.

**Returns:**
java.lang.String