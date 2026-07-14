---
title: NormalViewProperties
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: ویژگی‌های نمای عادی را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/normalviewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

نمایش ویژگی‌های نمای عادی را ارائه می‌دهد. نمای عادی شامل سه ناحیه محتوا است: خود اسلاید، یک ناحیه محتوا کناری و یک ناحیه محتوا پایین.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //یک شیء ارائه ایجاد می‌کند که نمایانگر یک فایل ارائه است
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
| [getShowOutlineIcons()](#getShowOutlineIcons--) | مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح بندی در هر یک از نواحی محتوا در حالت نمای عادی، آیکون‌ها را نشان دهد. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح بندی در هر یک از نواحی محتوا در حالت نمای عادی، آیکون‌ها را نشان دهد. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه کناری به حالت حداقل شود. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه کناری به حالت حداقل شود. |
| [getVerticalBarState()](#getVerticalBarState--) | وضعیت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | وضعیت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. |
| [getHorizontalBarState()](#getHorizontalBarState--) | وضعیت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | وضعیت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. |
| [getPreferSingleView()](#getPreferSingleView--) | مشخص می‌کند که کاربر ترجیح می‌دهد یک ناحیه محتوای تک-پنجره‌ای تمام‌صفحه را به جای نمای عادی استاندارد با سه ناحیه محتوا ببیند. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | مشخص می‌کند که کاربر ترجیح می‌دهد یک ناحیه محتوای تک-پنجره‌ای تمام‌صفحه را به جای نمای عادی استاندارد با سه ناحیه محتوا ببیند. |
| [getRestoredLeft()](#getRestoredLeft--) | این عنصر اندازه‌گیری ناحیه محتوای کناری نمای عادی را وقتی که ناحیه در اندازه بازگردانده متغیر (نه حداقل و نه حداکثر) باشد، مشخص می‌کند. |
| [getRestoredTop()](#getRestoredTop--) | این عنصر اندازه‌گیری ناحیه اسلاید بالایی نمای عادی را وقتی که ناحیه در اندازه بازگردانده متغیر (نه حداقل و نه حداکثر) باشد، مشخص می‌کند. |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```


مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح بندی در هر یک از نواحی محتوا در حالت نمای عادی، آیکون‌ها را نشان دهد. خواندنی/نوشتنی بولی.

**بازگشت:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```


مشخص می‌کند که آیا برنامه باید هنگام نمایش محتوای طرح بندی در هر یک از نواحی محتوا در حالت نمای عادی، آیکون‌ها را نشان دهد. خواندنی/نوشتنی بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```


مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه کناری به حالت حداقل شود. خواندنی/نوشتنی بولی.

**بازگشت:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```


مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن کافی ناحیه کناری به حالت حداقل شود. خواندنی/نوشتنی بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```


وضعیت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. نوار تقسیم‌کننده عمودی اسلاید را از ناحیه محتوای کناری جدا می‌کند.

**بازگشت:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```


وضعیت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. نوار تقسیم‌کننده عمودی اسلاید را از ناحیه محتوای کناری جدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```


وضعیت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. نوار تقسیم‌کننده افقی اسلاید را از ناحیه محتوای زیر اسلاید جدا می‌کند.

**بازگشت:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```


وضعیت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. نوار تقسیم‌کننده افقی اسلاید را از ناحیه محتوای زیر اسلاید جدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```


مشخص می‌کند که کاربر ترجیح می‌دهد یک ناحیه محتوای تک-پنجره‌ای تمام‌صفحه را به جای نمای عادی استاندارد با سه ناحیه محتوا ببیند. اگر فعال باشد، برنامه ممکن است یکی از نواحی محتوا را در کل پنجره نمایش دهد. خواندنی/نوشتنی بولی.

**بازگشت:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```


مشخص می‌کند که کاربر ترجیح می‌دهد یک ناحیه محتوای تک-پنجره‌ای تمام‌صفحه را به جای نمای عادی استاندارد با سه ناحیه محتوا ببیند. اگر فعال باشد، برنامه ممکن است یکی از نواحی محتوا را در کل پنجره نمایش دهد. خواندنی/نوشتنی بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```


این عنصر اندازه‌گیری ناحیه محتوای کناری نمای عادی را وقتی که ناحیه در اندازه بازگردانده متغیر (نه حداقل و نه حداکثر) باشد، مشخص می‌کند. فقط خواندنی [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**بازگشت:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```


این عنصر اندازه‌گیری ناحیه اسلاید بالایی نمای عادی را وقتی که ناحیه در اندازه بازگردانده متغیر (نه حداقل و نه حداکثر) باشد، مشخص می‌کند. فقط خواندنی [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**بازگشت:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)