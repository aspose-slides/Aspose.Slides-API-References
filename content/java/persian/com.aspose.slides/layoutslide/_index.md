---
title: LayoutSlide
second_title: مرجع API Aspose.Slides برای Java
description: یک اسلاید چیدمان را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/layoutslide/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

یک اسلاید چیدمان را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید چیدمان را باز می‌گرداند. |
| [getPlaceholderManager()](#getPlaceholderManager--) | مدیر جای‌گیر اسلاید چیدمان را باز می‌گرداند. |
| [getMasterSlide()](#getMasterSlide--) | اسلاید اصلی را برای یک چیدمان باز می‌گرداند یا تنظیم می‌کند. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | اسلاید اصلی را برای یک چیدمان باز می‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | چیدمان را از ارائه حذف می‌کند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم حاکم را باز می‌گرداند. |
| [getLayoutType()](#getLayoutType--) | نوع چیدمان این اسلاید چیدمان را باز می‌گرداند. |
| [getDependingSlides()](#getDependingSlides--) | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته‌اند را باز می‌گرداند. |
| [hasDependingSlides()](#hasDependingSlides--) | اگر حداقل یک اسلاید که به این اسلاید چیدمان وابسته باشد وجود داشته باشد، مقدار true را باز می‌گرداند. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند که آیا اشکال موجود در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند که آیا اشکال موجود در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه‌ای از راهنمای‌های رسم برای اسلاید چیدمان را باز می‌گرداند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


مدیر HeaderFooter اسلاید چیدمان را باز می‌گرداند. فقط خواندنی [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**باز می‌گردد:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


مدیر جای‌گیر اسلاید چیدمان را باز می‌گرداند. فقط خواندنی [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**باز می‌گردد:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


اسلاید اصلی را برای یک چیدمان باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IMasterSlide](../../com.aspose.slides/imasterslide).

**باز می‌گردد:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


اسلاید اصلی را برای یک چیدمان باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IMasterSlide](../../com.aspose.slides/imasterslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
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


مدیر تم حاکم را باز می‌گرداند. فقط خواندنی [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**باز می‌گردد:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


نوع چیدمان این اسلاید چیدمان را باز می‌گرداند. فقط خواندنی [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**باز می‌گردد:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته‌اند را باز می‌گرداند.

**باز می‌گردد:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


اگر حداقل یک اسلاید که به این اسلاید چیدمان وابسته باشد وجود داشته باشد، مقدار true را باز می‌گرداند. فقط خواندنی  boolean .

**باز می‌گردد:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


مشخص می‌کند که آیا اشکال موجود در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. قابل خواندن/نوشتن  boolean .

**باز می‌گردد:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


مشخص می‌کند که آیا اشکال موجود در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. قابل خواندن/نوشتن  boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


مجموعه‌ای از راهنمای‌های رسم برای اسلاید چیدمان را باز می‌گرداند. فقط خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // اضافه کردن راهنمای رسم عمودی جدید به سمت چپ مرکز اسلاید
> 
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گردد:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)