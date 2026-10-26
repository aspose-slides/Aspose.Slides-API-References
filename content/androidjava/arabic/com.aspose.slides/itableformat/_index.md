---
title: ITableFormat
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل تنسيق جدول.
type: docs
url: /ar/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

يمثل تنسيق جدول.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | يرجع كائن خصائص تعبئة الجدول. |
| [getTransparency()](#getTransparency--) | يحصل على شفافية لون التعبئة أو يضبطها. |
| [setTransparency(float value)](#setTransparency-float-) | يحصل على شفافية لون التعبئة أو يضبطها. |
| [getEffective()](#getEffective--) | يحصل على خصائص تنسيق الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


يرجع كائن خصائص تعبئة الجدول. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


يحصل على شفافية لون التعبئة أو يضبطها. قراءة/كتابة  float .

**الإرجاع:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


يحصل على شفافية لون التعبئة أو يضبطها. قراءة/كتابة  float .

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
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - عنصر [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).