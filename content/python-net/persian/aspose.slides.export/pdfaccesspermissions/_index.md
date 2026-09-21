---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/pdfaccesspermissions/
---
## شمارش PdfAccessPermissions

حاوی مجموعه‌ای از پرچم‌ها است که مشخص می‌کند کدام مجوزهای دسترسی باید هنگام باز شدن سند با دسترسی کاربر اعطا شوند.

نوع PdfAccessPermissions اعضای زیر را نمایان می‌کند:

## فیلدها

| فیلد | توضیح |
| :- | :- |
| NONE | مشخص می‌کند که کاربر مجوز دسترسی ندارد. |
| PRINT_DOCUMENT | مشخص می‌کند آیا کاربر می‌تواند سند را چاپ کند (ممکن است در بالاترین سطح کیفیت نباشد، بسته به <br/>            آیا بیت [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) نیز تنظیم شده است). |
| MODIFY_CONTENT | مشخص می‌کند آیا کاربر می‌تواند محتوای سند را با عملیات‌هایی غیر از آنهایی که توسط<br/>            بیت‌های [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) کنترل می‌شوند، تغییر دهد. |
| COPY_TEXT_AND_GRAPHICS | مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌های سند را کپی یا به‌طور دیگر استخراج کند توسط عملیات <br/>            غیر از آنهایی که توسط بیت [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) کنترل می‌شوند. |
| ADD_OR_MODIFY_FIELDS | مشخص می‌کند آیا کاربر می‌تواند حاشیه‌نویسی‌های متنی را اضافه یا تغییر دهد، فیلدهای فرم تعاملی را پر کند، و، اگر بیت<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) نیز تنظیم شده باشد، فیلدهای فرم تعاملی را (از جمله فیلدهای امضا) ایجاد یا تغییر دهد. |
| FILL_EXISTING_FIELDS | مشخص می‌کند آیا کاربر می‌تواند فیلدهای فرم تعاملی موجود (از جمله فیلدهای امضا) را پر کند، حتی اگر<br/>            بیت [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) پاک باشد. |
| EXTRACT_TEXT_AND_GRAPHICS | مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌ها را به‌منظور دسترس‌پذیری برای کاربران دارای ناتوانی<br/>            یا برای مقاصد دیگر استخراج کند. |
| ASSEMBLE_DOCUMENT | مشخص می‌کند آیا کاربر می‌تواند سند را ترکیب کند (صفحات را درج، چرخاندن یا حذف کرده و نشانک‌ها یا<br/>            تصاویر بندانگشتی ایجاد کند)، حتی اگر بیت [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) پاک باشد. |
| HIGH_QUALITY_PRINT | مشخص می‌کند آیا کاربر می‌تواند سند را به شکلی چاپ کند که از آن یک نسخه دیجیتال دقیق از<br/>            محتوای PDF تولید شود. وقتی این بیت پاک باشد (و بیت [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/fa/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) تنظیم شده باشد)،<br/>            چاپ به نمایش سطح پایین‌تری از ظاهر محدود می‌شود، که ممکن است کیفیت کاهش‌یافته‌ای داشته باشد. |

### موارد مرتبط
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)