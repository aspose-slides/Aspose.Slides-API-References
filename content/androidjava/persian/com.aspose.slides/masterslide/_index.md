---
title: MasterSlide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده یک اسلاید اصلی در یک ارائه.
type: docs
url: /fa/com.aspose.slides/masterslide/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام اینترفیس‌های پیاده‌سازی شده:**  
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)  
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

نمایانگر یک اسلاید اصلی در یک ارائه است.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | باز می گرداند مدیر HeaderFooter اسلاید اصلی. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | یک اسلاید اصلی جدید ایجاد می کند بر پایه اسلاید فعلی، یک تم خارجی را به آن اعمال می کند و اسلاید اصلی ایجاد شده را به تمام اسلایدهای وابسته اعمال می کند. |
| [getTitleStyle()](#getTitleStyle--) | باز می گرداند سبک متن عنوان. |
| [getBodyStyle()](#getBodyStyle--) | باز می گرداند سبک متن بدنه. |
| [getOtherStyle()](#getOtherStyle--) | باز می گرداند سبک متن دیگر. |
| [getLayoutSlides()](#getLayoutSlides--) | باز می گرداند مجموعه‌ای از اسلایدهای طرح‌چیدمان فرزند برای این اسلاید اصلی. |
| [getPreserve()](#getPreserve--) | تعیین می کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهای پیرو حذف شود. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | تعیین می کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهای پیرو حذف شود. |
| [getDependingSlides()](#getDependingSlides--) | باز می گرداند آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته هستند. |
| [hasDependingSlides()](#hasDependingSlides--) | اگر حداقل یک اسلاید به این اسلاید اصلی وابسته باشد، مقدار true را باز می گرداند. |
| [getThemeManager()](#getThemeManager--) | باز می گرداند مدیر تم. |
| [getName()](#getName--) | باز می گرداند یا تنظیم می کند نام اسلاید اصلی. |
| [setName(String value)](#setName-java.lang.String-) | باز می گرداند یا تنظیم می کند نام اسلاید اصلی. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. |
| [getDrawingGuides()](#getDrawingGuides--) | باز می گرداند مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

باز می گرداند مدیر HeaderFooter اسلاید اصلی. فقط خواندنی [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**بازگرداندن:**  
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

یک اسلاید اصلی جدید ایجاد می کند بر پایه اسلاید فعلی، یک تم خارجی را به آن اعمال می کند و اسلاید اصلی ایجاد شده را به تمام اسلایدهای وابسته اعمال می کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل تم خارجی (.thmx). |

**بازگرداندن:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide جدید دارای تم.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

باز می گرداند سبک متن عنوان. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

باز می گرداند سبک متن بدنه. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

باز می گرداند سبک متن دیگر. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگرداندن:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

باز می گرداند مجموعه‌ای از اسلایدهای طرح‌چیدمان فرزند برای این اسلاید اصلی. فقط خواندنی [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

می‌توانید با استفاده از ویژگی ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) به API جایگزین برای افزودن/درج/حذف/کلون کردن اسلایدهای طرح‌چیدمان دسترسی پیدا کنید.

**بازگرداندن:**  
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

تعیین می کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهای پیرو حذف شود. نکته: Aspose.Slides هرگز به طور خودکار اسلاید اصلی استفاده نشده را حذف نمی کند، برای حذف واقعی اسلایدهای اصلی استفاده نشده فراخوانی کنید [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) قابل خواندن/نوشتن  boolean .

**بازگرداندن:**  
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

تعیین می کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهای پیرو حذف شود. نکته: Aspose.Slides هرگز به طور خودکار اسلاید اصلی استفاده نشده را حذف نمی کند، برای حذف واقعی اسلایدهای اصلی استفاده نشده فراخوانی کنید [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) قابل خواندن/نوشتن  boolean .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

باز می گرداند آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته هستند.

**بازگرداندن:**  
com.aspose.slides.ISlide[] - آرایه‌ای از [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

اگر حداقل یک اسلاید به این اسلاید اصلی وابسته باشد، مقدار true را باز می گرداند. فقط خواندنی  boolean .

**بازگرداندن:**  
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

باز می گرداند مدیر تم. فقط خواندنی [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**بازگرداندن:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

باز می گرداند یا تنظیم می کند نام اسلاید اصلی. قابل خواندن/نوشتن String.

**بازگرداندن:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

باز می گرداند یا تنظیم می کند نام اسلاید اصلی. قابل خواندن/نوشتن String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را باز می گرداند. قابل خواندن/نوشتن  boolean .

**بازگرداندن:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را باز می گرداند. قابل خواندن/نوشتن  boolean .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

باز می گرداند مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی. فقط خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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


**بازگرداندن:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)