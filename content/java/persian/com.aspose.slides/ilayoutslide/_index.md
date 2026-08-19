---
title: ILayoutSlide
second_title: راهنمای API Aspose.Slides برای جاوا
description: نمایانگر یک اسلاید چیدمان است.
type: docs
url: /fa/com.aspose.slides/ilayoutslide/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

نمایانگر یک اسلاید چیدمان است.
## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید چیدمان را برمی‌گرداند. |
| [getPlaceholderManager()](#getPlaceholderManager--) | مدیر جای‌نگهدارنده اسلاید چیدمان را برمی‌گرداند. |
| [getMasterSlide()](#getMasterSlide--) | اسلاید اصلی برای یک چیدمان را برمی‌گرداند یا تنظیم می‌کند. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | اسلاید اصلی برای یک چیدمان را برمی‌گرداند یا تنظیم می‌کند. |
| [getLayoutType()](#getLayoutType--) | نوع چیدمان این اسلاید چیدمان را برمی‌گرداند. |
| [hasDependingSlides()](#hasDependingSlides--) | در صورتی که حداقل یک اسلاید که به این اسلاید چیدمان وابسته است وجود داشته باشد، true را برمی‌گرداند. |
| [getDependingSlides()](#getDependingSlides--) | یک آرایه شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته هستند را برمی‌گرداند. |
| [remove()](#remove--) | چیدمان را از ارائه حذف می‌کند. |
| [getDrawingGuides()](#getDrawingGuides--) | یک مجموعه از راهنمایی‌های رسم برای اسلاید چیدمان را برمی‌گرداند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


مدیر HeaderFooter اسلاید چیدمان را برمی‌گرداند. فقط-خواندنی [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**بازگرداندن:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


مدیر جای‌نگهدارنده اسلاید چیدمان را برمی‌گرداند. فقط-خواندنی [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**بازگرداندن:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


اسلاید اصلی برای یک چیدمان را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IMasterSlide](../../com.aspose.slides/imasterslide).

**بازگرداندن:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


اسلاید اصلی برای یک چیدمان را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IMasterSlide](../../com.aspose.slides/imasterslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


نوع چیدمان این اسلاید چیدمان را برمی‌گرداند. فقط-خواندنی [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**بازگرداندن:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


در صورتی که حداقل یک اسلاید که به این اسلاید چیدمان وابسته است وجود داشته باشد، true را برمی‌گرداند. فقط-خواندنی boolean.

**بازگرداندن:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


یک آرایه شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته هستند را برمی‌گرداند.

**بازگرداندن:**
com.aspose.slides.ISlide[] - آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته هستند
### remove() {#remove--}
```
public abstract void remove()
```


چیدمان را از ارائه حذف می‌کند.
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


یک مجموعه از راهنمایی‌های رسم برای اسلاید چیدمان را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
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

**بازگرداندن:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)