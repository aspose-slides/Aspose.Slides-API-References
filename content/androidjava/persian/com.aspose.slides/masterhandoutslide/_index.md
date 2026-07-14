---
title: MasterHandoutSlide
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نماینده اسلاید اصلی برای جزوات.
type: docs
url: /fa/com.aspose.slides/masterhandoutslide/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**همهٔ رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

نمایش اسلاید اصلی برای جزوات.
## متدها

| متد | توضیح |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید اصلی جزوه را برمی‌گرداند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم را برمی‌گرداند. |
| [getDrawingGuides()](#getDrawingGuides--) | یک مجموعه از راهنمای‌های رسم برای اسلاید اصلی جزوه را برمی‌گرداند. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. خواندنی/نوشتنی boolean.

**بازمی‌گرداند:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید اصلی جزوه را برمی‌گرداند. فقط-خواندنی [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**بازمی‌گرداند:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

مدیر تم را برمی‌گرداند. فقط-خواندنی [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**بازمی‌گرداند:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

یک مجموعه از راهنمای‌های رسم برای اسلاید اصلی جزوه را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // افزودن راهنمای رسم افقی جدید بالای مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)