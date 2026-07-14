---
title: NormalViewProperties
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
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

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | يحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط التفصيلي في أي من مناطق المحتوى في وضع العرض العادي. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | يحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط التفصيلي في أي من مناطق المحتوى في وضع العرض العادي. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | يحدد ما إذا كان الفاصل العمودي يجب أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما يكفى. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | يحدد ما إذا كان الفاصل العمودي يجب أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما يكفى. |
| [getVerticalBarState()](#getVerticalBarState--) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. |
| [getHorizontalBarState()](#getHorizontalBarState--) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. |
| [getPreferSingleView()](#getPreferSingleView--) | يحدد ما إذا كان المستخدم يفضّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | يحدد ما إذا كان المستخدم يفضّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [getRestoredLeft()](#getRestoredLeft--) | هذا العنصر يحدد حجم المنطقة الجانبية للمحتوى في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغيّر (ليس مصغراً ولا مكبّراً). |
| [getRestoredTop()](#getRestoredTop--) | هذا العنصر يحدد حجم منطقة الشريحة العليا في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغيّر (ليس مصغراً ولا مكبّراً). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

يحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط التفصيلي في أي من مناطق المحتوى في وضع العرض العادي. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

يحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط التفصيلي في أي من مناطق المحتوى في وضع العرض العادي. قراءة/كتابة منطقية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

يحدد ما إذا كان الفاصل العمودي يجب أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما يكفى. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

يحدد ما إذا كان الفاصل العمودي يجب أن ينتقل إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما يكفى. قراءة/كتابة منطقية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. شريط الفاصل العمودي يفصل الشريحة عن المنطقة الجانبية للمحتوى.

**الإرجاع:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. شريط الفاصل العمودي يفصل الشريحة عن المنطقة الجانبية للمحتوى.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**الإرجاع:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

يحدد ما إذا كان المستخدم يفضّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم التفعيل، قد يختار التطبيق عرض إحدى مناطق المحتوى في النافذة بأكملها. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

يحدد ما إذا كان المستخدم يفضّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم التفعيل، قد يختار التطبيق عرض إحدى مناطق المحتوى في النافذة بأكملها. قراءة/كتابة منطقية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

هذا العنصر يحدد حجم المنطقة الجانبية للمحتوى في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغيّر (ليس مصغراً ولا مكبّراً). قراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

هذا العنصر يحدد حجم منطقة الشريحة العليا في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغيّر (ليس مصغراً ولا مكبّراً). قراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)