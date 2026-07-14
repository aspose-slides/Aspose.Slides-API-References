---
title: ILayoutSlide
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: یک اسلاید طرح‌بندی را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/ilayoutslide/
---
**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

یک اسلاید طرح‌بندی را نمایان می‌کند.
## متدها

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید طرح‌بندی را برمی‌گرداند. |
| [getPlaceholderManager()](#getPlaceholderManager--) | مدیر placeholder اسلاید طرح‌بندی را برمی‌گرداند. |
| [getMasterSlide()](#getMasterSlide--) | اسلاید master را برای یک طرح‌بندی برمی‌گرداند یا تنظیم می‌کند. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | اسلاید master را برای یک طرح‌بندی برمی‌گرداند یا تنظیم می‌کند. |
| [getLayoutType()](#getLayoutType--) | نوع layout این اسلاید طرح‌بندی را برمی‌گرداند. |
| [hasDependingSlides()](#hasDependingSlides--) | اگر حداقل یک اسلاید که به این اسلاید طرح‌بندی وابسته باشد وجود داشته باشد، true را برمی‌گرداند. |
| [getDependingSlides()](#getDependingSlides--) | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید طرح‌بندی وابسته‌اند را برمی‌گرداند. |
| [remove()](#remove--) | طرح‌بندی را از ارائه حذف می‌کند. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه‌ای از راهنمایی‌های رسم برای اسلاید طرح‌بندی را برمی‌گرداند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**بازگرداندن:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

مدیر placeholder اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**بازگرداندن:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

اسلاید master را برای یک طرح‌بندی برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IMasterSlide](../../com.aspose.slides/imasterslide).

**بازگرداندن:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

اسلاید master را برای یک طرح‌بندی برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IMasterSlide](../../com.aspose.slides/imasterslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

نوع layout این اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**بازگرداندن:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

اگر حداقل یک اسلاید که به این اسلاید طرح‌بندی وابسته باشد وجود داشته باشد، true را برمی‌گرداند. فقط-خواندنی boolean.

**بازگرداندن:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید طرح‌بندی وابسته‌اند را برمی‌گرداند.

**بازگرداندن:**
com.aspose.slides.ISlide[] - آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید طرح‌بندی وابسته‌اند
### remove() {#remove--}
```
public abstract void remove()
```

طرح‌بندی را از ارائه حذف می‌کند.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

مجموعه‌ای از راهنمایی‌های رسم برای اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // اضافه کردن راهنمای رسم عمودی جدید به سمت چپ مرکز اسلاید
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)