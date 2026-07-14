---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /ar/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

يمثل قيمة تعديل الشكل الهندسي. تؤثر هذه القيم على شكل الشكل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRawValue()](#getRawValue--) | يعيد أو يضبط قيمة الضبط "كما هي". |
| [setRawValue(long value)](#setRawValue-long-) | يعيد أو يضبط قيمة الضبط "كما هي". |
| [getAngleValue()](#getAngleValue--) | يعيد أو يضبط القيمة، مع تفسيرها كزاوية بالدرجات. |
| [setAngleValue(float value)](#setAngleValue-float-) | يعيد أو يضبط القيمة، مع تفسيرها كزاوية بالدرجات. |
| [getName()](#getName--) | يعيد اسمًا لهذه القيمة الضبطية. |
| [getType()](#getType--) | يعيد نوع تعديل الشكل. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


يعيد أو يضبط قيمة الضبط "كما هي". قراءة/كتابة long.

**الإرجاع:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


يعيد أو يضبط قيمة الضبط "كما هي". قراءة/كتابة long.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


يعيد أو يضبط القيمة، مع تفسيرها كزاوية بالدرجات. قراءة/كتابة float.

**الإرجاع:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


يعيد أو يضبط القيمة، مع تفسيرها كزاوية بالدرجات. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


يعيد اسمًا لهذه القيمة الضبطية. قراءة فقط String.

**الإرجاع:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


يعيد نوع تعديل الشكل. قراءة فقط [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**الإرجاع:**
int