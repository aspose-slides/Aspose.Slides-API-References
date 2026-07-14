---
title: MasterNotesSlide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش اسلاید اصلی برای یادداشت‌ها.
type: docs
url: /fa/com.aspose.slides/masternotesslide/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

نمایش اسلاید اصلی برای یادداشت‌ها.
## متدها

| متد | شرح |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را بر می‌گرداند. قابل‌خواندن/قابل‌نوشتن boolean. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را بر می‌گرداند. قابل‌خواندن/قابل‌نوشتن boolean. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید اصلی یادداشت‌ها را بر می‌گرداند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم را بر می‌گرداند. |
| [getNotesStyle()](#getNotesStyle--) | سبک متن یادداشت‌ها را بر می‌گرداند. |
| [getDrawingGuides()](#getDrawingGuides--) | یک مجموعه از راهنمایی‌های رسم برای اسلاید اصلی یادداشت‌ها را بر می‌گرداند. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را بر می‌گرداند. قابل‌خواندن/قابل‌نوشتن boolean.

**بازگرداندن:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را بر می‌گرداند. قابل‌خواندن/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید اصلی یادداشت‌ها را بر می‌گرداند. فقط‌خواندنی [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**بازگرداندن:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

مدیر تم را بر می‌گرداند. فقط‌خواندنی [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**بازگرداندن:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

سبک متن یادداشت‌ها را بر می‌گرداند. فقط‌خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

یک مجموعه از راهنمایی‌های رسم برای اسلاید اصلی یادداشت‌ها را بر می‌گرداند. فقط‌خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // اضافه کردن راهنمای رسم افقی جدید زیر مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگرداندن:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)