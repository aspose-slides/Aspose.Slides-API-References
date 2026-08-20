---
title: ColorOperation
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثّل عمليات لون مختلفة تُستخدم في تحويلات اللون.
type: docs
url: /ar/com.aspose.slides/coloroperation/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

يمثل عمليات اللون المختلفة المستخدمة في تحويلات اللون. كائن غير قابل للتغيير.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | ينشئ عملية تحويل لون جديدة. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | ينشئ عملية تحويل لون جديدة. |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getOperationType()](#getOperationType--) | يُرجِع أو يضبط نوع العملية. |
| [getParameter()](#getParameter--) | يُرجِع مُعاملًا لعملية. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدِّد ما إذا كانت نسختا ColorOperation متساويتين. |
| [hashCode()](#hashCode--) | تعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

ينشئ عملية تحويل لون جديدة.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| op | int | نوع العملية. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

ينشئ عملية تحويل لون جديدة.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| op | int | نوع العملية. |
| parameter | float | معامل العملية. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

يُرجِع أو يضبط نوع العملية. قراءة فقط [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**القيمة المرجعة:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

يُرجِع مُعاملًا لعملية. قراءة فقط float.

**القيمة المرجعة:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدِّد ما إذا كانت نسختا ColorOperation متساويتين.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | عملية ColorOperation للمقارنة مع عملية ColorOperation الحالية. |

**القيمة المرجعة:**
boolean - **true** إذا كانت عملية ColorOperation المحددة مساوية لعملية ColorOperation الحالية؛ وإلا، **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

تعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

**القيمة المرجعة:**
int