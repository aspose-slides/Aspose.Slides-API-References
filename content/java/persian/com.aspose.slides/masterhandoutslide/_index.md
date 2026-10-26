---
title: MasterHandoutSlide
second_title: مرجع API Aspose.Slides برای Java
description: نماینده اسلاید اصلی برای جزوه‌ها.
type: docs
url: /fa/com.aspose.slides/masterhandoutslide/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

نماینده اسلاید اصلی برای جزوه‌ها است.
## متدها

| متد | توضیح |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند که آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند که آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید اصلی جزوه را باز می‌گرداند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم را باز می‌گرداند. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی جزوه باز می‌گرداند. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می‌کند که آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی، این ویژگی همیشه false را باز می‌گرداند. قابل خواندن/قابل نوشتن بولی.

**بازگرداندن:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می‌کند که آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی، این ویژگی همیشه false را باز می‌گرداند. قابل خواندن/قابل نوشتن بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید اصلی جزوه را باز می‌گرداند. فقط-خواندنی [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**بازگرداندن:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

مدیر تم را باز می‌گرداند. فقط-خواندنی [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**بازگرداندن:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی جزوه باز می‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // اضافه کردن راهنمای رسم افقی جدید بالای مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)