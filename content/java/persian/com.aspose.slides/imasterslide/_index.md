---
title: IMasterSlide
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک اسلاید اصلی در یک ارائه.
type: docs
url: /fa/com.aspose.slides/imasterslide/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

نمایانگر یک اسلاید اصلی در یک ارائه است.
## متدها

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | بازگرداندن مدیر HeaderFooter اسلاید اصلی. |
| [getTitleStyle()](#getTitleStyle--) | بازگرداندن سبک متن عنوان. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | یک اسلاید اصلی جدید بر پایه اسلاید فعلی ایجاد می‌کند، تم خارجی را به آن اعمال می‌نماید و اسلاید اصلی ایجاد شده را به تمام اسلایدهای وابسته اعمال می‌کند. |
| [getBodyStyle()](#getBodyStyle--) | بازگرداندن سبک متن بدنه. |
| [getOtherStyle()](#getOtherStyle--) | بازگرداندن سبک متن دیگر. |
| [getLayoutSlides()](#getLayoutSlides--) | بازگرداندن مجموعه اسلایدهای طرح‌بندی فرزند برای این اسلاید اصلی. |
| [getPreserve()](#getPreserve--) | مشخص می‌کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهایی که پس از آن می‌آیند، حذف می‌شود. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | مشخص می‌کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهایی که پس از آن می‌آیند، حذف می‌شود. |
| [hasDependingSlides()](#hasDependingSlides--) | بازگرداندن true اگر حداقل یک اسلاید که به این اسلاید اصلی وابسته است وجود داشته باشد. |
| [getDependingSlides()](#getDependingSlides--) | بازگرداندن آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته‌اند. |
| [getDrawingGuides()](#getDrawingGuides--) | بازگرداندن مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

بازگرداندن مدیر HeaderFooter اسلاید اصلی. فقط-خواندنی [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**بازگرداندن:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

بازگرداندن سبک متن عنوان. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

یک اسلاید اصلی جدید بر پایه اسلاید فعلی ایجاد می‌کند، تم خارجی را به آن اعمال می‌نماید و اسلاید اصلی ایجاد شده را به تمام اسلایدهای وابسته اعمال می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل تم خارجی (.thmx). |

**بازگرداندن:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اصلی جدید دارای تم.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

بازگرداندن سبک متن بدنه. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

بازگرداندن سبک متن دیگر. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

بازگرداندن مجموعه اسلایدهای طرح‌بندی فرزند برای این اسلاید اصلی. فقط-خواندنی [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

می‌توانید با استفاده از ویژگی ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) به API جایگزین برای اضافه/درج/حذف/کلون اسلایدهای طرح‌بندی دسترسی پیدا کنید.

**بازگرداندن:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

مشخص می‌کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهای پس‌ماننده حذف می‌شود. نکته: Aspose.Slides هرگز به‌طور خودکار اسلاید اصلی استفاده نشده را حذف نخواهد کرد؛ برای حذف واقعی اسلایدهای اصلی استفاده نشده، [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) را فراخوانی کنید. خواندن/نوشتن boolean.

**بازگرداندن:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

مشخص می‌کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهای پس‌ماننده حذف می‌شود. نکته: Aspose.Slides هرگز به‌طور خودکار اسلاید اصلی استفاده نشده را حذف نخواهد کرد؛ برای حذف واقعی اسلایدهای اصلی استفاده نشده، [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) را فراخوانی کنید. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

بازگرداندن true اگر حداقل یک اسلاید که به این اسلاید اصلی وابسته است وجود داشته باشد. فقط-خواندنی boolean.

**بازگرداندن:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

بازگرداندن آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته‌اند.

**بازگرداندن:**
com.aspose.slides.ISlide[] - آرایه‌ای از [ISlide](../../com.aspose.slides/islide) که به این اسلاید اصلی وابسته‌اند
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

بازگرداندن مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // افزودن راهنمای رسم عمودی جدید به سمت راست مرکز اسلاید
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگرداندن:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)