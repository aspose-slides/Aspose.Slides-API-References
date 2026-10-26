---
title: PdfAccessPermissions
second_title: مرجع API Aspose.Slides برای جاوا
description: شامل مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه مجوزهای دسترسی باید هنگام باز شدن سند با دسترسی کاربر اعطا شود.
type: docs
url: /fa/com.aspose.slides/pdfaccesspermissions/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

شامل مجموعه‌ای از پرچم‌ها است که مشخص می‌کند چه مجوزهای دسترسی باید هنگام باز شدن سند با دسترسی کاربر اعطا شود.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [None](#None) | مشخص می‌کند که کاربر هیچ مجوز دسترسی ندارد. |
| [PrintDocument](#PrintDocument) | مشخص می‌کند آیا کاربر می‌تواند سند را چاپ کند (ممکن است در بالاترین سطح کیفیت نباشد، بسته به اینکه بیت [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) نیز تنظیم شده باشد). |
| [ModifyContent](#ModifyContent) | مشخص می‌کند آیا کاربر می‌تواند محتوای سند را با عملیات‌هایی غیر از آن‌که توسط بیت‌های [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)، [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) کنترل می‌شوند، تغییر دهد. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌های سند را کپی یا به‌طور دیگری استخراج کند با عملیات‌هایی غیر از آن‌که توسط بیت [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) کنترل می‌شود. |
| [AddOrModifyFields](#AddOrModifyFields) | مشخص می‌کند آیا کاربر می‌تواند حاشیه‌نویس‌های متنی را اضافه یا اصلاح کند، فیلدهای فرم تعاملی را پر کند، و اگر بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) نیز تنظیم شده باشد، فیلدهای فرم تعاملی (از جمله فیلدهای امضا) را ایجاد یا اصلاح کند. |
| [FillExistingFields](#FillExistingFields) | مشخص می‌کند آیا کاربر می‌تواند فیلدهای فرم تعاملی موجود (از جمله فیلدهای امضا) را پر کند، حتی اگر بیت [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) پاک باشد. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌ها را برای پشتیبانی از دسترسی برای کاربران دارای ناتوانی یا برای مقاصد دیگر استخراج کند. |
| [AssembleDocument](#AssembleDocument) | مشخص می‌کند آیا کاربر می‌تواند سند را ترکیب کند (صفحات را درج، چرخش یا حذف کرده و نشانک‌ها یا تصویرهای بندانگشتی ایجاد کند)، حتی اگر بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) پاک باشد. |
| [HighQualityPrint](#HighQualityPrint) | مشخص می‌کند آیا کاربر می‌تواند سند را به نمایی چاپ کند که از آن می‌توان یک نسخه دیجیتال دقیق از محتوای PDF تولید کرد. |
### هیچ {#None}
```
public static final int None
```

مشخص می‌کند که کاربر هیچ مجوز دسترسی ندارد.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

مشخص می‌کند آیا کاربر می‌تواند سند را چاپ کند (ممکن است در بالاترین سطح کیفیت نباشد، بسته به اینکه بیت [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) نیز تنظیم شده باشد).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

مشخص می‌کند آیا کاربر می‌تواند محتوای سند را با عملیات‌هایی غیر از آن‌که توسط بیت‌های [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)، [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) کنترل می‌شوند، تغییر دهد.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌های سند را کپی یا به‌طور دیگری استخراج کند با عملیات‌هایی غیر از آن‌که توسط بیت [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) کنترل می‌شود.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

مشخص می‌کند آیا کاربر می‌تواند حاشیه‌نویس‌های متنی را اضافه یا اصلاح کند، فیلدهای فرم تعاملی را پر کند، و اگر بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) نیز تنظیم شده باشد، فیلدهای فرم تعاملی (از جمله فیلدهای امضا) را ایجاد یا اصلاح کند.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

مشخص می‌کند آیا کاربر می‌تواند فیلدهای فرم تعاملی موجود (از جمله فیلدهای امضا) را پر کند، حتی اگر بیت [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) پاک باشد.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

مشخص می‌کند آیا کاربر می‌تواند متن و گرافیک‌ها را برای پشتیبانی از دسترسی برای کاربران دارای ناتوانی یا برای مقاصد دیگر استخراج کند.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

مشخص می‌کند آیا کاربر می‌تواند سند را ترکیب کند (صفحات را درج، چرخش یا حذف کرده و نشانک‌ها یا تصویرهای بندانگشتی ایجاد کند)، حتی اگر بیت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) پاک باشد.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

مشخص می‌کند آیا کاربر می‌تواند سند را به نمایی چاپ کند که از آن می‌توان یک نسخه دیجیتال دقیق از محتوای PDF تولید کرد. هنگامی که این بیت پاک باشد (و بیت [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) تنظیم شده باشد)، چاپ به نمایی سطح پایین از ظاهر محدود می‌شود که ممکن است کیفیت کاهش یافته‌ای داشته باشد.