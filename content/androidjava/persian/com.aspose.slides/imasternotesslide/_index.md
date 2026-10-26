---
title: IMasterNotesSlide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: اسلاید اصلی برای یادداشت‌ها را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/imasternotesslide/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

اسلاید اصلی برای یادداشت‌ها را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید یادداشت‌های اصلی را باز می‌گرداند. |
| [getNotesStyle()](#getNotesStyle--) | سبک متن یادداشت‌ها را باز می‌گرداند. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه‌ای از راهنمایی‌های رسم برای اسلاید یادداشت‌های اصلی را باز می‌گرداند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید یادداشت‌های اصلی را باز می‌گرداند. فقط خواندنی [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**باز می‌گردد:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

سبک متن یادداشت‌ها را باز می‌گرداند. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**باز می‌گردد:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

مجموعه‌ای از راهنمایی‌های رسم برای اسلاید یادداشت‌های اصلی را باز می‌گرداند. فقط خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
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

**باز می‌گردد:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)