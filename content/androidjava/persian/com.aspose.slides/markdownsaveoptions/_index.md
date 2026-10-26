---
title: MarkdownSaveOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را نشان می‌دهد که نحوه ذخیره ارائه به markdown را کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/markdownsaveoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

نمایش گزینه‌هایی که نحوه ذخیره ارائه به markdown را کنترل می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | سازنده. |
## متدها

| متد | توضیح |
| --- | --- |
| [getExportType()](#getExportType--) | مشخص می‌کند که کدام مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [setExportType(int value)](#setExportType-int-) | مشخص می‌کند که کدام مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [getBasePath()](#getBasePath--) | مسیر پایه‌ای را که سند با منابع در آن ذخیره می‌شود، مشخص می‌کند. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | مسیر پایه‌ای را که سند با منابع در آن ذخیره می‌شود، مشخص می‌کند. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | نام پوشه‌ای را که تصاویر در آن ذخیره می‌شوند، مشخص می‌کند. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | نام پوشه‌ای را که تصاویر در آن ذخیره می‌شوند، مشخص می‌کند. |
| [getNewLineType()](#getNewLineType--) | مشخص می‌کند آیا سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. |
| [setNewLineType(int value)](#setNewLineType-int-) | مشخص می‌کند آیا سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. |
| [getShowComments()](#getShowComments--) | مشخص می‌کند آیا سند تولید شده نظرات را نشان دهد یا نه. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | مشخص می‌کند آیا سند تولید شده نظرات را نشان دهد یا نه. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. |
| [getShowSlideNumber()](#getShowSlideNumber--) | مشخص می‌کند آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | مشخص می‌کند آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. |
| [getFlavor()](#getFlavor--) | مشخص می‌کند که کدام مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [setFlavor(int value)](#setFlavor-int-) | مشخص می‌کند که کدام مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | دریافت یا تنظیم رشته قالب‌بندی مورد استفاده برای سرعنوان‌های شماره اسلاید در خروجی Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | دریافت یا تنظیم رشته قالب‌بندی مورد استفاده برای سرعنوان‌های شماره اسلاید در خروجی Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | مشخص می‌کند کاراکترهای فضای خالی عادی تکراری چگونه در هنگام صادرات Markdown پردازش شوند. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | مشخص می‌کند کاراکترهای فضای خالی عادی تکراری چگونه در هنگام صادرات Markdown پردازش شوند. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | اگر به true تنظیم شود، خطوط خالی یا تنها حاوی فضای خالی را از خروجی نهایی Markdown حذف می‌کند. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | اگر به true تنظیم شود، خطوط خالی یا تنها حاوی فضای خالی را از خروجی نهایی Markdown حذف می‌کند. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | در هنگام صادرات Markdown برای هر تصویر غیر SVG (bitmap یا metafile) رخ می‌دهد. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | در هنگام صادرات Markdown برای هر تصویر SVG رخ می‌دهد. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

سازنده.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

مشخص می‌کند کدام مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض TextOnly است.

**بازگشت:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

مشخص می‌کند کدام مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض TextOnly است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

مسیر پایه‌ای را که سند با منابع در آن ذخیره می‌شود، مشخص می‌کند. پیش‌فرض پوشه جاری برنامه است.

**بازگشت:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

مسیر پایه‌ای را که سند با منابع در آن ذخیره می‌شود، مشخص می‌کند. پیش‌فرض پوشه جاری برنامه است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

نام پوشه‌ای را که تصاویر در آن ذخیره می‌شوند، مشخص می‌کند. پیش‌فرض Images است.

**بازگشت:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

نام پوشه‌ای را که تصاویر در آن ذخیره می‌شوند، مشخص می‌کند. پیش‌فرض Images است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

مشخص می‌کند آیا سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. پیش‌فرض Unix است.

**بازگشت:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

مشخص می‌کند آیا سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. پیش‌فرض Unix است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

مشخص می‌کند آیا سند تولید شده نظرات را نشان دهد یا نه. پیش‌فرض false است.

**بازگشت:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

مشخص می‌کند آیا سند تولید شده نظرات را نشان دهد یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**بازگشت:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

مشخص می‌کند آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. پیش‌فرض false است.

**بازگشت:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

مشخص می‌کند آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

مشخص می‌کند کدام مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض Multi-markdown است.

**بازگشت:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

مشخص می‌کند کدام مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض Multi-markdown است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

دریافت یا تنظیم رشته قالب‌بندی مورد استفاده برای سرعنوان‌های شماره اسلاید در خروجی Markdown. قالب باید شامل جای‌گذار "\{0\}" باشد که در هنگام صادرات با اندیس اسلاید جایگزین می‌شود. مثال: "\# Slide \{0\}" → "\# Slide 1"، "\# Slide 2"، و غیره.

**بازگشت:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

دریافت یا تنظیم رشته قالب‌بندی مورد استفاده برای سرعنوان‌های شماره اسلاید در خروجی Markdown. قالب باید شامل جای‌گذار "\{0\}" باشد که در هنگام صادرات با اندیس اسلاید جایگزین می‌شود. مثال: "\# Slide \{0\}" → "\# Slide 1"، "\# Slide 2"، و غیره.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

مشخص می‌کند کاراکترهای فضای خالی عادی تکراری چگونه در هنگام صادرات Markdown پردازش شوند. این ویژگی تعریف می‌کند که فضاهای متوالی: - به صورت کاراکترهای فضای عادی حفظ شوند، - بین فضای عادی و نهادهای فضای غیرقابل شکستن (�) جابجا شوند، - یا پس از اولین فضا به طور کامل با فضای غیرقابل شکستن جایگزین شوند تا چینش ظاهری در خروجی حفظ شود. مقدار پیش‌فرض [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) است.

**بازگشت:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

مشخص می‌کند کاراکترهای فضای خالی عادی تکراری چگونه در هنگام صادرات Markdown پردازش شوند. این ویژگی تعریف می‌کند که فضاهای متوالی: - به صورت کاراکترهای فضای عادی حفظ شوند، - بین فضای عادی و نهادهای فضای غیرقابل شکستن (�) جابجا شوند، - یا پس از اولین فضا به طور کامل با فضای غیرقابل شکستن جایگزین شوند تا چینش ظاهری در خروجی حفظ شود. مقدار پیش‌فرض [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

اگر به true تنظیم شود، خطوط خالی یا تنها حاوی فضای خالی را از خروجی نهایی Markdown حذف می‌کند. پیش‌فرض false است.

**بازگشت:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

اگر به true تنظیم شود، خطوط خالی یا تنها حاوی فضای خالی را از خروجی نهایی Markdown حذف می‌کند. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

در هنگام صادرات Markdown برای هر تصویر غیر SVG (bitmap یا metafile) رخ می‌دهد. امکان سفارشی‌سازی نحوه ذخیره و ارجاع به تصویر فراهم می‌شود. اگر مدیریت نشود، تصویر به‌صورت محلی با لینک نسبی ذخیره می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | رویداد ذخیره تصویر Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

در هنگام صادرات Markdown برای هر تصویر SVG رخ می‌دهد. امکان جایگزینی ذخیره پیش‌فرض و تولید لینک را فراهم می‌کند. اگر مدیریت نشود، SVG به‌صورت محلی با لینک نسبی ذخیره می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | رویداد ذخیره SVG Markdown. |