---
title: IMasterSlide
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک اسلاید مستر را در یک ارائه نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/imasterslide/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)  
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

یک اسلاید مستر را در یک ارائه نماینده می‌کند.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید مستر را برمی‌گرداند. |
| [getTitleStyle()](#getTitleStyle--) | قالب متن عنوان را برمی‌گرداند. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | یک اسلاید مستر جدید بر پایه اسلاید فعلی می‌سازد، یک تم خارجی را بر آن اعمال می‌کند و اسلاید مستر ساخته‌شده را بر تمام اسلایدهای وابسته اعمال می‌نماید. |
| [getBodyStyle()](#getBodyStyle--) | قالب متن بدنه را برمی‌گرداند. |
| [getOtherStyle()](#getOtherStyle--) | قالب متن دیگر را برمی‌گرداند. |
| [getLayoutSlides()](#getLayoutSlides--) | مجموعه اسلایدهای چیدمان فرزند برای این اسلاید مستر را برمی‌گرداند. |
| [getPreserve()](#getPreserve--) | تعیین می‌کند آیا مستر مربوطه وقتی تمام اسلایدهای پیرو آن مستر حذف شوند، حذف می‌شود. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | تعیین می‌کند آیا مستر مربوطه وقتی تمام اسلایدهای پیرو آن مستر حذف شوند، حذف می‌شود. |
| [hasDependingSlides()](#hasDependingSlides--) | اگر حداقل یک اسلاید که به این اسلاید مستر وابسته است وجود داشته باشد، true را برمی‌گرداند. |
| [getDependingSlides()](#getDependingSlides--) | یک آرایه شامل تمام اسلایدهایی که به این اسلاید مستر وابسته‌اند را برمی‌گرداند. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه راهنمای نگارشی برای اسلاید مستر را برمی‌گرداند. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید مستر را برمی‌گرداند. فقط-خواندنی [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**بازگشت:**  
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

قالب متن عنوان را برمی‌گرداند. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگشت:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

یک اسلاید مستر جدید بر پایه اسلاید فعلی می‌سازد، یک تم خارجی را بر آن اعمال می‌کند و اسلاید مستر ساخته‌شده را بر تمام اسلایدهای وابسته اعمال می‌نماید.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل تم خارجی (.thmx). |

**بازگشت:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide جدید با تم.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

قالب متن بدنه را برمی‌گرداند. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگشت:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

قالب متن دیگر را برمی‌گرداند. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگشت:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

مجموعه اسلایدهای چیدمان فرزند برای این اسلاید مستر را برمی‌گرداند. فقط-خواندنی [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

می‌توانید با استفاده از ویژگی ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) به API جایگزین برای افزودن/درج/حذف/کلون کردن اسلایدهای چیدمان دسترسی پیدا کنید.

**بازگشت:**  
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

تعیین می‌کند آیا مستر مربوطه وقتی تمام اسلایدهای پیرو آن مستر حذف شوند، حذف می‌شود. توجه: Aspose.Slides هرگز به خودی خود هیچ مستر استفاده‌نشده‌ای را حذف نمی‌کند، برای حذف واقعی مسترهای استفاده‌نشده از [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) قابل‌نوشتن/خواندن boolean استفاده کنید.

**بازگشت:**  
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

تعیین می‌کند آیا مستر مربوطه وقتی تمام اسلایدهای پیرو آن مستر حذف شوند، حذف می‌شود. توجه: Aspose.Slides هرگز به خودی خود هیچ مستر استفاده‌نشده‌ای را حذف نمی‌کند، برای حذف واقعی مسترهای استفاده‌نشده از [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) قابل‌نوشتن/خواندن boolean استفاده کنید.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

اگر حداقل یک اسلاید که به این اسلاید مستر وابسته است وجود داشته باشد، true را برمی‌گرداند. فقط-خواندنی boolean.

**بازگشت:**  
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

یک آرایه شامل تمام اسلایدهایی که به این اسلاید مستر وابسته‌اند را برمی‌گرداند.

**بازگشت:**  
com.aspose.slides.ISlide[] - آرایه‌ای از [ISlide](../../com.aspose.slides/islide) که به این اسلاید مستر وابسته‌اند

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

مجموعه راهنمای نگارشی برای اسلاید مستر را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
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


**بازگشت:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)