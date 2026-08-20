---
title: NormalViewProperties
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل خصائص العرض العادي.
type: docs
url: /ar/com.aspose.slides/normalviewproperties/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، منطقة محتوى جانبية، ومنطقة محتوى سفلية.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //إنشاء كائن عرض يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | يحدد ما إذا كان يجب على التطبيق عرض الأيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | يحدد ما إذا كان يجب على التطبيق عرض الأيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | يحدد ما إذا كان ينبغي لمقسم العمود الرأسي أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | يحدد ما إذا كان ينبغي لمقسم العمود الرأسي أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. |
| [getVerticalBarState()](#getVerticalBarState--) | يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم العمودي. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم العمودي. |
| [getHorizontalBarState()](#getHorizontalBarState--) | يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم الأفقي. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم الأفقي. |
| [getPreferSingleView()](#getPreferSingleView--) | يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى واحدة تغطي النافذة بالكامل بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى واحدة تغطي النافذة بالكامل بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [getRestoredLeft()](#getRestoredLeft--) | هذا العنصر يحدد حجم المنطقة الجانبية للمحتوى في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغراً ولا مكبراً). |
| [getRestoredTop()](#getRestoredTop--) | هذا العنصر يحدد حجم المنطقة العليا للشريحة في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغراً ولا مكبراً). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

يحدد ما إذا كان يجب على التطبيق عرض الأيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قابل للقراءة والكتابة من نوع Boolean.

**الإرجاع:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

يحدد ما إذا كان يجب على التطبيق عرض الأيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قابل للقراءة والكتابة من نوع Boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

يحدد ما إذا كان ينبغي لمقسم العمود الرأسي أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. قابل للقراءة والكتابة من نوع Boolean.

**الإرجاع:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

يحدد ما إذا كان ينبغي لمقسم العمود الرأسي أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. قابل للقراءة والكتابة من نوع Boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم العمودي. شريط المقسم العمودي يفصل الشريحة عن المنطقة الجانبية للمحتوى.

**الإرجاع:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم العمودي. شريط المقسم العمودي يفصل الشريحة عن المنطقة الجانبية للمحتوى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم الأفقي. شريط المقسم الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**الإرجاع:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

يحدد الحالة التي يجب أن يُظهر فيها شريط المقسم الأفقي. شريط المقسم الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى واحدة تغطي النافذة بالكامل بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. قابل للقراءة والكتابة من نوع Boolean.

**الإرجاع:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى واحدة تغطي النافذة بالكامل بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. قابل للقراءة والكتابة من نوع Boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

هذا العنصر يحدد حجم المنطقة الجانبية للمحتوى في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغراً ولا مكبراً). للقراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

هذا العنصر يحدد حجم المنطقة العليا للشريحة في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغراً ولا مكبراً). للقراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)