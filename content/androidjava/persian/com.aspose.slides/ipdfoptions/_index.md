---
title: IPdfOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Pdf را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/ipdfoptions/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره ارائه در فرمت Pdf را کنترل می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | نوع فشرده‌سازی که برای تمام محتوای متنی در سند استفاده می‌شود را مشخص می‌کند. |
| [setTextCompression(int value)](#setTextCompression-int-) | نوع فشرده‌سازی که برای تمام محتوای متنی در سند استفاده می‌شود را مشخص می‌کند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به‌ جای پیش‌فرض) برای هر تصویر به‌ صورت خودکار انتخاب شود یا نه. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به‌ جای پیش‌فرض) برای هر تصویر به‌ صورت خودکار انتخاب شود یا نه. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True برای جاسازی قلم‌های true type برای کاراکترهای ASCII ۳۲-۱۲۷. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True برای جاسازی قلم‌های true type برای کاراکترهای ASCII ۳۲-۱۲۷. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند آیا سند تولید-شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند آیا سند تولید-شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، باز می‌گرداند یا تنظیم می‌کند. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، باز می‌گرداند یا تنظیم می‌کند. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | تعیین می‌کند آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | تعیین می‌کند آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | نشان می‌دهد آیا متن باید به‌صورت بیت‌مپ رستر شده و در PDF ذخیره شود وقتی قلم از استایل بولد پشتیبانی نمی‌کند. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | نشان می‌دهد آیا متن باید به‌صورت بیت‌مپ رستر شده و در PDF ذخیره شود وقتی قلم از استایل بولد پشتیبانی نمی‌کند. |
| [getJpegQuality()](#getJpegQuality--) | یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. |
| [getCompliance()](#getCompliance--) | سطح انطباق مورد نظر برای سند PDF تولید-شده. |
| [setCompliance(int value)](#setCompliance-int-) | سطح انطباق مورد نظر برای سند PDF تولید-شده. |
| [getPassword()](#getPassword--) | تنظیم رمزعبور کاربر برای محافظت از سند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تنظیم رمزعبور کاربر برای محافظت از سند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | شامل مجموعه‌ای از پرچم‌هاست که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | شامل مجموعه‌ای از پرچم‌هاست که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True برای تبدیل تمام متافایل‌های استفاده-شده در ارائه به تصویر PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True برای تبدیل تمام متافایل‌های استفاده-شده در ارائه به تصویر PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True برای رسم قاب سیاه دور هر اسلاید. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True برای رسم قاب سیاه دور هر اسلاید. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | اگر true باشد، رنگ شفافیت مشخص‌شده به تصویر اعمال می‌شود. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | اگر true باشد، رنگ شفافیت مشخص‌شده به تصویر اعمال می‌شود. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادر-شده کنترل می‌کند. |
| [getIncludeOleData()](#getIncludeOleData--) | True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF نهایی. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF نهایی. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

نوع فشرده‌سازی که برای تمام محتوای متنی در سند استفاده می‌شود را مشخص می‌کند. خواندن/نوشتن [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

پیش‌فرض [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate) است.

**بازگشت:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

نوع فشرده‌سازی که برای تمام محتوای متنی در سند استفاده می‌شود را مشخص می‌کند. خواندن/نوشتن [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

پیش‌فرض [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به‌ جای پیش‌فرض) برای هر تصویر به‌ صورت خودکار انتخاب شود یا نه. اگر true تنظیم شود، برای هر تصویر در ارائه مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن اندازه سند PDF می‌شود.

--------------------

انتخاب نسبت فشرده‌سازی مؤثرترین تصویر محاسباتاً سنگین است و حافظه RAM بیشتری می‌طلبد؛ این گزینه به‌ صورت پیش‌فرض false است.

--------------------

پیش‌فرض false است.

**بازگشت:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به‌ جای پیش‌فرض) برای هر تصویر به‌ صورت خودکار انتخاب شود یا نه. اگر true تنظیم شود، برای هر تصویر در ارائه مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن اندازه سند PDF می‌شود.

--------------------

انتخاب نسبت فشرده‌سازی مؤثرترین تصویر محاسباتاً سنگین است و حافظه RAM بیشتری می‌طلبد؛ این گزینه به‌ صورت پیش‌فرض false است.

--------------------

پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True برای جاسازی قلم‌های true type برای کاراکترهای ASCII ۳۲-۱۲۷. قلم‌های با کد کاراکتری بالاتر از ۱۲۷ همیشه جاسازی می‌شوند. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **true** است.

**بازگشت:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True برای جاسازی قلم‌های true type برای کاراکترهای ASCII ۳۲-۱۲۷. قلم‌های با کد کاراکتری بالاتر از ۱۲۷ همیشه جاسازی می‌شوند. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **true** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

مشخص می‌کند آیا سند تولید-شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**بازگشت:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

مشخص می‌کند آیا سند تولید-شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String[].

**بازگشت:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String[].

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

تعیین می‌کند آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **false** است.

**بازگشت:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

تعیین می‌کند آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

نشان می‌دهد آیا متن باید به‌صورت بیت‌مپ رستر شده و در PDF ذخیره شود وقتی قلم از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF نهایی را برای برخی قلم‌ها بهبود بخشد. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **false** است.

**بازگشت:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

نشان می‌دهد آیا متن باید به‌صورت بیت‌مپ رستر شده و در PDF ذخیره شود وقتی قلم از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF نهایی را برای برخی قلم‌ها بهبود بخشد. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن byte.

--------------------

فقط زمانی مؤثر است که سند حاوی تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در فرمت PDF استفاده کنید. مقدار می‌تواند بین ۰ تا ۱۰۰ باشد؛ ۰ پایین‌ترین کیفیت با بیشترین فشرده‌سازی و ۱۰۰ بالاترین کیفیت با کم‌ترین فشرده‌سازی.

مقدار پیش‌فرض **100** است.

**بازگشت:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن byte.

--------------------

فقط زمانی مؤثر است که سند حاوی تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در فرمت PDF استفاده کنید. مقدار می‌تواند بین ۰ تا ۱۰۰ باشد؛ ۰ پایین‌ترین کیفیت با بیشترین فشرده‌سازی و ۱۰۰ بالاترین کیفیت با کم‌ترین فشرده‌سازی.

مقدار پیش‌فرض **100** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

سطح انطباق مورد نظر برای سند PDF تولید-شده. خواندن/نوشتن [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

پیش‌فرض [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17) است.

**بازگشت:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

سطح انطباق مورد نظر برای سند PDF تولید-شده. خواندن/نوشتن [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

پیش‌فرض [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17) است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

تنظیم رمزعبور کاربر برای محافظت از سند PDF. خواندن/نوشتن String.

**بازگشت:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

تنظیم رمزعبور کاربر برای محافظت از سند PDF. خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

شامل مجموعه‌ای از پرچم‌هاست که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. ببینید [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگشت:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

شامل مجموعه‌ای از پرچم‌هاست که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. ببینید [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True برای تبدیل تمام متافایل‌های استفاده-شده در ارائه به تصویر PNG. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **true** است. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. اگر SaveMetafilesAsPng برابر true باشد، تصویر متافایل منبع به فرمت PNG تبدیل و به‌ عنوان تصویر رستری در PDF ذخیره می‌شود. اگر برابر false باشد، متافایل منبع به گرافیک برداری PDF تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. به عنوان مثال، اگر متافایل به PNG تبدیل شود، ممکن است در حین بزرگ‌نمایی سند نهایی کیفیتی از دست برود. اگر به گرافیک برداری PDF تبدیل شود، ممکن است مشکلات عملکردی در ابزارهای مشاهده PDF ایجاد شود.

**بازگشت:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True برای تبدیل تمام متافایل‌های استفاده-شده در ارائه به تصویر PNG. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **true** است. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. اگر SaveMetafilesAsPng برابر true باشد، تصویر متافایل منبع به فرمت PNG تبدیل و به‌ عنوان تصویر رستری در PDF ذخیره می‌شود. اگر برابر false باشد، متافایل منبع به گرافیک برداری PDF تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. به عنوان مثال، اگر متافایل به PNG تبدیل شود، ممکن است در حین بزرگ‌نمایی سند نهایی کیفیتی از دست برود. اگر به گرافیک برداری PDF تبدیل شود، ممکن است مشکلات عملکردی در ابزارهای مشاهده PDF ایجاد شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

مقدار: اثر این پارامتر به چند عامل بستگی دارد. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار ویژگی، اندازه تصویر منبع و اندازه چارچوب تصویر به-دست آورد. استفاده از مقادیر مشابه ممکن است نتیجهٔ یکسانی بدهد. توصیه می‌شود گام ۱۶ یا ۳۲ برای مشاهدهٔ اثر استفاده شود.

--------------------

این ویژگی بر حجم فایل، زمان خروجی‌گیری و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96** است.

**بازگشت:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را باز می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن float.

مقدار: اثر این پارامتر به چند عامل بستگی دارد. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار ویژگی، اندازه تصویر منبع و اندازه چارچوب تصویر به-دست آورد. استفاده از مقادیر مشابه ممکن است نتیجهٔ یکسانی بدهد. توصیه می‌شود گام ۱۶ یا ۳۲ برای مشاهدهٔ اثر استفاده شود.

--------------------

این ویژگی بر حجم فایل، زمان خروجی‌گیری و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True برای رسم قاب سیاه دور هر اسلاید. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **false** است.

**بازگشت:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True برای رسم قاب سیاه دور هر اسلاید. خواندن/نوشتن boolean.

--------------------

پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفافیت تصویر.

**بازگشت:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفافیت تصویر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

اگر true باشد، رنگ شفافیت مشخص‌شده به تصویر اعمال می‌شود.

**بازگشت:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

اگر true باشد، رنگ شفافیت مشخص‌شده به تصویر اعمال می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادر-شده کنترل می‌کند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF نهایی. خواندن/نوشتن  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

پیش‌فرض  **false**  است.

**بازگشت:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF نهایی. خواندن/نوشتن  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

پیش‌فرض  **false**  است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |