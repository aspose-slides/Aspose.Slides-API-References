---
title: IMasterNotesSlide
second_title: راهنمای API Aspose.Slides برای جاوا
description: نمایش اسلاید اصلی برای یادداشت‌ها.
type: docs
url: /fa/com.aspose.slides/imasternotesslide/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

نمایش اسلاید اصلی برای یادداشت‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | بازمی‌گرداند مدیر HeaderFooter اسلاید اصلی یادداشت‌ها. |
| [getNotesStyle()](#getNotesStyle--) | بازمی‌گرداند سبک متن یادداشت‌ها. |
| [getDrawingGuides()](#getDrawingGuides--) | بازمی‌گرداند مجموعه‌ای از راهنمای‌های رسم برای اسلاید اصلی یادداشت‌ها. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

بازمی‌گرداند مدیر HeaderFooter اسلاید اصلی یادداشت‌ها. فقط-خواندنی [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**بازمی‌گرداند:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

بازمی‌گرداند سبک متن یادداشت‌ها. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازمی‌گرداند:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

بازمی‌گرداند مجموعه‌ای از راهنمای‌های رسم برای اسلاید اصلی یادداشت‌ها. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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