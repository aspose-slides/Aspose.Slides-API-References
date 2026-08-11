---
title: PdfAccessPermissions
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند کدام مجوزهای دسترسی باید هنگام باز کردن سند با دسترسی کاربر اعطا شوند.
type: docs
weight: 989
url: /fa/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

مجموعه‌ای از پرچم‌ها را شامل می‌شود که مشخص می‌کند کدام مجوزهای دسترسی باید هنگام باز کردن سند با دسترسی کاربر اعطا شوند.

```cpp
enum class PdfAccessPermissions
```

### مقادیر

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | مشخص می‌کند که کاربر هیچ مجوز دسترسی ندارد. |
| PrintDocument | 4 | مشخص می‌کند که آیا کاربر می‌تواند سند را چاپ کند (احتمالاً نه با بالاترین کیفیت، بسته به این که آیا بیت [PdfAccessPermissions::HighQualityPrint](./) نیز تنظیم شده است یا نه). |
| ModifyContent | 8 | مشخص می‌کند که آیا کاربر می‌تواند محتوای سند را با عملیات‌هایی غیر از آنهایی که توسط بیت‌های [PdfAccessPermissions::AddOrModifyFields](./)، [PdfAccessPermissions::FillExistingFields](./) و [PdfAccessPermissions::AssembleDocument](./) کنترل می‌شوند، تغییر دهد. |
| CopyTextAndGraphics | 16 | مشخص می‌کند که آیا کاربر می‌تواند متن و گرافیک‌ها را از سند کپی یا به روشی دیگر استخراج کند، با عملیات‌هایی غیر از آنکه توسط بیت [PdfAccessPermissions::ExtractTextAndGraphics](./) کنترل می‌شود. |
| AddOrModifyFields | 32 | مشخص می‌کند که آیا کاربر می‌تواند حاشیه‌نویسی‌های متنی را اضافه یا تغییر دهد، فیلدهای فرم تعاملی را پر کند، و اگر بیت [PdfAccessPermissions::ModifyContent](./) نیز تنظیم شده باشد، فیلدهای فرم تعاملی (از جمله فیلدهای امضا) را ایجاد یا تغییر دهد. |
| FillExistingFields | 256 | مشخص می‌کند که آیا کاربر می‌تواند فیلدهای فرم تعاملی موجود (از جمله فیلدهای امضا) را پر کند، حتی اگر بیت [PdfAccessPermissions::AddOrModifyFields](./) پاک باشد. |
| ExtractTextAndGraphics | 512 | مشخص می‌کند که آیا کاربر می‌تواند متن و گرافیک‌ها را برای پشتیبانی از دسترسی‌پذیری به کاربران با ناتوانی یا برای سایر اهداف استخراج کند. |
| AssembleDocument | 1024 | مشخص می‌کند که آیا کاربر می‌تواند سند را ترکیب کند (صفحات را درج، چرخش یا حذف کرده و نشانک‌ها یا تصاویر بندانگشتی ایجاد کند)، حتی اگر بیت [PdfAccessPermissions::ModifyContent](./) پاک باشد. |
| HighQualityPrint | 2048 | مشخص می‌کند که آیا کاربر می‌تواند سند را به گونه‌ای چاپ کند که نمایی تولید شود که بتوان یک نسخه دیجیتال دقیق از محتوای PDF را از آن به دست آورد. وقتی این بیت پاک باشد (و بیت [PdfAccessPermissions::PrintDocument](./) تنظیم شده باشد)، چاپ به نمای سطح پایین‌تری از ظاهر محدود می‌شود که ممکن است کیفیت کاهش یافته داشته باشد. |

## موارد مرتبط

* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)