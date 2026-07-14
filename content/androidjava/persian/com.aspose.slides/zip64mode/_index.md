---
title: Zip64Mode
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مشخص می‌کند که چه زمانی باید از افزونه‌های فرمت ZIP64 برای فایل OpenXML استفاده شود.
type: docs
url: /fa/com.aspose.slides/zip64mode/
---
**وراثت:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

مشخص می‌کند که کی از افزونه‌های فرمت ZIP64 برای فایل OpenXML استفاده شود.

--------------------

فایل OpenXML یک بایگانی ZIP است که محدودیت ۴ گیگابایت (۲^۳۲ بایت) برای اندازهٔ فشرده نشدهٔ هر فایل، اندازهٔ فشردهٔ هر فایل و مجموع اندازهٔ بایگانی دارد و همچنین محدودیت ۶۵٬۵۳۵ (۲^۱۶-۱) فایل در بایگانی را دارا می‌باشد. افزونه‌های فرمت ZIP64 این محدودیت‌ها را به ۲^۶۴ افزایش می‌دهند.

## فیلدها

| فیلد | توضیح |
| --- | --- |
| [Never](#Never) | از افزونه‌های فرمت ZIP64 استفاده نشود. |
| [IfNecessary](#IfNecessary) | در صورت نیاز از افزونه‌های فرمت ZIP64 استفاده شود. |
| [Always](#Always) | همیشه از افزونه‌های فرمت ZIP64 استفاده شود. |
### Never {#Never}
```
public static final int Never
```


از افزونه‌های فرمت ZIP64 استفاده نشود.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


در صورت نیاز از افزونه‌های فرمت ZIP64 استفاده شود.

### Always {#Always}
```
public static final int Always
```


همیشه از افزونه‌های فرمت ZIP64 استفاده شود.