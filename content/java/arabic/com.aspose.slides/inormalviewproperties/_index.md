---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: يمثل خصائص العرض العادي.
type: docs
url: /ar/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

يمثل خصائص العرض العادي. يتكون العرض العادي من ثلاث مناطق محتوى: الشريحة نفسها، ومنطقة محتوى جانبية، ومنطقة محتوى سفلية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | تحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | تحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | تحدد ما إذا كان من المفترض أن يتم تثبيت القسام العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | تحدد ما إذا كان من المفترض أن يتم تثبيت القسام العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. |
| [getVerticalBarState()](#getVerticalBarState--) | تحدد الحالة التي يجب أن يُظهر فيها شريط القسام العمودي. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | تحدد الحالة التي يجب أن يُظهر فيها شريط القسام العمودي. |
| [getHorizontalBarState()](#getHorizontalBarState--) | تحدد الحالة التي يجب أن يُظهر فيها شريط القسام الأفقي. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | تحدد الحالة التي يجب أن يُظهر فيها شريط القسام الأفقي. |
| [getPreferSingleView()](#getPreferSingleView--) | تحدد ما إذا كان المستخدم يفضِّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | تحدد ما إذا كان المستخدم يفضِّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. |
| [getRestoredLeft()](#getRestoredLeft--) | تحدد هذه العنصر حجم منطقة المحتوى الجانبية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغّرًا ولا مكبَّرًا). |
| [getRestoredTop()](#getRestoredTop--) | تحدد هذه العنصر حجم منطقة الشريحة العلوية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغّرًا ولا مكبَّرًا). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

تحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

تحدد ما إذا كان يجب على التطبيق إظهار الرموز عند عرض محتوى المخطط في أي من مناطق المحتوى في وضع العرض العادي. قراءة/كتابة boolean.

**الوسائط:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

تحدد ما إذا كان من المفترض أن يتم تثبيت القسام العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

تحدد ما إذا كان من المفترض أن يتم تثبيت القسام العمودي إلى حالة مصغرة عندما تكون المنطقة الجانبية صغيرة بما فيه الكفاية. قراءة/كتابة boolean.

**الوسائط:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

تحدد الحالة التي يجب أن يُظهر فيها شريط القسام العمودي. شريط القسام العمودي يفصل الشريحة عن منطقة المحتوى الجانبية.

**الإرجاع:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

تحدد الحالة التي يجب أن يُظهر فيها شريط القسام العمودي. شريط القسام العمودي يفصل الشريحة عن منطقة المحتوى الجانبية.

**الوسائط:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

تحدد الحالة التي يجب أن يُظهر فيها شريط القسام الأفقي. شريط القسام الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**الإرجاع:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

تحدد الحالة التي يجب أن يُظهر فيها شريط القسام الأفقي. شريط القسام الأفقي يفصل الشريحة عن منطقة المحتوى أسفل الشريحة.

**الوسائط:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

تحدد ما إذا كان المستخدم يفضِّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكينها، قد يختار التطبيق عرض إحدى مناطق المحتوى في النافذة بالكامل. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

تحدد ما إذا كان المستخدم يفضِّل رؤية منطقة محتوى واحدة ملء النافذة بدلاً من العرض العادي القياسي الذي يحتوي على ثلاث مناطق محتوى. إذا تم تمكينها، قد يختار التطبيق عرض إحدى مناطق المحتوى في النافذة بالكامل. قراءة/كتابة boolean.

**الوسائط:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

هذه العنصر تحدد حجم منطقة المحتوى الجانبية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغّرًا ولا مكبَّرًا). قراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

هذه العنصر تحدد حجم منطقة الشريحة العلوية في العرض العادي، عندما تكون المنطقة بحجم مستعاد متغير (ليس مصغّرًا ولا مكبَّرًا). قراءة فقط [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**الإرجاع:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)