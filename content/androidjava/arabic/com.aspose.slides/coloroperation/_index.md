---
title: ColorOperation
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل عمليات لون مختلفة تُستخدم لتحويل الألون.
type: docs
url: /ar/com.aspose.slides/coloroperation/
---
**Inheritance:**  
الوراثة:
java.lang.Object

**All Implemented Interfaces:**  
جميع الواجهات المنفذة:
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

يمثل عمليات لون مختلفة تُستخدم لتحويل الألوان. كائن غير قابل للتغيير.

## Constructors
## المُنشئات

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | ينشئ عملية تحويل لون جديدة. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | ينشئ عملية تحويل لون جديدة. |

## Methods
## الدوال

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | يعيد أو يضبط نوع العملية. |
| [getParameter()](#getParameter--) | يعيد معلمة عملية. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدّد ما إذا كانت مثيلتي ColorOperation متساويتين. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

ينشئ عملية تحويل لون جديدة.

**Parameters:**  
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | نوع العملية. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

ينشئ عملية تحويل لون جديدة.

**Parameters:**  
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | نوع العملية. |
| parameter | float | معلمة العملية. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

يعيد أو يضبط نوع العملية. للقراءة فقط [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Returns:**  
**القيمة المرجعة:**  
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

يعيد معلمة عملية. float للقراءة فقط.

**Returns:**  
**القيمة المرجعة:**  
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدّد ما إذا كانت مثيلتي ColorOperation متساويتين.

**Parameters:**  
**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | الـ ColorOperation للمقارنة مع الـ ColorOperation الحالي. |

**Returns:**  
**القيمة المرجعة:**  
boolean - **true** إذا كان الـ ColorOperation المحدد يساوي الـ ColorOperation الحالي؛ وإلا **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

**Returns:**  
**القيمة المرجعة:**  
int