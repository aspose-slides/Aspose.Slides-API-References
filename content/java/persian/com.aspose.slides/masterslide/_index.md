---
title: MasterSlide
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک اسلاید اصلی در یک ارائه است.
type: docs
url: /fa/com.aspose.slides/masterslide/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)  
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

نمایانگر یک اسلاید اصلی در یک ارائه است.

## متدها

| متد | توضیح |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter اسلاید اصلی را باز می‌گرداند. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | یک اسلاید اصلی جدید بر پایه اسلاید فعلی ایجاد می‌کند، تم خارجی را به آن اعمال می‌نماید و اسلاید اصلی ایجاد‌شده را بر تمام اسلایدهای وابسته اعمال می‌کند. |
| [getTitleStyle()](#getTitleStyle--) | سبک متن عنوان را باز می‌گرداند. |
| [getBodyStyle()](#getBodyStyle--) | سبک متن بدنه را باز می‌گرداند. |
| [getOtherStyle()](#getOtherStyle--) | سبک متن دیگر را باز می‌گرداند. |
| [getLayoutSlides()](#getLayoutSlides--) | مجموعه اسلایدهای چیدمان فرزند برای این اسلاید اصلی را باز می‌گرداند. |
| [getPreserve()](#getPreserve--) | تعیین می‌کند که آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهایی که پس از آن می‌آیند حذف می‌شود یا خیر. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | تعیین می‌کند که آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهایی که پس از آن می‌آیند حذف می‌شود یا خیر. |
| [getDependingSlides()](#getDependingSlides--) | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته هستند را باز می‌گرداند. |
| [hasDependingSlides()](#hasDependingSlides--) | اگر حداقل یک اسلاید وجود داشته باشد که به این اسلاید اصلی وابسته باشد، true باز می‌گرداند. |
| [getThemeManager()](#getThemeManager--) | مدیر تم را باز می‌گرداند. |
| [getName()](#getName--) | نام یک اسلاید اصلی را باز می‌گرداند یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک اسلاید اصلی را باز می‌گرداند یا تنظیم می‌کند. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی را باز می‌گرداند. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter اسلاید اصلی را باز می‌گرداند. فقط خواندنی [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**باز می‌گرداند:**  
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

یک اسلاید اصلی جدید بر پایه اسلاید فعلی ایجاد می‌کند، تم خارجی را به آن اعمال می‌نماید و اسلاید اصلی ایجاد‌شده را بر تمام اسلایدهای وابسته اعمال می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل تم خارجی (.thmx). |

**باز می‌گرداند:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اصلی جدید تم‌دار.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

سبک متن عنوان را باز می‌گرداند. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**باز می‌گرداند:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

سبک متن بدنه را باز می‌گرداند. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**باز می‌گرداند:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

سبک متن دیگر را باز می‌گرداند. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**باز می‌گرداند:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

مجموعه اسلایدهای چیدمان فرزند برای این اسلاید اصلی را باز می‌گرداند. فقط خواندنی [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

شما می‌توانید با استفاده از ویژگی ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) به API جایگزین برای افزودن/درج/حذف/کلون کردن اسلایدهای چیدمان دسترسی داشته باشید.

**باز می‌گرداند:**  
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

تعیین می‌کند آیا اسلاید اصلی مرتبط هنگام حذف تمام اسلایدهایی که پس از آن می‌آیند حذف می‌شود یا خیر. نکته: Aspose.Slides هرگز به‌تنهایی اسلاید اصلی بلااستفاده‌ای را حذف نمی‌کند؛ برای حذف واقعی اسلایدهای اصلی بلااستفاده باید [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) را صدا بزنید. خواندنی/قابل‌نوشتن  boolean .

**باز می‌گرداند:**  
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

تعیین می‌کند آیا اسلاید اصلی مرتبط هنگام حذف تمام اسلایدهایی که پس از آن می‌آیند حذف می‌شود یا خیر. نکته: Aspose.Slides هرگز به‌تنهایی اسلاید اصلی بلااستفاده‌ای را حذف نمی‌کند؛ برای حذف واقعی اسلایدهای اصلی بلااستفاده باید [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) را صدا بزنید. خواندنی/قابل‌نوشتن  boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته هستند را باز می‌گرداند.

**باز می‌گرداند:**  
com.aspose.slides.ISlide[] - آرایه‌ای از [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

اگر حداقل یک اسلاید وجود داشته باشد که به این اسلاید اصلی وابسته باشد، true باز می‌گرداند. فقط خواندنی  boolean .

**باز می‌گرداند:**  
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

مدیر تم را باز می‌گرداند. فقط خواندنی [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**باز می‌گرداند:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

نام یک اسلاید اصلی را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن String.

**باز می‌گرداند:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

نام یک اسلاید اصلی را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را برمی‌گرداند. خواندنی/قابل‌نوشتن  boolean .

**باز می‌گرداند:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار false را برمی‌گرداند. خواندنی/قابل‌نوشتن  boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی را باز می‌گرداند. فقط خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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


**باز می‌گرداند:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)