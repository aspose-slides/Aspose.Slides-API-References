---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation wide view properties.
type: docs
url: /ar/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

خصائص العرض على مستوى العرض التقديمي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLastView()](#getLastView--) | يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. |
| [setLastView(int value)](#setLastView-int-) | يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. |
| [getShowComments()](#getShowComments--) | يحدد ما إذا كان ينبغي إظهار تعليقات الشريحة. |
| [setShowComments(byte value)](#setShowComments-byte-) | يحدد ما إذا كان ينبغي إظهار تعليقات الشريحة. |
| [getSlideViewProperties()](#getSlideViewProperties--) | يحدد خصائص العرض العامة المرتبطة بوضع عرض الشريحة. |
| [getNotesViewProperties()](#getNotesViewProperties--) | يحدد خصائص العرض العامة المرتبطة بوضع عرض الملاحظات. |
| [getNormalViewProperties()](#getNormalViewProperties--) | يمثل خصائص العرض العادي. |
| [getGridSpacing()](#getGridSpacing--) | يرجع أو يحدد تباعد الشبكة الذي يجب استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | يرجع أو يحدد تباعد الشبكة الذي يجب استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. قراءة/كتابة [ViewType](../../com.aspose.slides/viewtype).

**القيمة المرجعة:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. قراءة/كتابة [ViewType](../../com.aspose.slides/viewtype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

يحدد ما إذا كان ينبغي إظهار تعليقات الشريحة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

يحدد ما إذا كان ينبغي إظهار تعليقات الشريحة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

يحدد خصائص العرض العامة المرتبطة بوضع عرض الشريحة. قراءة فقط [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**القيمة المرجعة:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

يحدد خصائص العرض العامة المرتبطة بوضع عرض الملاحظات. قراءة فقط [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**القيمة المرجعة:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، ومنطقة محتوى جانبية، ومنطقة محتوى سفلية. قراءة فقط [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**القيمة المرجعة:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

يرجع أو يحدد تباعد الشبكة الذي يجب استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. قراءة/كتابة float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

يجب أن تكون قيمة تباعد الشبكة عددًا موجبًا. النطاق القيمي النموذجي هو من 1 مم (2.8349607 نقاط) إلى 2 بوصة (144 نقطة).

**القيمة المرجعة:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

يرجع أو يحدد تباعد الشبكة الذي يجب استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. قراءة/كتابة float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

يجب أن تكون قيمة تباعد الشبكة عددًا موجبًا. النطاق القيمي النموذجي هو من 1 مم (2.8349607 نقاط) إلى 2 بوصة (144 نقطة).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |