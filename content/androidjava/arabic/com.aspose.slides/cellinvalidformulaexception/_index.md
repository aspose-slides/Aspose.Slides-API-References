---
title: CellInvalidFormulaException
second_title: مرجع API لجافا لـ Aspose.Slides لنظام Android
description: الاستثناء الذي يُرمى عندما تكون الصيغة المحسوبة غير صحيحة أو لم يتم تحليلها.
type: docs
url: /ar/com.aspose.slides/cellinvalidformulaexception/
---
**الوراثة:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

الاستثناء الذي يُرمى عندما تكون الصيغة المحسوبة غير صحيحة أو لم يتم تحليلها.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | يإنشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | يإنشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | يإنشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | يإنشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة خلية تحتوي على الصيغة غير الصالحة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getReference()](#getReference--) | يحصل على إشارة خلية تحتوي على الصيغة غير الصالحة. |

### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

ينشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

ينشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

ينشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة إلى الاستثناء الداخلي الذي هو سبب هذا الاستثناء.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| innerException | java.lang.RuntimeException | الاستثناء الذي هو سبب الاستثناء الحالي. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

ينشئ نسخة جديدة من الفئة [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) مع رسالة خطأ محددة وإشارة خلية تحتوي على الصيغة غير الصالحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | سلسلة تصف الخطأ. |
| reference | java.lang.String | سلسلة تصف إشارة إلى الاستثناء الداخلي. |

### getReference() {#getReference--}
```
public final String getReference()
```

يحصل على إشارة خلية تحتوي على الصيغة غير الصالحة.

**القيمة المرجعة:**
java.lang.String