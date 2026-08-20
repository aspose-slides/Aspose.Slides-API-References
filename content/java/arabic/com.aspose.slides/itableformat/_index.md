---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: يمثل تنسيق جدول.
type: docs
url: /ar/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

يمثل تنسيق جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | يعيد كائن خصائص تعبئة الجدول. |
| [getTransparency()](#getTransparency--) | يحصل أو يعيّن شفافية لون التعبئة. |
| [setTransparency(float value)](#setTransparency-float-) | يحصل أو يعيّن شفافية لون التعبئة. |
| [getEffective()](#getEffective--) | يحصل على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

يعيد كائن خصائص تعبئة الجدول. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

يحصل أو يعيّن شفافية لون التعبئة. قراءة/كتابة  float .

**الإرجاع:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

يحصل أو يعيّن شفافية لون التعبئة. قراءة/كتابة  float .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

يحصل على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

**الإرجاع:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - كائن [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).