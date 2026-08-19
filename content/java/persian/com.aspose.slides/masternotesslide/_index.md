---
title: MasterNotesSlide
second_title: مرجع API Aspose.Slides برای Java
description: نمایندهٔ اسلاید مستر برای یادداشت‌ها.
type: docs
url: /fa/com.aspose.slides/masternotesslide/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)  
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

نمایندهٔ اسلاید مستر برای یادداشت‌ها است.

## متدها

| متد | توضیح |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا اشکال روی اسلاید مستر باید روی اسلایدها نشان داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا اشکال روی اسلاید مستر باید روی اسلایدها نشان داده شوند یا نه. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید مستر یادداشت‌ها را بازمی‌گرداند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم را بازمی‌گرداند. |
| [getNotesStyle()](#getNotesStyle--) | سبک متن یادداشت‌ها را بازمی‌گرداند. |
| [getDrawingGuides()](#getDrawingGuides--) | یک مجموعه از راهنمایی‌های رسم برای اسلاید مستر یادداشت‌ها را بازمی‌گرداند. |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می‌کند آیا اشکال روی اسلاید مستر باید روی اسلایدها نشان داده شوند یا نه. برای خود اسلاید مستر این ویژگی همیشه false بازمی‌گرداند. خواندنی/قابل نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا اشکال روی اسلاید مستر باید روی اسلایدها نشان داده شوند یا نه. برای خود اسلاید مستر این ویژگی همیشه false بازمی‌گرداند. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید مستر یادداشت‌ها را بازمی‌گرداند. فقط‌خواندنی [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**بازمی‌گرداند:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

مدیر تم را بازمی‌گرداند. فقط‌خواندنی [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**بازمی‌گرداند:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

سبک متن یادداشت‌ها را بازمی‌گرداند. فقط‌خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازمی‌گرداند:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

یک مجموعه از راهنمایی‌های رسم برای اسلاید مستر یادداشت‌ها را بازمی‌گرداند. فقط‌خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // افزودن راهنمای رسم افقی جدید زیر مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)