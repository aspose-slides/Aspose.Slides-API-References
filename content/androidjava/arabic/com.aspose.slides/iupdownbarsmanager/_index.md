---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: توفر إمكانية الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي.
type: docs
url: /ar/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

توفر إمكانية الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | إرجاع تنسيق أشرطة الصعود. |
| [getDownBarsFormat()](#getDownBarsFormat--) | إرجاع تنسيق أشرطة الهبوط. |
| [hasUpDownBars()](#hasUpDownBars--) | تحديد ما إذا كان المخطط يحتوي على أشرطة صعود/هبوط. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | تحديد ما إذا كان المخطط يحتوي على أشرطة صعود/هبوط. |
| [getGapWidth()](#getGapWidth--) | إرجاع أو تعيين عرض الفجوة. |
| [setGapWidth(int value)](#setGapWidth-int-) | إرجاع أو تعيين عرض الفجوة. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

إرجاع تنسيق أشرطة الصعود. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

إرجاع تنسيق أشرطة الهبوط. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

تحديد ما إذا كان المخطط يحتوي على أشرطة صعود/هبوط. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

تحديد ما إذا كان المخطط يحتوي على أشرطة صعود/هبوط. قراءة/كتابة منطقية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

إرجاع أو تعيين عرض الفجوة. قراءة/كتابة عدد صحيح.

**الإرجاع:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

إرجاع أو تعيين عرض الفجوة. قراءة/كتابة عدد صحيح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |