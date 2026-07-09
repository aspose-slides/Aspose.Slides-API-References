---
title: IPdfOptions
second_title: Aspose.Sildes برای مرجع API .NET
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب Pdf را کنترل می‌کند.
type: docs
weight: 4000
url: /fa/aspose.slides.export/ipdfoptions/
---
## IPdfOptions رابط

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی ارائه در قالب Pdf را کنترل می‌کند.

```csharp
public interface IPdfOptions : ISaveOptions
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کند چه مجوزهای دسترسی‌ای هنگام باز شدن سند با دسترسی کاربر اعطا شود. به [`PdfAccessPermissions`](../pdfaccesspermissions) مراجعه کنید. |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | یک آرایه از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های قلم را که Aspose.Slides باید به عنوان قلم‌های عمومی در نظر بگیرد، بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | اگر `true` باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | رابط ISaveOptions را بازمی‌گرداند. فقط‌خواندنی [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | نشان می‌دهد آیا فشرده‌سازی مؤثرترین (به جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر به Boolean.true تنظیم شود، برای هر تصویر در ارائه الگوریتم فشرده‌سازی مناسب‌ترین انتخاب می‌شود که منجر به اندازهٔ کوچکتر سند PDF تولید شده می‌شود. انتخاب بهترین نسبت فشرده‌سازی تصویر هزینهٔ محاسباتی بالایی دارد و مقدار بیشتری RAM مصرف می‌کند، و این گزینه به‌طور پیش‌فرض Boolean.false است. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | سطح انطباق مطلوب برای سند PDF تولید شده. خواندنی/نوشتنی [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | اگر True باشد، قاب سیاه دور هر اسلاید رسم می‌شود. خواندنی/نوشتنی Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | تعیین می‌کند آیا تمام کاراکترهای قلم باید جاسازی شوند یا فقط زیرمجموعه استفاده‌شده. خواندنی/نوشتنی Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | اگر True باشد، قلم‌های TrueType برای کاراکترهای ASCII 32-127 جاسازی می‌شوند. قلم‌های با کدهای کاراکتری بزرگتر از 127 همیشه جاسازی می‌شوند. خواندنی/نوشتنی Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | رنگ شفاف تصویر را بازمی‌گرداند یا تنظیم می‌کند. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | اگر True باشد، تمام داده‌های OLE از ارائه به فایل‌های جاسازی‌شده در PDF تولیدی تبدیل می‌شوند. خواندنی/نوشتنی Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند خروجی را کنترل می‌کند. فقط‌خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | یک مقدار تعیین‌کنندهٔ کیفیت تصاویر JPEG داخل سند PDF را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | تنظیم رمز عبور کاربر برای حفاظت از سند PDF. خواندنی/نوشتنی String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | نشان می‌دهد آیا متن باید به‌صورت bitmap رستر شود و در PDF ذخیره شود وقتی قلم از استایل بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF تولیدی را برای برخی قلم‌ها بهبود بخشد. خواندنی/نوشتنی Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | اگر True باشد، تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG تبدیل می‌شوند. خواندنی/نوشتنی Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | مشخص می‌کند آیا سند تولیدی باید اسلایدهای مخفی را شامل شود یا خیر. پیش‌فرض `false` است. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن از ارائه را بازمی‌گرداند یا تنظیم می‌کند [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | یک مقدار تعیین‌کنندهٔ وضوح تصاویر داخل سند PDF را بازمی‌گرداند یا تنظیم می‌کند. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | نوع فشرده‌سازی مورد استفاده برای تمام محتوای متنی در سند را مشخص می‌کند. خواندنی/نوشتنی [`PdfTextCompression`](../pdftextcompression). |

### موارد مربوط

* رابط [ISaveOptions](../isaveoptions)
* فضای نام [Aspose.Slides.Export](../../aspose.slides.export)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->