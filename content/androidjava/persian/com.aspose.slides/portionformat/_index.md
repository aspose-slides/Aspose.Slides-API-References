---
title: PortionFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: این کلاس شامل ویژگی‌های قالب‌بندی قسمت متن است.
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

این کلاس شامل ویژگی‌های قالب‌بندی قسمت متن است. برخلاف [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //یک شیء presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides از این شناسه‌های خاص استفاده می‌کند (مشابه شناسه‌های استفاده شده در PowerPoint):
>      // +mn-lt - قلم بدنه لاتین (قلم لاتین جزئی)
>      // +mj-lt - قلم سرعنوان لاتین (قلم لاتین اصلی)
>      // +mn-ea - قلم بدنه شرق آسیایی (قلم شرق آسیایی جزئی)
>      // +mj-ea - قلم بدنه شرق آسیایی (قلم شرق آسیایی جزئی)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی قسمت متن تعریف‌شده برای بخش خاص استفاده می‌شود. این بدان معناست که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در اکثر موارد مقادیر «undefined» دریافت می‌کنید.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل ارث‌بری، باید از متد [getEffective](../../com.aspose.slides/portionformat\#getEffective) استفاده کنید که یک نمونهٔ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) را برمی‌گرداند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | یک نمونهٔ جدید از کلاس [PortionFormat](../../com.aspose.slides/portionformat) را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | شناسهٔ نشانک را برمی‌گرداند یا تنظیم می‌کند. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | شناسهٔ نشانک را برمی‌گرداند یا تنظیم می‌کند. |
| [getSmartTagClean()](#getSmartTagClean--) | مشخص می‌کند که آیا برچسب هوشمند باید پاک شود یا نه. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | مشخص می‌کند که آیا برچسب هوشمند باید پاک شود یا نه. |
| [getHyperlinkClick()](#getHyperlinkClick--) | پیوند یاب تعریف‌شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | پیوند یاب تعریف‌شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | پیوند یاب تعریف‌شده برای حرکت موس را برمی‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | پیوند یاب تعریف‌شده برای حرکت موس را برمی‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkManager()](#getHyperlinkManager--) | مدیر پیوندهای یاب. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر قسمت را با اعمال ارث‌بری دریافت می‌کند. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

یک نمونهٔ جدید از کلاس [PortionFormat](../../com.aspose.slides/portionformat) را مقداردهی اولیه می‌کند.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

شناسهٔ نشانک را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

شناسهٔ نشانک را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

مشخص می‌کند که آیا برچسب هوشمند باید پاک شود. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی boolean .

**بازگشت:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

مشخص می‌کند که آیا برچسب هوشمند باید پاک شود. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

پیوند یاب تعریف‌شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

پیوند یاب تعریف‌شده برای کلیک موس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

پیوند یاب تعریف‌شده برای حرکت موس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**بازگشت:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

پیوند یاب تعریف‌شده برای حرکت موس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

مدیر پیوندهای یاب. فقط-خواندنی [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**بازگشت:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر قسمت را با اعمال ارث‌بری دریافت می‌کند.

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