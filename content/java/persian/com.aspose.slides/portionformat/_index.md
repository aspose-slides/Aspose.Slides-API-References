---
title: PortionFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است.
type: docs
url: /fa/com.aspose.slides/portionformat/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)  
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //یک شیء Presentation که نمایانگر یک فایل ارائه است را نمونه‌سازی می‌کند
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides از این شناسه‌های خاص استفاده می‌کند (مشابه آنچه در PowerPoint استفاده می‌شود):
>      // +mn-lt - قلم بدنه لاتین (قلم لاتین جزئی)
>      // +mj-lt - قلم سرعنوان لاتین (قلم لاتین اصلی)
>      // +mn-ea - قلم بدنه شرق آسیا (قلم شرق آسیا جزئی)
>      // +mj-ea - قلم بدنه شرق آسیا (قلم شرق آسیا جزئی)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، به‌طوری‌که در اکثر موارد مقادیر «نامشخص» دریافت خواهید کرد.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از متد [getEffective](../../com.aspose.slides/portionformat\#getEffective) استفاده کنید که یک نمونه از [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) را برمی‌گرداند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | یک نمونه جدید از کلاس [PortionFormat](../../com.aspose.slides/portionformat) را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | شناسه‌ی نشانک را باز می‌گرداند یا تنظیم می‌کند. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | شناسه‌ی نشانک را باز می‌گرداند یا تنظیم می‌کند. |
| [getSmartTagClean()](#getSmartTagClean--) | تشخیص می‌دهد که آیا برچسب هوشمند باید پاک شود یا خیر. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | تشخیص می‌دهد که آیا برچسب هوشمند باید پاک شود یا خیر. |
| [getHyperlinkClick()](#getHyperlinkClick--) | پیوندی که برای کلیک موس تعریف شده است را باز می‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | پیوندی که برای کلیک موس تعریف شده است را باز می‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | پیوندی که برای حرکت موس بر روی آن تعریف شده است را باز می‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | پیوندی که برای حرکت موس بر روی آن تعریف شده است را باز می‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkManager()](#getHyperlinkManager--) | مدیر پیوندها. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی بخش مؤثر را با اعمال ارث‌بری دریافت می‌کند. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

یک نمونه جدید از کلاس [PortionFormat](../../com.aspose.slides/portionformat) را مقداردهی اولیه می‌کند.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

شناسه‌ی نشانک را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگشت:**  
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

شناسه‌ی نشانک را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

تشخیص می‌دهد که آیا برچسب هوشمند باید پاک شود یا خیر. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن boolean .

**بازگشت:**  
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

تشخیص می‌دهد که آیا برچسب هوشمند باید پاک شود یا خیر. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

پیوند تعریف‌شده برای کلیک موس را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IHyperlink](../../com.aspose.slides/ihyperlink).

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

پیوند تعریف‌شده برای کلیک موس را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

پیوند تعریف‌شده برای حرکت موس بر روی آن را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IHyperlink](../../com.aspose.slides/ihyperlink).

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

پیوند تعریف‌شده برای حرکت موس بر روی آن را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

مدیر پیوندها. فقط-خواندنی [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**بازگشت:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی بخش مؤثر را با اعمال ارث‌بری دریافت می‌کند.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).