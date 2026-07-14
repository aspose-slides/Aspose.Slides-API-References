---
title: INormalViewProperties
second_title: Aspose.Slides لـ Android عبر مرجع API للـ Java
description: يمثل خصائص العرض العادي.
type: docs
url: /ar/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، منطقة محتوى جانبية، ومنطقة محتوى سفلية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | يحدد ما إذا كان يجب على التطبيق عرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | يحدد ما إذا كان يجب على التطبيق عرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | يحدد ما إذا كان يجب أن ينتقل فاصل العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | يحدد ما إذا كان يجب أن ينتقل فاصل العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. |
| [getVerticalBarState()](#getVerticalBarState--) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. |
| [getHorizontalBarState()](#getHorizontalBarState--) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. |
| [getPreferSingleView()](#getPreferSingleView--) | يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى وحيدة تعرض على كامل النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى وحيدة تعرض على كامل النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [getRestoredLeft()](#getRestoredLeft--) | يحدد هذا العنصر حجم منطقة المحتوى الجانبية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغرة ولا مكبرة). |
| [getRestoredTop()](#getRestoredTop--) | يحدد هذا العنصر حجم منطقة الشريحة العلوية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغرة ولا مكبرة). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

يحدد ما إذا كان يجب على التطبيق عرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قابل للقراءة والكتابة من نوع boolean.

**الإرجاع:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

يحدد ما إذا كان يجب على التطبيق عرض أيقونات عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قابل للقراءة والكتابة من نوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

يحدد ما إذا كان يجب أن ينتقل فاصل العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. قابل للقراءة والكتابة من نوع boolean.

**الإرجاع:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

يحدد ما إذا كان يجب أن ينتقل فاصل العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. قابل للقراءة والكتابة من نوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. شريط الفاصل العمودي يفصل الشريحة عن منطقة المحتوى الجانبية.

**الإرجاع:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل العمودي. شريط الفاصل العمودي يفصل الشريحة عن منطقة المحتوى الجانبية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**الإرجاع:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

يحدد الحالة التي يجب أن يُعرض فيها شريط الفاصل الأفقي. شريط الفاصل الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى وحيدة تعرض على كامل النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكينه، قد يختار التطبيق عرض إحداها في النافذة بأكملها. قابل للقراءة والكتابة من نوع boolean.

**الإرجاع:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

يحدد ما إذا كان المستخدم يفضل رؤية منطقة محتوى وحيدة تعرض على كامل النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكينه، قد يختار التطبيق عرض إحداها في النافذة بأكملها. قابل للقراءة والكتابة من نوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

يحدد هذا العنصر حجم منطقة المحتوى الجانبية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغرة ولا مكبرة). قراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

يحدد هذا العنصر حجم منطقة الشريحة العلوية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغرة ولا مكبرة). قراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)