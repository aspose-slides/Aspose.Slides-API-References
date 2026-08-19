---
title: IPdfOptions
second_title: Aspose.Slides برای مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Pdf را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/ipdfoptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Pdf را کنترل می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | نوع فشرده‌سازی را که برای تمام محتوای متنی در سند استفاده می‌شود، مشخص می‌کند. |
| [setTextCompression(int value)](#setTextCompression-int-) | نوع فشرده‌سازی را که برای تمام محتوای متنی در سند استفاده می‌شود، مشخص می‌کند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True برای جاسازی قلم‌های true type برای کاراکترهای ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True برای جاسازی قلم‌های true type برای کاراکترهای ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | آرایه‌ای از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، را برمی‌گرداند یا تنظیم می‌کند. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | آرایه‌ای از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، را برمی‌گرداند یا تنظیم می‌کند. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | نشان می‌دهد که آیا متن باید به‌صورت bitmap رستر شده و در PDF ذخیره شود زمانی که قلم از سبک بولد پشتیبانی نمی‌کند. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | نشان می‌دهد که آیا متن باید به‌صورت bitmap رستر شده و در PDF ذخیره شود زمانی که قلم از سبک بولد پشتیبانی نمی‌کند. |
| [getJpegQuality()](#getJpegQuality--) | مقداری که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | مقداری که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. |
| [getCompliance()](#getCompliance--) | سطح سازگاری موردنظر برای سند PDF تولید شده. |
| [setCompliance(int value)](#setCompliance-int-) | سطح سازگاری موردنظر برای سند PDF تولید شده. |
| [getPassword()](#getPassword--) | تنظیم گذرواژه کاربر برای محافظت از سند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تنظیم گذرواژه کاربر برای محافظت از سند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کند کدام مجوزهای دسترسی باید هنگام باز شدن سند با دسترسی کاربر اعطا شود. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کند کدام مجوزهای دسترسی باید هنگام باز شدن سند با دسترسی کاربر اعطا شود. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | مقداری که وضوح تصاویر داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | مقداری که وضوح تصاویر داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True برای کشیدن حاشیهٔ سیاه دور هر اسلاید. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True برای کشیدن حاشیهٔ سیاه دور هر اسلاید. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام استخراج ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام استخراج ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | رنگ شفاف تصویر را دریافت یا تنظیم می‌کند. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | رنگ شفاف تصویر را دریافت یا تنظیم می‌کند. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | اگر True باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | اگر True باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند استخراج‌شده کنترل می‌کنند. |
| [getIncludeOleData()](#getIncludeOleData--) | True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

نوع فشرده‌سازی را که برای تمام محتوای متنی در سند استفاده می‌شود، مشخص می‌کند. خواندنی/نوشتنی [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

پیش‌فرض [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate) است.

**بازگشت:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

نوع فشرده‌سازی را که برای تمام محتوای متنی در سند استفاده می‌شود، مشخص می‌کند. خواندنی/نوشتنی [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

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

نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر بر True تنظیم شود، برای هر تصویر در ارائه، مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن اندازه سند PDF نهایی می‌شود.

--------------------

انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار اضافی RAM مصرف می‌کند، و این گزینه به‌صورت پیش‌فرض False است.

--------------------

پیش‌فرض False است.

**بازگشت:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر بر True تنظیم شود، برای هر تصویر در ارائه، مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن اندازه سند PDF نهایی می‌شود.

--------------------

انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار اضافی RAM مصرف می‌کند، و این گزینه به‌صورت پیش‌فرض False است.

--------------------

پیش‌فرض False است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True برای جاسازی قلم‌های true type برای کاراکترهای ASCII 32-127. قلم‌ها برای کدهای کاراکتر بزرگتر از 127 همیشه جاسازی می‌شوند. خواندنی/نوشتنی boolean.

--------------------

پیش‌فرض **true** است.

**بازگشت:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True برای جاسازی قلم‌های true type برای کاراکترهای ASCII 32-127. قلم‌ها برای کدهای کاراکتر بزرگتر از 127 همیشه جاسازی می‌شوند. خواندنی/نوشتنی boolean.

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

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض False است.

**بازگشت:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض False است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

آرایه‌ای از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String[].

**بازگشت:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

آرایه‌ای از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید به‌عنوان مشترک در نظر بگیرد، را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String[].

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندنی/نوشتنی boolean.

--------------------

پیش‌فرض **false** است.

**بازگشت:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندنی/نوشتنی boolean.

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

نشان می‌دهد که آیا متن باید به‌صورت bitmap رستر شده و در PDF ذخیره شود زمانی که قلم از استایل بولد پشتیبانی نمی‌کند. این رویکرد می‌تواند کیفیت متن در PDF نهایی را برای برخی قلم‌ها بهبود بخشد. خواندنی/نوشتنی boolean.

--------------------

پیش‌فرض **false** است.

**بازگشت:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

نشان می‌دهد که آیا متن باید به‌صورت bitmap رستر شده و در PDF ذخیره شود زمانی که قلم از استایل بولد پشتیبانی نمی‌کند. این رویکرد می‌تواند کیفیت متن در PDF نهایی را برای برخی قلم‌ها بهبود بخشد. خواندنی/نوشتنی boolean.

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

مقداری که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی byte.

--------------------

فقط زمانی که سند شامل تصاویر JPEG باشد، تأثیر دارد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند بین 0 تا 100 باشد که 0 به معنی کم‌ترین کیفیت اما حداکثر فشرده‌سازی و 100 به معنی بهترین کیفیت اما کم‌ترین فشرده‌سازی است.

مقدار پیش‌فرض **100** است.

**بازگشت:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

مقداری که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی byte.

--------------------

فقط زمانی که سند شامل تصاویر JPEG باشد، تأثیر دارد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند بین 0 تا 100 باشد که 0 به معنی کم‌ترین کیفیت اما حداکثر فشرده‌سازی و 100 به معنی بهترین کیفیت اما کم‌ترین فشرده‌سازی است.

مقدار پیش‌فرض **100** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

سطح سازگاری موردنظر برای سند PDF تولید شده. خواندنی/نوشتنی [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

پیش‌فرض [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17) است.

**بازگشت:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

سطح سازگاری موردنظر برای سند PDF تولید شده. خواندنی/نوشتنی [PdfCompliance](../../com.aspose.slides/pdfcompliance).

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

تنظیم گذرواژه کاربر برای محافظت از سند PDF. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

تنظیم گذرواژه کاربر برای محافظت از سند PDF. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کند کدام مجوزهای دسترسی باید هنگام باز شدن سند با دسترسی کاربر اعطا شود. مراجعه کنید به [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کند کدام مجوزهای دسترسی باید هنگام باز شدن سند با دسترسی کاربر اعطا شود. مراجعه کنید به [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. خواندنی/نوشتنی boolean.

--------------------

پیش‌فرض **true** است. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. اگر SaveMetafilesAsPng روی true تنظیم شود، تصویر متافایل منبع به فرمت Png تبدیل شده و به‌عنوان تصویر رستری در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng روی false تنظیم شود، متافایل منبع به گرافیک‌های برداری Pdf تبدیل می‌شود. هر روش مزایا و معایبی دارد. برای مثال، اگر متافایل به PNG تبدیل شود، ممکن است در مقیاس‌گذاری سند نهایی کاهش کیفیت رخ دهد. اگر متافایل به گرافیک‌های برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده Pdf ایجاد شود.

**بازگشت:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. خواندنی/نوشتنی boolean.

--------------------

پیش‌فرض **true** است. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. اگر SaveMetafilesAsPng روی true تنظیم شود، تصویر متافایل منبع به فرمت Png تبدیل شده و به‌عنوان تصویر رستری در Pdf ذخیره می‌شود. اگر SaveMetafilesAsPng روی false تنظیم شود، متافایل منبع به گرافیک‌های برداری Pdf تبدیل می‌شود. هر روش مزایا و معایبی دارد. برای مثال، اگر متافایل به PNG تبدیل شود، ممکن است در مقیاس‌گذاری سند نهایی کاهش کیفیت رخ دهد. اگر متافایل به گرافیک‌های برداری Pdf تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده Pdf ایجاد شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

مقداری که وضوح تصاویر داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

Value: اثر این پارامتر به چند عامل بستگی دارد. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار ویژگی، اندازه تصویر منبع و اندازه چارچوب تصویر به‌دست آورد. استفاده از مقادیر مشابه ویژگی ممکن است همان نتیجه را بدهد. توصیه می‌شود برای مشاهده اثر گام 16 یا 32 را استفاده کنید.

--------------------

این ویژگی بر حجم فایل، زمان استخراج و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96** است.

**بازگشت:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

مقداری که وضوح تصاویر داخل سند PDF را تعیین می‌کند، را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

Value: اثر این پارامتر به چند عامل بستگی دارد. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار ویژگی، اندازه تصویر منبع و اندازه چارچوب تصویر به‌دست آورد. استفاده از مقادیر مشابه ویژگی ممکن است همان نتیجه را بدهد. توصیه می‌شود برای مشاهده اثر گام 16 یا 32 را استفاده کنید.

--------------------

این ویژگی بر حجم فایل، زمان استخراج و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True برای رسم حاشیهٔ سیاه دور هر اسلاید. خواندنی/نوشتنی boolean.

--------------------

پیش‌فرض **false** است.

**بازگشت:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True برای رسم حاشیهٔ سیاه دور هر اسلاید. خواندنی/نوشتنی boolean.

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

حالت قرارگیری اسلایدها بر روی صفحه هنگام استخراج ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

حالت قرارگیری اسلایدها بر روی صفحه هنگام استخراج ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract Color getImageTransparentColor()
```

رنگ شفاف تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفاف تصویر.

**بازگشت:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

رنگ شفاف تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفاف تصویر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

اگر True باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند.

**بازگشت:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

اگر True باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند استخراج‌شده کنترل می‌کنند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. خواندنی/نوشتنی boolean.

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

پیش‌فرض **false** است.

**بازگشت:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. خواندنی/نوشتنی boolean.

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

پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |