---
title: CellInvalidFormulaException
second_title: مرجع API لـ Aspose.Slides للـ Java
description: الاستثناء الذي يتم إثارته عندما لا تكون الصيغة المحسوبة صحيحة أو لم يتم تحليلها.
type: docs
url: /ar/com.aspose.slides/cellinvalidformulaexception/
---
**الوراثة:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

الاستثناء الذي يتم إثاره عندما لا تكون الصيغة المحسوبة صحيحة أو لم يتم تحليلها.
## المنشئون

| المنشئ | الوصف |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة خلية تحتوي على الصيغة غير الصالحة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getReference()](#getReference--) | يحصل على إشارة خلية تحتوي على الصيغة غير الصالحة. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة نصية تصف الخطأ. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة نصية تصف الخطأ. |
| innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

يقوم بإنشاء مثال جديد من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة خلية تحتوي على الصيغة غير الصالحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة نصية تصف الخطأ. |
| reference | java.lang.String | سلسلة نصية تصف إشارة إلى الاستثناء الداخلي. |

### getReference() {#getReference--}
```
public final String getReference()
```

يحصل على إشارة خلية تحتوي على الصيغة غير الصالحة.

**الإرجاع:**
java.lang.String