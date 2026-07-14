---
title: PdfOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب Pdf را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/pdfoptions/
---
**ارث‌برداری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب Pdf را کنترل می‌کند.

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
>  // یک نمونه از کلاس Presentation ایجاد می‌کند که فایل PowerPoint را نمایندگی می‌کند
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // یک نمونه از کلاس PdfOptions ایجاد می‌کند
>      PdfOptions pdfOptions = new PdfOptions();
>      // اسلایدهای پنهان را اضافه می‌کند
>      pdfOptions.setShowHiddenSlides(true);
>      // ارائه را به صورت PDF ذخیره می‌کند
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // یک شی Presentation ایجاد می‌کند که فایل PowerPoint را نمایندگی می‌کند
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // یک نمونه از کلاس PdfOptions ایجاد می‌کند
>      PdfOptions pdfOptions = new PdfOptions();
>      // رمز عبور PDF و مجوزهای دسترسی را تنظیم می‌کند
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
>  // یک شی Presentation ایجاد می‌کند که یک فایل ارائه را نمایندگی می‌کند
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // تنظیم نوع و اندازه اسلاید
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

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | سازنده پیش‌فرض. |
## متدها

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند خروجی را کنترل می‌کند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولیدی باید اسلایدهای پنهان را شامل شود یا خیر. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولیدی باید اسلایدهای پنهان را شامل شود یا خیر. |
| [getTextCompression()](#getTextCompression--) | نوع فشرده‌سازی مورد استفاده برای تمام محتویات متنی در سند را مشخص می‌کند. |
| [setTextCompression(int value)](#setTextCompression-int-) | نوع فشرده‌سازی مورد استفاده برای تمام محتویات متنی در سند را مشخص می‌کند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود یا خیر. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود یا خیر. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | تعیین می‌کند که آیا Aspose.Slides فونت‌های عمومی را برای متن ASCII (محدوده کد 33..127) جاسازی خواهد کرد یا خیر. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | تعیین می‌کند که آیا Aspose.Slides فونت‌های عمومی را برای متن ASCII (محدوده کد 33..127) جاسازی خواهد کرد یا خیر. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید آن‌ها را عمومی در نظر بگیرد، برمی‌گرداند یا تنظیم می‌کند. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید آن‌ها را عمومی در نظر بگیرد، برمی‌گرداند یا تنظیم می‌کند. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | نشان می‌دهد که آیا متن باید به‌صورت بیت‌مپ رستر شود و در PDF ذخیره گردد وقتی قلم از استایل بولد پشتیبانی نمی‌کند. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | نشان می‌دهد که آیا متن باید به‌صورت بیت‌مپ رستر شود و در PDF ذخیره گردد وقتی قلم از استایل بولد پشتیبانی نمی‌کند. |
| [getJpegQuality()](#getJpegQuality--) | یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. |
| [getCompliance()](#getCompliance--) | سطح انطباق موردنظر برای سند PDF تولید‌شده. |
| [setCompliance(int value)](#setCompliance-int-) | سطح انطباق موردنظر برای سند PDF تولید‌شده. |
| [getPassword()](#getPassword--) | تنظیم رمز عبور کاربر برای محافظت از سند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تنظیم رمز عبور کاربر برای محافظت از سند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه دسترسی‌هایی باید هنگام باز کردن سند با دسترسی کاربر اعطا شوند. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه دسترسی‌هایی باید هنگام باز کردن سند با دسترسی کاربر اعطا شوند. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | درست برای کشیدن قاب سیاه دور هر اسلاید. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | درست برای کشیدن قاب سیاه دور هر اسلاید. |
| [getImageTransparentColor()](#getImageTransparentColor--) | رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | اگر درست باشد، رنگ شفافیت مشخص‌شده را به تصویر اعمال می‌کند. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | اگر درست باشد، رنگ شفافیت مشخص‌شده را به تصویر اعمال می‌کند. |
| [getIncludeOleData()](#getIncludeOleData--) | درست برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | درست برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

سازنده پیش‌فرض.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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

حالت قرارگیری اسلایدها بر روی صفحه هنگام خروجی گرفتن از یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند خروجی را کنترل می‌کند. فقط خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولیدی باید اسلایدهای پنهان را شامل شود یا خیر. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولیدی باید اسلایدهای پنهان را شامل شود یا خیر. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

نوع فشرده‌سازی مورد استفاده برای تمام محتویات متنی در سند را مشخص می‌کند. قابل خواندن/نوشتن [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

مقدار پیش‌فرض [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**بازگشت:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

نوع فشرده‌سازی مورد استفاده برای تمام محتویات متنی در سند را مشخص می‌کند. قابل خواندن/نوشتن [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

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

نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود یا خیر. اگر به true تنظیم شود، برای هر تصویر در ارائه الگوریتم فشرده‌سازی مناسب‌ترین انتخاب می‌شود که منجر به کاهش اندازه سند PDF می‌شود.

--------------------

انتخاب نسبت فشرده‌سازی تصویر مؤثر، محاسباتی گران است و مقدار RAM بیشتری مصرف می‌کند، و به‌طور پیش‌فرض false است.

--------------------

مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود یا خیر. اگر به true تنظیم شود، برای هر تصویر در ارائه الگوریتم فشرده‌سازی مناسب‌ترین انتخاب می‌شود که منجر به کاهش اندازه سند PDF می‌شود.

--------------------

انتخاب نسبت فشرده‌سازی تصویر مؤثر، محاسباتی گران است و مقدار RAM بیشتری مصرف می‌کند، و به‌طور پیش‌فرض false است.

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

تعیین می‌کند که آیا Aspose.Slides فونت‌های عمومی را برای متن ASCII (محدوده کد 33..127) جاسازی خواهد کرد یا خیر. فونت‌های با کد بزرگتر از 127 همیشه جاسازی می‌شوند. فهرست فونت‌های عمومی شامل ۱۴ فونت پایه PDF و فونت‌های اضافی تعریف‌شده توسط کاربر است. قابل خواندن/نوشتن boolean.

--------------------

مقدار پیش‌فرض **true**.

**بازگشت:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

تعیین می‌کند که آیا Aspose.Slides فونت‌های عمومی را برای متن ASCII (محدوده کد 33..127) جاسازی خواهد کرد یا خیر. فونت‌های با کد بزرگتر از 127 همیشه جاسازی می‌شوند. فهرست فونت‌های عمومی شامل ۱۴ فونت پایه PDF و فونت‌های اضافی تعریف‌شده توسط کاربر است. قابل خواندن/نوشتن boolean.

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

یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید آن‌ها را عمومی در نظر بگیرد، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String[].

**بازگشت:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید آن‌ها را عمومی در نظر بگیرد، برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String[].

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. قابل خواندن/نوشتن boolean.

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

تعیین می‌کند که آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. قابل خواندن/نوشتن boolean.

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

نشان می‌دهد که آیا متن باید به‌صورت بیت‌مپ رستر شود و در PDF ذخیره گردد وقتی قلم از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF حاصل را برای برخی قلم‌ها بهبود بخشد. قابل خواندن/نوشتن boolean.

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

نشان می‌دهد که آیا متن باید به‌صورت بیت‌مپ رستر شود و در PDF ذخیره گردد وقتی قلم از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF حاصل را برای برخی قلم‌ها بهبود بخشد. قابل خواندن/نوشتن boolean.

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

یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن byte.

--------------------

فقط زمانی مؤثر است که سند شامل تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 باشد که 0 به معنای کم‌ترین کیفیت ولی بیش‌ترین فشرده‌سازی و 100 به معنای بالاترین کیفیت ولی کم‌ترین فشرده‌سازی است.

مقدار پیش‌فرض **100**.

**بازگشت:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

یک مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن byte.

--------------------

فقط زمانی مؤثر است که سند شامل تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 باشد که 0 به معنای کم‌ترین کیفیت ولی بیش‌ترین فشرده‌سازی و 100 به معنای بالاترین کیفیت ولی کم‌ترین فشرده‌سازی است.

مقدار پیش‌فرض **100**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

سطح انطباق موردنظر برای سند PDF تولید‌شده. قابل خواندن/نوشتن [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

مقدار پیش‌فرض [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**بازگشت:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

سطح انطباق موردنظر برای سند PDF تولید‌شده. قابل خواندن/نوشتن [PdfCompliance](../../com.aspose.slides/pdfcompliance).

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

تنظیم رمز عبور کاربر برای محافظت از سند PDF. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

تنظیم رمز عبور کاربر برای محافظت از سند PDF. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه دسترسی‌هایی باید هنگام باز کردن سند با دسترسی کاربر اعطا شوند. ببینید [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه دسترسی‌هایی باید هنگام باز کردن سند با دسترسی کاربر اعطا شوند. ببینید [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. قابل خواندن/نوشتن boolean.

--------------------

مقدار پیش‌فرض **true**. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. اگر SaveMetafilesAsPng به true تنظیم شود، تصویر متافایل منبع به فرمت PNG تبدیل شده و به‌عنوان تصویر رستری در PDF ذخیره می‌شود. اگر به false تنظیم شود، متافایل منبع به گرافیک برداری PDF تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. برای مثال، اگر متافایل به PNG تبدیل شود، ممکن است در مقیاس‌بندی سند نهایی کاهش کیفیتی ایجاد شود. اگر به گرافیک برداری PDF تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده PDF ایجاد شود.

**بازگشت:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. قابل خواندن/نوشتن boolean.

--------------------

مقدار پیش‌فرض **true**. سند PDF می‌تواند شامل گرافیک‌های برداری و تصاویر رستری باشد. اگر SaveMetafilesAsPng به true تنظیم شود، تصویر متافایل منبع به فرمت PNG تبدیل شده و به‌عنوان تصویر رستری در PDF ذخیره می‌شود. اگر به false تنظیم شود، متافایل منبع به گرافیک برداری PDF تبدیل می‌شود. هر رویکرد مزایا و معایبی دارد. برای مثال، اگر متافایل به PNG تبدیل شود، ممکن است در مقیاس‌بندی سند نهایی کاهش کیفیتی ایجاد شود. اگر به گرافیک برداری PDF تبدیل شود، ممکن است مشکلات عملکردی در ابزار مشاهده PDF ایجاد شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن float.

مقدار: اثر این پارامتر به چند عامل وابسته است. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار ویژگی، اندازه تصویر منبع و اندازه قاب تصویر محاسبه کند. استفاده از مقادیر مشابه ممکن است همان نتیجه را بدهد. توصیه می‌شود از گام 16 یا 32 برای مشاهده اثر استفاده کنید.

--------------------

این ویژگی بر حجم فایل، زمان خروجی و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96**.

**بازگشت:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

یک مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن float.

مقدار: اثر این پارامتر به چند عامل وابسته است. الگوریتم سعی می‌کند بهترین اندازه تصویر خروجی را بر اساس مقدار ویژگی، اندازه تصویر منبع و اندازه قاب تصویر محاسبه کند. استفاده از مقادیر مشابه ممکن است همان نتیجه را بدهد. توصیه می‌شود از گام 16 یا 32 برای مشاهده اثر استفاده کنید.

--------------------

این ویژگی بر حجم فایل، زمان خروجی و کیفیت تصویر تأثیر می‌گذارد.

مقدار پیش‌فرض **96**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

درست برای کشیدن قاب سیاه دور هر اسلاید. قابل خواندن/نوشتن boolean.

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

درست برای کشیدن قاب سیاه دور هر اسلاید. قابل خواندن/نوشتن boolean.

--------------------

مقدار پیش‌فرض **false**.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفافیت تصویر.

**بازگشت:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

رنگ شفافیت تصویر را دریافت یا تنظیم می‌کند.

مقدار: رنگ شفافیت تصویر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

اگر درست باشد، رنگ شفافیت مشخص‌شده را به تصویر اعمال می‌کند.

**بازگشت:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

اگر درست باشد، رنگ شفافیت مشخص‌شده را به تصویر اعمال می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

درست برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. قابل خواندن/نوشتن boolean .

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

**بازگشت:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

درست برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF حاصل. قابل خواندن/نوشتن boolean .

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