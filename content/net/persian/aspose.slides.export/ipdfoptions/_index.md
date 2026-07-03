---
title: IPdfOptions
second_title: Aspose.Sildes برای مرجع API .NET
description: گزینه‌هایی را فراهم می‌کند که کنترل می‌کند یک ارائه چگونه در قالب Pdf ذخیره شود.
type: docs
weight: 4000
url: /fa/aspose.slides.export/ipdfoptions/
---
## IPdfOptions رابط

گزینه‌هایی را فراهم می‌کند که کنترل می‌کنند یک ارائه چگونه در قالب Pdf ذخیره شود.

```csharp
public interface IPdfOptions : ISaveOptions
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | حاوی مجموعه‌ای از پرچم‌ها که تعیین می‌کند کدام دسترسی‌ها هنگام باز کردن سند با دسترسی کاربر اعطا شوند. ببینید [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم که Aspose.Slides باید آنها را مشترک در نظر بگیرد، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | اگر `true` باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | رابط ISaveOptions را برمی‌گرداند. فقط-خواندنی [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | نشان می‌دهد آیا فشرده‌سازی کارآمدترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر به Boolean.true تنظیم شود، برای هر تصویر در ارائه، بهینه‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به کوچک‌تر شدن اندازه سند PDF تولید شده می‌گردد. انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و حافظه RAM اضافی مصرف می‌کند، و به‌صورت پیش‌فرض این گزینه Boolean.false است. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | سطح انطباق مورد نظر برای سند PDF تولیدشده. خواندنی/نوشتنی [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True برای رسم قاب سیاه دور هر اسلاید. خواندنی/نوشتنی Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | تعیین می‌کند آیا تمام کاراکترهای قلم باید درون‌ریزی شوند یا تنها زیرمجموعه‌ای استفاده شود. خواندنی/نوشتنی Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True برای درون‌ریزی فونت‌های TrueType برای کاراکترهای ASCII 32-127. فونت‌های کاراکترهای با کد بزرگتر از 127 همیشه درون‌ریزی می‌شوند. خواندنی/نوشتنی Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | رنگ شفاف تصویر را می‌گیرد یا تنظیم می‌کند. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True برای تبدیل تمام داده‌های OLE از ارائه به فایل‌های درون‌ریزی‌شده در PDF حاصل. خواندنی/نوشتنی Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند خروجی را کنترل می‌کنند. فقط-خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | مقدار را برمی‌گرداند یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندنی/نوشتنی Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | تنظیم رمز عبور کاربر برای حفاظت از سند PDF. خواندنی/نوشتنی String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | نشان می‌دهد آیا متن باید به‌عنوان bitmap رستر شود و در PDF ذخیره گردد وقتی قلم از قالب بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF حاصل را برای برخی قلم‌ها بهبود بخشد. خواندنی/نوشتنی Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. خواندنی/نوشتنی Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | مشخص می‌کند آیا سند تولیدشده باید اسلایدهای مخفی را شامل شود یا خیر. مقدار پیش‌فرض `false` است. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن از یک ارائه را می‌گیرد یا تنظیم می‌کند [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | مقدار را برمی‌گرداند یا تنظیم می‌کند که وضوح تصاویر داخل سند PDF را تعیین می‌کند. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. خواندنی/نوشتنی [`PdfTextCompression`](../pdftextcompression). |

### مراجع

* رابط [ISaveOptions](../isaveoptions)
* فضای نام [Aspose.Slides.Export](../../aspose.slides.export)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->