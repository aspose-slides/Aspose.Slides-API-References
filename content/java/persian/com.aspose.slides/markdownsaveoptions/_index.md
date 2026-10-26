---
title: MarkdownSaveOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: گزینه‌هایی را که نحوه ذخیره‌سازی ارائه به فرمت markdown را کنترل می‌کنند، نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/markdownsaveoptions/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

نمایانگر گزینه‌هایی است که نحوه ذخیره‌سازی ارائه به قالب markdown را کنترل می‌کند.

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
| [getExportType()](#getExportType--) | مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [setExportType(int value)](#setExportType-int-) | مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [getBasePath()](#getBasePath--) | مسیر پایه‌ای که سند همراه با منابع در آن ذخیره می‌شود را مشخص می‌کند. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | مسیر پایه‌ای که سند همراه با منابع در آن ذخیره می‌شود را مشخص می‌کند. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | نام پوشه‌ای که تصاویر در آن ذخیره می‌شوند را مشخص می‌کند. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | نام پوشه‌ای که تصاویر در آن ذخیره می‌شوند را مشخص می‌کند. |
| [getNewLineType()](#getNewLineType--) | مشخص می‌کند که سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. |
| [setNewLineType(int value)](#setNewLineType-int-) | مشخص می‌کند که سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. |
| [getShowComments()](#getShowComments--) | مشخص می‌کند که آیا سند تولید شده نظرات را نشان دهد یا نه. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | مشخص می‌کند که آیا سند تولید شده نظرات را نشان دهد یا نه. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. |
| [getShowSlideNumber()](#getShowSlideNumber--) | مشخص می‌کند که آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | مشخص می‌کند که آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. |
| [getFlavor()](#getFlavor--) | مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [setFlavor(int value)](#setFlavor-int-) | مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | رشته قالب‌بندی مورد استفاده برای سرصفحه شماره اسلاید در خروجی Markdown را دریافت یا تنظیم می‌کند. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | رشته قالب‌بندی مورد استفاده برای سرصفحه شماره اسلاید در خروجی Markdown را دریافت یا تنظیم می‌کند. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | مشخص می‌کند که کاراکترهای فاصله منظم تکراری در هنگام صادرات به Markdown چگونه پردازش شوند. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | مشخص می‌کند که کاراکترهای فاصله منظم تکراری در هنگام صادرات به Markdown چگونه پردازش شوند. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | اگر به مقدار true تنظیم شود، خطوط خالی یا فقط حاوی فاصله را از خروجی نهایی Markdown حذف می‌کند. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | اگر به مقدار true تنظیم شود، خطوط خالی یا فقط حاوی فاصله را از خروجی نهایی Markdown حذف می‌کند. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | در هنگام صادرات به Markdown برای هر تصویر غیر SVG (bitmap یا metafile) رخ می‌دهد. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | در هنگام صادرات به Markdown برای هر تصویر SVG رخ می‌دهد. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

سازنده.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض TextOnly است.

**بازگشت:**  
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض TextOnly است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

مسیر پایه‌ای که سند همراه با منابع در آن ذخیره می‌شود را مشخص می‌کند. پیش‌فرض مسیر جاری برنامه است.

**بازگشت:**  
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

مسیر پایه‌ای که سند همراه با منابع در آن ذخیره می‌شود را مشخص می‌کند. پیش‌فرض مسیر جاری برنامه است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

نام پوشه‌ای که تصاویر در آن ذخیره می‌شوند را مشخص می‌کند. پیش‌فرض Images است.

**بازگشت:**  
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

نام پوشه‌ای که تصاویر در آن ذخیره می‌شوند را مشخص می‌کند. پیش‌فرض Images است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

مشخص می‌کند که سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. پیش‌فرض Unix است.

**بازگشت:**  
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

مشخص می‌کند که سند تولید شده باید خطوط جدید \\r(Macintosh) یا \\n(Unix) یا \\r\\n(Windows) داشته باشد. پیش‌فرض Unix است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

مشخص می‌کند که آیا سند تولید شده نظرات را نشان دهد یا نه. پیش‌فرض false است.

**بازگشت:**  
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

مشخص می‌کند که آیا سند تولید شده نظرات را نشان دهد یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**بازگشت:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

مشخص می‌کند که آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. پیش‌فرض false است.

**بازگشت:**  
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

مشخص می‌کند که آیا سند تولید شده شماره هر اسلاید را نشان دهد یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض Multi-markdown است.

**بازگشت:**  
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

مشخص می‌کند که از چه مشخصات markdown برای تبدیل ارائه استفاده شود. پیش‌فرض Multi-markdown است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

رشته قالب‌بندی مورد استفاده برای سرصفحه شماره اسلاید در خروجی Markdown را دریافت یا تنظیم می‌کند. قالب باید شامل جای‌گذاری‌کننده "\{0\}" باشد که در زمان صادرات با شماره اسلاید جایگزین می‌شود. مثال: "\# Slide \{0\}" منجر به "\# Slide 1"، "\# Slide 2" و... می‌شود.

**بازگشت:**  
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

رشته قالب‌بندی مورد استفاده برای سرصفحه شماره اسلاید در خروجی Markdown را دریافت یا تنظیم می‌کند. قالب باید شامل جای‌گذاری‌کننده "\{0\}" باشد که در زمان صادرات با شماره اسلاید جایگزین می‌شود. مثال: "\# Slide \{0\}" منجر به "\# Slide 1"، "\# Slide 2" و... می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

مشخص می‌کند که کاراکترهای فاصله منظم تکراری در هنگام صادرات به Markdown چگونه پردازش شوند. این ویژگی تعریف می‌کند که فاصله‌های متوالی:
- به صورت کاراکترهای فاصله عادی حفظ شوند،
- بین فاصله‌های عادی و موجودیت‌های غیرقابل شکست (�) تناوب داشته باشند،
- یا پس از اولین فاصله با یک فضای غیرقابل شکست جایگزین شوند تا ترازبندی بصری در خروجی حفظ شود. مقدار پیش‌فرض [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) است.

**بازگشت:**  
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

مشخص می‌کند که کاراکترهای فاصله منظم تکراری در هنگام صادرات به Markdown چگونه پردازش شوند. این ویژگی تعریف می‌کند که فاصله‌های متوالی:
- به صورت کاراکترهای فاصله عادی حفظ شوند،
- بین فاصله‌های عادی و موجودیت‌های غیرقابل شکست (�) تناوب داشته باشند،
- یا پس از اولین فاصله با یک فضای غیرقابل شکست جایگزین شوند تا ترازبندی بصری در خروجی حفظ شود. مقدار پیش‌فرض [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

اگر به مقدار true تنظیم شود، خطوط خالی یا فقط حاوی فاصله را از خروجی نهایی Markdown حذف می‌کند. پیش‌فرض false است.

**بازگشت:**  
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

اگر به مقدار true تنظیم شود، خطوط خالی یا فقط حاوی فاصله را از خروجی نهایی Markdown حذف می‌کند. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

در هنگام صادرات به Markdown برای هر تصویر غیر SVG (bitmap یا metafile) رخ می‌دهد. امکان سفارشی‌سازی نحوه ذخیره و ارجاع به تصویر فراهم می‌شود. اگر مدیریت نشود، تصویر به‌صورت محلی با یک لینک نسبی ذخیره می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | رویداد ذخیره‌سازی تصویر markdown. |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

در هنگام صادرات به Markdown برای هر تصویر SVG رخ می‌دهد. امکان overriding ذخیره‌سازی پیش‌فرض و تولید لینک فراهم می‌شود. اگر مدیریت نشود، SVG به‌صورت محلی با یک لینک نسبی ذخیره می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | رویداد ذخیره‌سازی تصویر SVG markdown. |