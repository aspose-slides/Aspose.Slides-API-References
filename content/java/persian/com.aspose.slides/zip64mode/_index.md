---
title: Zip64Mode
second_title: مرجع API Aspose.Slides برای Java
description: مشخص می‌کند که چه زمانی باید از افزونه‌های فرمت ZIP64 برای فایل OpenXML استفاده شود.
type: docs
url: /fa/com.aspose.slides/zip64mode/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

مشخص می‌کند که چه زمانی باید از افزونه‌های فرمت ZIP64 برای فایل OpenXML استفاده شود.

--------------------

فایل OpenXML یک آرشیو ZIP است که حداکثر ۴ گیگابایت (۲^۳۲ بایت) برای اندازهٔ فایل فشرده‌نشده، اندازهٔ فایل فشرده و اندازهٔ کلی آرشیو دارد، همچنین حداکثر ۶۵٬۵۳۵ (۲^۱۶-۱) فایل در آرشیو مجاز است. افزونه‌های فرمت ZIP64 این محدودیت‌ها را به ۲^۶۴ افزایش می‌دهند.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [Never](#Never) | از افزونه‌های فرمت ZIP64 استفاده نکنید. |
| [IfNecessary](#IfNecessary) | در صورت لزوم از افزونه‌های فرمت ZIP64 استفاده کنید. |
| [Always](#Always) | همواره از افزونه‌های فرمت ZIP64 استفاده کنید. |
### Never {#Never}
```
public static final int Never
```


از افزونه‌های فرمت ZIP64 استفاده نکنید.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


در صورت لزوم از افزونه‌های فرمت ZIP64 استفاده کنید.

### Always {#Always}
```
public static final int Always
```


همواره از افزونه‌های فرمت ZIP64 استفاده کنید.