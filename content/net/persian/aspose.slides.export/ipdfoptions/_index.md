---
title: IPdfOptions
second_title: Aspose.Sildes برای .NET مرجع API
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیرهٔ ارائه در قالب Pdf را کنترل می‌کند.
type: docs
weight: 4020
url: /fa/aspose.slides.export/ipdfoptions/
---
## IPdfOptions رابط

گزینه‌هایی را فراهم می‌کند که نحوه ذخیرهٔ ارائه در فرمت Pdf را کنترل می‌کند.

```csharp
public interface IPdfOptions : ISaveOptions
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | مجموعه‌ای از پرچم‌ها را شامل می‌شود که تعیین می‌کنند چه مجوزهای دسترسی‌ای هنگام باز شدن سند با دسترسی کاربر اعطا شود. ببینید [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | آرایه‌ای از نام‌های تعریف‌شده توسط کاربر برای خانواده‌های فونت که Aspose.Slides باید به‌عنوان عمومی در نظر بگیرد را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | اگر `true` باشد، رنگ شفاف مشخص‌شده را بر روی تصویر اعمال می‌کند. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | رابط ISaveOptions را برمی‌گرداند. فقط خواندنی [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | نشان می‌دهد که آیا فشرده‌سازی مؤثرترین (به‌جای پیش‌فرض) برای هر تصویر باید به‌صورت خودکار انتخاب شود. اگر به Boolean.true تنظیم شود، برای هر تصویر در ارائه، مناسب‌ترین الگوریتم فشرده‌سازی انتخاب می‌شود که منجر به اندازهٔ کوچکتر سند PDF نهایی می‌شود. انتخاب بهترین نسبت فشرده‌سازی تصویر هزینه محاسباتی بالایی دارد و مقدار اضافی RAM مصرف می‌کند، و این گزینه به‌صورت پیش‌فرض Boolean.false است. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | سطح انطباق مطلوب برای سند PDF تولید شده. خواندن/نوشتن [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | اگر True باشد، چارچوب سیاه دور هر اسلاید کشیده می‌شود. خواندن/نوشتن Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | تعیین می‌کند که آیا تمام کاراکترهای فونت باید جاسازی شوند یا فقط زیرمجموعه‌ای استفاده شود. خواندن/نوشتن Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | اگر True باشد، فونت‌های TrueType برای کاراکترهای ASCII 32-127 جاسازی می‌شوند. فونت‌ها برای کدهای کاراکتری بزرگتر از 127 همیشه جاسازی می‌شوند. خواندن/نوشتن Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | رنگ شفاف تصویر را برمی‌گیرد یا تنظیم می‌کند. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | اگر True باشد، تمام داده‌های OLE موجود در ارائه به فایل‌های جاسازی‌شده در PDF نهایی تبدیل می‌شود. خواندن/نوشتن Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادر شده کنترل می‌کند. فقط خواندنی [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | مقدار تعیین‌کنندهٔ کیفیت تصاویر JPEG داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | تنظیم رمز عبور کاربر برای محافظت از سند PDF. خواندن/نوشتن String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | نشان می‌دهد آیا متن باید به‌صورت bitmap رستر شود و در PDF ذخیره شود وقتی که فونت از سبک بولد پشتیبانی نمی‌کند. این روش می‌تواند کیفیت متن در PDF نهایی را برای برخی فونت‌ها ارتقا دهد. خواندن/نوشتن Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | اگر True باشد، تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG تبدیل می‌شوند. خواندن/نوشتن Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | مشخص می‌کند آیا سند تولید‌شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض `false` است. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن یک ارائه [`ISlidesLayoutOptions`](../islideslayoutoptions) را برمی‌گیرد یا تنظیم می‌کند. |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | مقدار تعیین‌کننده وضوح تصاویر داخل سند PDF را برمی‌گرداند یا تنظیم می‌کند. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | نوع فشرده‌سازی که برای تمام محتوای متنی سند استفاده می‌شود را مشخص می‌کند. خواندن/نوشتن [`PdfTextCompression`](../pdftextcompression). |

### مراجع

* رابط [ISaveOptions](../isaveoptions)
* فضای‌نام [Aspose.Slides.Export](../../aspose.slides.export)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->