---
title: ViewProperties
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: خصائص العرض على مستوى العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/viewproperties/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

خصائص العرض على مستوى العرض التقديمي.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getLastView()](#getLastView--) | يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. |
| [setLastView(int value)](#setLastView-int-) | يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. |
| [getShowComments()](#getShowComments--) | يحدد ما إذا كان يجب إظهار تعليقات الشريحة. |
| [setShowComments(byte value)](#setShowComments-byte-) | يحدد ما إذا كان يجب إظهار تعليقات الشريحة. |
| [getNormalViewProperties()](#getNormalViewProperties--) | يمثل خصائص العرض العادي. |
| [getSlideViewProperties()](#getSlideViewProperties--) | يحدد خصائص العرض المشتركة المرتبطة بوضع عرض الشريحة. |
| [getNotesViewProperties()](#getNotesViewProperties--) | يحدد خصائص العرض المشتركة المرتبطة بوضع عرض الملاحظات. |
| [getGridSpacing()](#getGridSpacing--) | يعيد أو يضبط تباعد الشبكة الذي ينبغي استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | يعيد أو يضبط تباعد الشبكة الذي ينبغي استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. قراءة/كتابة [ViewType](../../com.aspose.slides/viewtype).

**القيمة الراجعة:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

يحدد وضع العرض الذي تم استخدامه عندما تم حفظ مستند العرض التقديمي آخر مرة. قراءة/كتابة [ViewType](../../com.aspose.slides/viewtype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

يحدد ما إذا كان يجب إظهار تعليقات الشريحة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة الراجعة:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

يحدد ما إذا كان يجب إظهار تعليقات الشريحة. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، منطقة محتوى جانبية، ومنطقة محتوى سفلية. قراءة فقط [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**القيمة الراجعة:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

يحدد خصائص العرض المشتركة المرتبطة بوضع عرض الشريحة. قراءة فقط [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**القيمة الراجعة:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

يحدد خصائص العرض المشتركة المرتبطة بوضع عرض الملاحظات. قراءة فقط [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**القيمة الراجعة:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

يعيد أو يضبط تباعد الشبكة الذي ينبغي استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. قراءة/كتابة float.

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

يجب أن تكون قيمة تباعد الشبكة عددًا موجبًا. النطاق النموذجي للقيمة هو من 1 ملم (2.8349607 نقطة) إلى 2 بوصة (144 نقطة).

**القيمة الراجعة:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

يعيد أو يضبط تباعد الشبكة الذي ينبغي استخدامه للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. قراءة/كتابة float.

--------------------

> ```
> يعرض المثال التالي كيفية تغيير تباعد الشبكة في عرض تقديمي لبرنامج PowerPoint.
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

يجب أن تكون قيمة تباعد الشبكة عددًا موجبًا. النطاق النموذجي للقيمة هو من 1 ملم (2.8349607 نقطة) إلى 2 بوصة (144 نقطة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة الراجعة:**
com.aspose.slides.IDOMObject