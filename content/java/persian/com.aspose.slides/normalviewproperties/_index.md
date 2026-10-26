---
title: NormalViewProperties
second_title: مرجع API Aspose.Slides برای جاوا
description: ویژگی‌های نمای عادی را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/normalviewproperties/
---
**ارث‌بری:**  
java.lang.Object

**همه رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)  
```
public class NormalViewProperties implements INormalViewProperties
```

نمایش عادی نمایانگر خاصیت‌های آن است. نمایش عادی شامل سه ناحیه محتوا است: خود اسلاید، یک ناحیه محتوا جانبی، و یک ناحیه محتوا پایین.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
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

## متدها

| متد | توضیح |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح کلی در هر یک از ناحیه‌های محتوا در حالت نمایش عادی، آیکون‌ها را نشان دهد. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح کلی در هر یک از ناحیه‌های محتوا در حالت نمایش عادی، آیکون‌ها را نشان دهد. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | مشخص می‌کند آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه جانبی، به حالت به‌حداقل‌رسیده بچسبد. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | مشخص می‌کند آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه جانبی، به حالت به‌حداقل‌رسیده بچسبد. |
| [getVerticalBarState()](#getVerticalBarState--) | حالت نمایش نوار تقسیم‌کننده عمودی را مشخص می‌کند. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | حالت نمایش نوار تقسیم‌کننده عمودی را مشخص می‌کند. |
| [getHorizontalBarState()](#getHorizontalBarState--) | حالت نمایش نوار تقسیم‌کننده افقی را مشخص می‌کند. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | حالت نمایش نوار تقسیم‌کننده افقی را مشخص می‌کند. |
| [getPreferSingleView()](#getPreferSingleView--) | مشخص می‌کند آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک‌پنجره‌ای را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | مشخص می‌کند آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک‌پنجره‌ای را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. |
| [getRestoredLeft()](#getRestoredLeft--) | این عنصر اندازه‌گیری ناحیه محتوا جانبی نمایش عادی را مشخص می‌کند، هنگامی که ناحیه دارای اندازه بازگردانی متغیر (نه کوچک‌شده نه بزرگ‌شده) باشد. |
| [getRestoredTop()](#getRestoredTop--) | این عنصر اندازه‌گیری ناحیه اسلاید بالایی نمایش عادی را مشخص می‌کند، هنگامی که ناحیه دارای اندازه بازگردانی متغیر (نه کوچک‌شده نه بزرگ‌شده) باشد. |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح کلی در هر یک از ناحیه‌های محتوا در حالت نمایش عادی، آیکون‌ها را نشان دهد. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح کلی در هر یک از ناحیه‌های محتوا در حالت نمایش عادی، آیکون‌ها را نشان دهد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

مشخص می‌کند آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه جانبی، به حالت به‌حداقل‌رسیده بچسبد. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

مشخص می‌کند آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه جانبی، به حالت به‌حداقل‌رسیده بچسبد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

حالت نمایش نوار تقسیم‌کننده عمودی را مشخص می‌کند. یک نوار تقسیم‌کننده عمودی اسلاید را از ناحیه محتوا جانبی جدا می‌کند.

**بازمی‌گرداند:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

حالت نمایش نوار تقسیم‌کننده عمودی را مشخص می‌کند. یک نوار تقسیم‌کننده عمودی اسلاید را از ناحیه محتوا جانبی جدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

حالت نمایش نوار تقسیم‌کننده افقی را مشخص می‌کند. یک نوار تقسیم‌کننده افقی اسلاید را از ناحیه محتوا زیر اسلاید جدا می‌کند.

**بازمی‌گرداند:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

حالت نمایش نوار تقسیم‌کننده افقی را مشخص می‌کند. یک نوار تقسیم‌کننده افقی اسلاید را از ناحیه محتوا زیر اسلاید جدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

مشخص می‌کند آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک‌پنجره‌ای را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. اگر فعال باشد، برنامه ممکن است یکی از ناحیه‌های محتوا را در تمام پنجره نمایش دهد. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

مشخص می‌کند آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک‌پنجره‌ای را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. اگر فعال باشد، برنامه ممکن است یکی از ناحیه‌های محتوا را در تمام پنجره نمایش دهد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

این عنصر اندازه‌گیری ناحیه محتوا جانبی نمایش عادی را مشخص می‌کند، هنگامی که ناحیه دارای اندازه بازگردانی متغیر (نه کوچک‌شده نه بزرگ‌شده) باشد. فقط‌خواندنی [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**بازمی‌گرداند:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

این عنصر اندازه‌گیری ناحیه اسلاید بالایی نمایش عادی را مشخص می‌کند، هنگامی که ناحیه دارای اندازه بازگردانی متغیر (نه کوچک‌شده نه بزرگ‌شده) باشد. فقط‌خواندنی [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**بازمی‌گرداند:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)