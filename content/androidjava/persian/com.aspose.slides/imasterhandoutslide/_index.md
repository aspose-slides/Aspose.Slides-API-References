---
title: IMasterHandoutSlide
second_title: Aspose.Slides برای Android از طریق رفرنس API جاوا
description: نماینده اسلاید اصلی برای جزوه‌ها.
type: docs
url: /fa/com.aspose.slides/imasterhandoutslide/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

نماینده اسلاید اصلی برای جزوه‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید اصلی جزوه را برمی‌گرداند. |
| [getDrawingGuides()](#getDrawingGuides--) | یک مجموعه از راهنمایی‌های رسم برای اسلاید اصلی جزوه را برمی‌گرداند. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


مدیر HeaderFooter اسلاید اصلی جزوه را برمی‌گرداند. فقط-خواندنی [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**بازمی‌گرداند:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


یک مجموعه از راهنمایی‌های رسم برای اسلاید اصلی جزوه را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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