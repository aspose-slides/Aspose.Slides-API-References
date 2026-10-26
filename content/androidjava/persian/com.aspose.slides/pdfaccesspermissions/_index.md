---
title: PdfAccessPermissions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شامل مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه دسترسی‌هایی هنگام باز شدن سند با  دسترسی کاربر باید اعطا شود.
type: docs
url: /fa/com.aspose.slides/pdfaccesspermissions/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

شامل مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه دسترسی‌هایی هنگام باز کردن سند با دسترسی کاربر باید اعطا شود.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [None](#None) | مشخص می‌کند که کاربر دسترسی ندارد. |
| [PrintDocument](#PrintDocument) | مشخص می‌کند آیا کاربر می‌تواند سند را چاپ کند (ممکن است در بالاترین کیفیت نباشد، بسته به اینکه بیت [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) نیز تنظیم شده باشد). |
| [ModifyContent](#ModifyContent) | مشخص می‌کند آیا کاربر می‌تواند محتوای سند را با عملیات‌هایی غیر از آنچه توسط بیت‌های [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields) و [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) کنترل می‌شود، تغییر دهد. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌های سند را با عملیات‌هایی غیر از آنچه توسط بیت [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) کنترل می‌شود، کپی یا استخراج کند. |
| [AddOrModifyFields](#AddOrModifyFields) | مشخص می‌کند آیا کاربر می‌تواند حاشیه‌نویسی‌های متنی را اضافه یا ویرایش کند، فیلدهای فرم تعاملی را پر کند، و در صورت تنظیم بودن بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent)، فیلدهای فرم تعاملی (از جمله فیلدهای امضا) را ایجاد یا ویرایش کند. |
| [FillExistingFields](#FillExistingFields) | مشخص می‌کند آیا کاربر می‌تواند فیلدهای فرم تعاملی موجود (از جمله فیلدهای امضا) را پر کند، حتی اگر بیت [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) پاک باشد. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌ها را برای پشتیبانی از دسترسی کاربران با ناتوانی یا برای اهداف دیگر استخراج کند. |
| [AssembleDocument](#AssembleDocument) | مشخص می‌کند آیا کاربر می‌تواند سند را ترکیب کند (صفحات را وارد، چرخانده یا حذف کند و نشانک‌ها یا تصاویر بندانگشتی ایجاد کند)، حتی اگر بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) پاک باشد. |
| [HighQualityPrint](#HighQualityPrint) | مشخص می‌کند آیا کاربر می‌تواند سند را به گونه‌ای چاپ کند که بتوان یک نسخه دیجیتالی دقیق از محتوای PDF تولید کرد. |
### None {#None}
```
public static final int None
```

مشخص می‌کند که کاربر دسترسی ندارد.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

مشخص می‌کند آیا کاربر می‌تواند سند را چاپ کند (ممکن است در بالاترین کیفیت نباشد، بسته به اینکه بیت [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) نیز تنظیم شده باشد).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

مشخص می‌کند آیا کاربر می‌تواند محتوای سند را با عملیات‌هایی غیر از آنچه توسط بیت‌های [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields) و [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) کنترل می‌شود، تغییر دهد.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌های سند را با عملیات‌هایی غیر از آنچه توسط بیت [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) کنترل می‌شود، کپی یا استخراج کند.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

مشخص می‌کند آیا کاربر می‌تواند حاشیه‌نویسی‌های متنی را اضافه یا ویرایش کند، فیلدهای فرم تعاملی را پر کند، و در صورت تنظیم بودن بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent)، فیلدهای فرم تعاملی (از جمله فیلدهای امضا) را ایجاد یا ویرایش کند.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

مشخص می‌کند آیا کاربر می‌تواند فیلدهای فرم تعاملی موجود (از جمله فیلدهای امضا) را پر کند، حتی اگر بیت [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) پاک باشد.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌ها را برای پشتیبانی از دسترسی کاربران با ناتوانی یا برای اهداف دیگر استخراج کند.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

مشخص می‌کند آیا کاربر می‌تواند سند را ترکیب کند (صفحات را وارد، چرخانده یا حذف کند و نشانک‌ها یا تصاویر بندانگشتی ایجاد کند)، حتی اگر بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) پاک باشد.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

مشخص می‌کند آیا کاربر می‌تواند سند را به گونه‌ای چاپ کند که بتوان یک نسخه دیجیتالی دقیق از محتوای PDF تولید کرد. هنگامی که این بیت پاک باشد (و بیت [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) تنظیم شده باشد)، چاپ به نمای سطح پایین از ظاهر محدود می‌شود که ممکن است کیفیت کاهش‌یافته‌ای داشته باشد.