---
title: PdfOptions
second_title: Aspose.Slides برای جاوا مرجع API
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب Pdf را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/pdfoptions/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)  
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

پیکربندی‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در فرمت Pdf کنترل می‌کند.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // یک نمونه از کلاس PdfOptions ایجاد می‌کند
>      PdfOptions pdfOptions = new PdfOptions();
>      // کیفیت Jpeg را تنظیم می‌کند
>      pdfOptions.setJpegQuality((byte)90);
>      // رفتار متافایل‌ها را تنظیم می‌کند
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // سطح فشرده‌سازی متن را تنظیم می‌کند
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // استاندارد PDF را تعریف می‌کند
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // ارائه را به صورت PDF ذخیره می‌کند
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // یک نمونه از کلاس Presentation که یک فایل PowerPoint را نشان می‌دهد ایجاد می‌کند
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // یک نمونه از کلاس PdfOptions ایجاد می‌کند
>      PdfOptions pdfOptions = new PdfOptions();
>      // اسلایدهای مخفی را اضافه می‌کند
>      pdfOptions.setShowHiddenSlides(true);
>      // ارائه را به صورت PDF ذخیره می‌کند
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // یک نمونه از شیء Presentation که یک فایل PowerPoint را نشان می‌دهد ایجاد می‌کند
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // یک نمونه از کلاس PdfOptions ایجاد می‌کند
>      PdfOptions pdfOptions = new PdfOptions();
>      // رمز عبور PDF و دسترسی‌های مورد نیاز را تنظیم می‌کند
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // ارائه را به صورت PDF ذخیره می‌کند
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // یک نمونه از شیء Presentation که یک فایل ارائه را نشان می‌دهد ایجاد می‌کند
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // تنظیم نوع اسلاید و اندازه
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | سازنده پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها در صفحه هنگام استخراج ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها در صفحه هنگام استخراج ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند استخراج‌شده کنترل می‌کند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند آیا سند تولیدشده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند آیا سند تولیدشده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getTextCompression()](#getTextCompression--) | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. |
| [setTextCompression(int value)](#setTextCompression-int-) | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | نشان می‌دهد آیا فشرده‌سازی مؤثرتر (به‌جای پیش‌فرض) برای هر تصویر به‌صورت خودکار انتخاب شود یا نه. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | نشان می‌دهد آیا فشرده‌سازی مؤثرتر (به‌جای پیش‌فرض) برای هر تصویر به‌صورت خودکار انتخاب شود یا نه. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | تعیین می‌کند آیا Aspose.Slides فونت‌های رایج برای متون ASCII (بازه کد 33..127) را تعبیه می‌کند یا خیر. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | تعیین می‌کند آیا Aspose.Slides فونت‌های رایج برای متون ASCII (بازه کد 33..127) را تعبیه می‌کند یا خیر. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | آرایه‌ای از نام‌های کاربری فونت‌های خانواده‌ای که Aspose.Slides باید به‌عنوان رایج در نظر بگیرد را دریافت یا تنظیم می‌کند. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | آرایه‌ای از نام‌های کاربری فونت‌های خانواده‌ای که Aspose.Slides باید به‌عنوان رایج در نظر بگیرد را دریافت یا تنظیم می‌کند. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | تعیین می‌کند آیا تمام کاراکترهای فونت باید تعبیه شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | تعیین می‌کند آیا تمام کاراکترهای فونت باید تعبیه شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | نشان می‌دهد آیا متن باید به‌صورت bitmap رستر شود و در PDF ذخیره شود وقتی فونت از استایل بولد پشتیبانی نمی‌کند. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | نشان می‌دهد آیا متن باید به‌صورت bitmap رستر شود و در PDF ذخیره شود وقتی فونت از استایل بولد پشتیبانی نمی‌کند. |
| [getJpegQuality()](#getJpegQuality--) | مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را دریافت یا تنظیم می‌کند. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را دریافت یا تنظیم می‌کند. |
| [getCompliance()](#getCompliance--) | سطح تطابق مورد نیاز برای سند PDF تولیدشده را مشخص می‌کند. |
| [setCompliance(int value)](#setCompliance-int-) | سطح تطابق مورد نیاز برای سند PDF تولیدشده را مشخص می‌کند. |
| [getPassword()](#getPassword--) | تنظیم رمز عبور کاربر برای حفاظت از سند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تنظیم رمز عبور کاربر برای حفاظت از سند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | true برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | true برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را دریافت یا تنظیم می‌کند. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را دریافت یا تنظیم می‌کند. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | true برای کشیدن قاب سیاه دور هر اسلاید. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | true برای کشیدن قاب سیاه دور هر اسلاید. |
| [getImageTransparentColor()](#getImageTransparentColor--) | رنگ شفاف تصویر را دریافت یا تنظیم می‌کند. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | رنگ شفاف تصویر را دریافت یا تنظیم می‌کند. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | اگر true باشد، رنگ شفاف مشخص‌شده را به تصویر اعمال می‌کند. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | اگر true باشد، رنگ شفاف مشخص‌شده را به تصویر اعمال می‌کند. |
| [getIncludeOleData()](#getIncludeOleData--) | true برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های تعبیه‌شده در PDF نتیجه. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | true برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های تعبیه‌شده در PDF نتیجه. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

سازنده پیش‌فرض.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها در صفحه هنگام استخراج ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها در صفحه هنگام استخراج ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند استخراج‌شده کنترل می‌کند. فقط خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند آیا سند تولیدشده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**بازگشت:**  
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند آیا سند تولیدشده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. قابل خواندن/نوشتن [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

مقدار پیش‌فرض [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**بازگشت:**  
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. قابل خواندن/نوشتن [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

مقدار پیش‌فرض [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

نشان می‌دهد آیا فشرده‌سازی مؤثرتر (به‌جای پیش‌فرض) برای هر تصویر به‌صورت خودکار انتخاب شود یا نه. اگر true باشد، برای هر تصویر در ارائه مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن حجم سند PDF می‌شود.

--------------------

انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار RAM بیشتری مصرف می‌کند؛ این گزینه به‌صورت پیش‌فرض false است.

--------------------

مقدار پیش‌فرض false است.

**بازگشت:**  
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

نشان می‌دهد آیا فشرده‌سازی مؤثرتر (به‌جای پیش‌فرض) برای هر تصویر به‌صورت خودکار انتخاب شود یا نه. اگر true باشد، برای هر تصویر در ارائه مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن حجم سند PDF می‌شود.

--------------------

انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار RAM بیشتری مصرف می‌کند؛ این گزینه به‌صورت پیش‌فرض false است.

--------------------

مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

تعیین می‌کند آیا Aspose.Slides فونت‌های رایج برای متون ASCII (بازه کد 33..127) را تعبیه می‌کند. فونت‌های با کد بالاتر از 127 همیشه تعبیه می‌شوند. فهرست فونت‌های رایج شامل ۱۴ فونت پایه PDF و فونت‌های کاربری اضافه شده است. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **true**.

**بازگشت:**  
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

تعیین می‌کند آیا Aspose.Slides فونت‌های رایج برای متون ASCII (بازه کد 33..127) را تعبیه می‌کند. فونت‌های با کد بالاتر از 127 همیشه تعبیه می‌شوند. فهرست فونت‌های رایج شامل ۱۴ فونت پایه PDF و فونت‌های کاربری اضافه شده است. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **true**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

آرایه‌ای از نام‌های کاربری فونت‌های خانواده‌ای که Aspose.Slides باید به‌عنوان رایج در نظر بگیرد را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن String[].

**بازگشت:**  
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

آرایه‌ای از نام‌های کاربری فونت‌های خانواده‌ای که Aspose.Slides باید به‌عنوان رایج در نظر بگیرد را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن String[].

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

تعیین می‌کند آیا تمام کاراکترهای فونت باید تعبیه شوند یا فقط زیرمجموعه‌ای استفاده شود. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**  
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

تعیین می‌کند آیا تمام کاراکترهای فونت باید تعبیه شوند یا فقط زیرمجموعه‌ای استفاده شود. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **false**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

نشان می‌دهد آیا متن باید به‌صورت bitmap رستر شود و در PDF ذخیره شود وقتی فونت از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF خروجی را برای برخی فونت‌ها بهبود دهد. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**  
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

نشان می‌دهد آیا متن باید به‌صورت bitmap رستر شود و در PDF ذخیره شود وقتی فونت از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF خروجی را برای برخی فونت‌ها بهبود دهد. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **false**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

مقداری که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن byte.

--------------------

فقط زمانی اثر دارد که سند شامل تصاویر JPEG باشد.

از این خصوصیت برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در فرمت PDF استفاده کنید. مقدار می‌تواند بین ۰ تا ۱۰۰ باشد؛ ۰ به معنای کمترین کیفیت ولی بیشترین فشرده‌سازی و ۱۰۰ به معنای بالاترین کیفیت ولی کمترین فشرده‌سازی.

مقدار پیش‌فرض **100**.

**بازگشت:**  
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

مقداری که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن byte.

--------------------

فقط زمانی اثر دارد که سند شامل تصاویر JPEG باشد.

از این خصوصیت برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در فرمت PDF استفاده کنید. مقدار می‌تواند بین ۰ تا ۱۰۰ باشد؛ ۰ به معنای کمترین کیفیت ولی بیشترین فشرده‌سازی و ۱۰۰ به معنای بالاترین کیفیت ولی کمترین فشرده‌سازی.

مقدار پیش‌فرض **100**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

سطح تطابق مورد نیاز برای سند PDF تولیدشده را تعیین می‌کند. قابل خواندن/نوشتن [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

مقدار پیش‌فرض [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**بازگشت:**  
int

### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

سطح تطابق مورد نیاز برای سند PDF تولیدشده را تعیین می‌کند. قابل خواندن/نوشتن [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

مقدار پیش‌فرض [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

تنظیم رمز عبور کاربر برای حفاظت از سند PDF. قابل خواندن/نوشتن String.

**بازگشت:**  
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

تنظیم رمز عبور کاربر برای حفاظت از سند PDF. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. ببینید [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final void setAccessPermissions(int value)
```

مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با دسترسی کاربر اعطا شود. ببینید [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final boolean getSaveMetafilesAsPng()
```

true برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **true**. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستر باشد. اگر SaveMetafilesAsPng برابر true باشد، تصویر متافایل منبع به فرمت PNG تبدیل می‌شود و به‌عنوان تصویر رستر در PDF ذخیره می‌شود. اگر برابر false باشد، متافایل منبع به گرافیک‌های برداری PDF تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. برای مثال، اگر به PNG تبدیل شود، ممکن است در مقیاس‌گذاری سند نهایی کیفیتی از دست بروند. اگر به گرافیک‌های برداری PDF تبدیل شود، ممکن است مشکلات عملکردی در ابزارهای مشاهده PDF ایجاد شود.

**بازگشت:**  
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

true برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **true**. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستر باشد. اگر SaveMetafilesAsPng برابر true باشد، تصویر متافایل منبع به فرمت PNG تبدیل می‌شود و به‌عنوان تصویر رستر در PDF ذخیره می‌شود. اگر برابر false باشد، متافایل منبع به گرافیک‌های برداری PDF تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. برای مثال، اگر به PNG تبدیل شود، ممکن است در مقیاس‌گذاری سند نهایی کیفیتی از دست بروند. اگر به گرافیک‌های برداری PDF تبدیل شود، ممکن است مشکلات عملکردی در ابزارهای مشاهده PDF ایجاد شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

مقداری که وضوح تصاویر داخل سند PDF را تعیین می‌کند را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن float.

مقدار: اثر این پارامتر به چند عامل وابسته است. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار خصوصیت، اندازه تصویر منبع و اندازه قاب تصویر محاسبه کند. استفاده از مقادیر مشابه ممکن است نتیجه یکسانی بدهد. توصیه می‌شود برای داشتن اثر قابل مشاهده از گام ۱۶ یا ۳۲ استفاده شود.

--------------------

این خصوصیت بر حجم فایل، زمان استخراج و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96**.

**بازگشت:**  
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

مقداری که وضوح تصاویر داخل سند PDF را تعیین می‌کند را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن float.

مقدار: اثر این پارامتر به چند عامل وابسته است. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار خصوصیت، اندازه تصویر منبع و اندازه قاب تصویر محاسبه کند. استفاده از مقادیر مشابه ممکن است نتیجه یکسانی بدهد. توصیه می‌شود برای داشتن اثر قابل مشاهده از گام ۱۶ یا ۳۲ استفاده شود.

--------------------

این خصوصیت بر حجم فایل، زمان استخراج و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

true برای کشیدن قاب سیاه دور هر اسلاید. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**  
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

true برای کشیدن قاب سیاه دور هر اسلاید. قابل خواندن/نوشتن بولی.

--------------------

مقدار پیش‌فرض **false**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

رنگ شفاف تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفاف تصویر.

**بازگشت:**  
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

رنگ شفاف تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفاف تصویر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

اگر true باشد، رنگ شفاف مشخص‌شده را به تصویر اعمال می‌کند.

**بازگشت:**  
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

اگر true باشد، رنگ شفاف مشخص‌شده را به تصویر اعمال می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

true برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های تعبیه‌شده در PDF نتیجه. قابل خواندن/نوشتن  بولی .

--------------------

> ```
> مثال:
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

مقدار پیش‌فرض **false** .

**بازگشت:**  
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

true برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های تعبیه‌شده در PDF نتیجه. قابل خواندن/نوشتن  بولی .

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

مقدار پیش‌فرض **false** .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |