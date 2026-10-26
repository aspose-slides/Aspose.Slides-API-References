---
title: LayoutSlide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک اسلاید چیدمان را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/layoutslide/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

نمایش‌گر اسلاید چیدمان.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیّر HeaderFooter اسلاید چیدمان را برمی‌گرداند. |
| [getPlaceholderManager()](#getPlaceholderManager--) | مدیّر placeholder اسلاید چیدمان را برمی‌گرداند. |
| [getMasterSlide()](#getMasterSlide--) | اسلاید master را برای یک چیدمان برمی‌گرداند یا تنظیم می‌کند. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | اسلاید master را برای یک چیدمان برمی‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | چیدمان را از ارائه حذف می‌کند. |
| [getThemeManager()](#getThemeManager--) | مدیّر theme حاکم را برمی‌گرداند. |
| [getLayoutType()](#getLayoutType--) | نوع چیدمان این اسلاید چیدمان را برمی‌گرداند. |
| [getDependingSlides()](#getDependingSlides--) | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته‌اند را برمی‌گرداند. |
| [hasDependingSlides()](#hasDependingSlides--) | اگر حداقل یک اسلاید که به این اسلاید چیدمان وابسته باشد وجود داشته باشد، مقدار true را برمی‌گرداند. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا اشکال در اسلاید master باید روی اسلایدها نشان داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا اشکال در اسلاید master باید روی اسلایدها نشان داده شوند یا نه. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه‌ای از راهنمایی‌های رسم برای اسلاید چیدمان را برمی‌گرداند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


مدیّر HeaderFooter اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Returns:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


مدیّر placeholder اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Returns:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


اسلاید master را برای یک چیدمان برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [IMasterSlide](../../com.aspose.slides/imasterslide).

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


اسلاید master را برای یک چیدمان برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


چیدمان را از ارائه حذف می‌کند.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


مدیّر theme حاکم را برمی‌گرداند. فقط خواندنی [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returns:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


نوع چیدمان این اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Returns:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته‌اند را برمی‌گرداند.

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


اگر حداقل یک اسلاید که به این اسلاید چیدمان وابسته باشد وجود داشته باشد، مقدار true را برمی‌گرداند. فقط خواندنی  boolean .

**Returns:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


مشخص می‌کند آیا اشکال در اسلاید master باید روی اسلایدها نشان داده شوند یا نه. قابل خواندن و نوشتن  boolean .

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


مشخص می‌کند آیا اشکال در اسلاید master باید روی اسلایدها نشان داده شوند یا نه. قابل خواندن و نوشتن  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


مجموعه‌ای از راهنمایی‌های رسم برای اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // افزودن راهنمای رسم عمودی جدید به سمت چپ مرکز اسلاید
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)