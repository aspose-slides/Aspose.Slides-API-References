---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: يمثل قيمة تعديل الشكل الهندسي.
type: docs
url: /ar/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

يمثل قيمة تعديل الشكل الهندسي. تؤثر هذه القيم على شكل الشكل.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRawValue()](#getRawValue--) | إرجاع أو تعيين قيمة التعديل "كما هي". |
| [setRawValue(long value)](#setRawValue-long-) | إرجاع أو تعيين قيمة التعديل "كما هي". |
| [getAngleValue()](#getAngleValue--) | إرجاع أو تعيين القيمة، مع تفسيرها كزاوية بالدرجات. |
| [setAngleValue(float value)](#setAngleValue-float-) | إرجاع أو تعيين القيمة، مع تفسيرها كزاوية بالدرجات. |
| [getName()](#getName--) | إرجاع اسم هذه القيمة المعدلة. |
| [getType()](#getType--) | إرجاع نوع تعديل الشكل. |

### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

إرجاع أو تعيين قيمة التعديل "كما هي". قراءة/كتابة long.

**القيمة المرجعة:**
long

### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

إرجاع أو تعيين قيمة التعديل "كما هي". قراءة/كتابة long.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

إرجاع أو تعيين القيمة، مع تفسيرها كزاوية بالدرجات. قراءة/كتابة float.

**القيمة المرجعة:**
float

### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

إرجاع أو تعيين القيمة، مع تفسيرها كزاوية بالدرجات. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

إرجاع اسم هذه القيمة المعدلة. قراءة فقط String.

**القيمة المرجعة:**
java.lang.String

### getType() {#getType--}
```
public abstract int getType()
```

إرجاع نوع تعديل الشكل. قراءة فقط [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**القيمة المرجعة:**
int