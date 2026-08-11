---
title: Convert
second_title: مرجع API Aspose.Slides برای C++
description: "ساختاری که شامل روش‌هایی برای تبدیل مقادیر یک نوع به مقادیر نوع دیگر است. این نوع باید در پشته اختصاص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 1561
url: /fa/system/convert/
---
## ساختار تبدیل

ساختاری که شامل متدهایی است که تبدیل مقادیر یک نوع به مقادیر نوع دیگری را انجام می‌دهند. این نوع باید روی پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class Convert
```

## متدها

| Method | توضیح |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | پیاده‌سازی نشده. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | داده‌های رمزگذاری‌شدهٔ base-64 را که به صورت یک بازه در آرایهٔ کاراکترهای یونیکد نمایش داده شده‌اند، رمزگشایی می‌کند. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | داده‌های رمزگذاری‌شدهٔ base-64 را که به صورت یک رشته نمایش داده شده‌اند، رمزگشایی می‌کند. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | یک مقدار TypeCode که نوع مقدار جعبه‌شدهٔ مشخص‌شده را نشان می‌دهد را برمی‌گرداند. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | پیاده‌سازی نشده. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | پیاده‌سازی نشده. پیاده‌سازی تقلبی، بررسی می‌کند که آیا مقدار nullptr است. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | داده‌های base-64 را از یک بازه از عناصر در آرایهٔ بایتی مشخص‌شده رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به عنوان آرایه‌ای از کاراکترهای یونیکد ذخیره می‌نماید. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | داده‌های base-64 را از یک بازه از عناصر در آرایهٔ بایتی مشخص‌شده رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به عنوان آرایه‌ای از کاراکترهای یونیکد ذخیره می‌نماید. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | عناصر آرایهٔ بایتی مشخص‌شده را به‌صورت base-64 رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به‌صورت رشته برمی‌گرداند. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | یک بازه از عناصر آرایهٔ بایتی مشخص‌شده را به‌صورت base-64 رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به‌صورت رشته برمی‌گرداند. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | عناصر آرایهٔ بایتی مشخص‌شده را به‌صورت base-64 رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به‌صورت رشته برمی‌گرداند. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | یک بازه از عناصر آرایهٔ بایتی مشخص‌شده را به‌صورت base-64 رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به‌صورت رشته برمی‌گرداند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | مقدار بولی مشخص‌شده را برمی‌گرداند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | عدد صحیح بدون علامت 8 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | عدد صحیح مثبت/منفی 8 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | عدد صحیح بدون علامت 16 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | عدد صحیح 16 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | عدد صحیح بدون علامت 32 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | عدد صحیح 32 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | عدد صحیح بدون علامت 64 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | عدد صحیح 64 بیتی مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | عدد شناور (float) مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | عدد دوبل (double) مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | عدد دسیمال مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | رشتهٔ null را به مقدار بولی معادل تبدیل می‌کند. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | رشته C-style را به مقدار نوع bool تبدیل می‌کند. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده را به مقدار نوع bool تبدیل می‌کند. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده را به مقدار نوع bool تبدیل می‌کند. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص‌شده را به مقدار بولی معادل تبدیل می‌کند. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | مقدار بولی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | عدد صحیح بدون علامت 8 بیتی مشخص‌شده را برمی‌گرداند. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | عدد صحیح 8 بیتی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | عدد صحیح بدون علامت 16 بیتی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | عدد صحیح 16 بیتی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | عدد صحیح بدون علامت 32 بیتی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | عدد صحیح 32 بیتی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | عدد صحیح بدون علامت 64 بیتی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | عدد صحیح 64 بیتی مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | عدد شناور (float) مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | عدد دوبل (double) مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | عدد دسیمال مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | کاراکتر یونیکد مشخص‌شده را به عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | رشتهٔ null را به مقدار عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | رشته C-style که نمایانگر عدد است را به مقدار عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | رشته‌ای که نمایانگر عدد است را به مقدار عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | رشته‌ای که نمایانگر عدد در پایهٔ مشخص‌شده است را به مقدار عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایانگر عدد است را با استفاده از اطلاعات فرمت فراهم‌شده به مقدار عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایانگر عدد است را با استفاده از اطلاعات فرمت و سبک عددی فراهم‌شده به مقدار عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص‌شده را به مقدار عدد صحیح بدون علامت 8 بیتی معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**bool**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | عدد صحیح بدون علامت 8 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**int8_t**) | عدد صحیح 8 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | عدد صحیح بدون علامت 16 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**int16_t**) | عدد صحیح 16 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | عدد صحیح بدون علامت 32 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**int32_t**) | عدد صحیح 32 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | عدد صحیح بدون علامت 64 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**int64_t**) | عدد صحیح 64 بیتی مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(**float**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static char_t [ToChar](./tochar/)(**double**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | کاراکتر یونیکد مشخص‌شده را برمی‌گرداند. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static char_t [ToChar](./tochar/)(const char_t *) | اولین و تنها کاراکتر رشته C-style مشخص‌شده را به مقدار char_t تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | اولین و تنها کاراکتر رشتهٔ مشخص‌شده را به مقدار char_t تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | اولین و تنها کاراکتر رشتهٔ مشخص‌شده را به مقدار char_t تبدیل می‌کند. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص‌شده را به کاراکتر یونیکد معادل تبدیل می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | تبدیل پشتیبانی نمی‌شود. همیشه استثنای InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | تاریخ و زمان مشخص‌شده را برمی‌گرداند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | رشتهٔ مشخص‌شده را به یک نمونه از کلاس [DateTime](../datetime/) تبدیل می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ مشخص‌شده را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به یک نمونه از کلاس [DateTime](../datetime/) تبدیل می‌کند. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص‌شده را به مقدار مساوی [DateTime](../datetime/) تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | مقدار بولی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | عدد صحیح علامت‌دار ۸ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | عدد صحیح بدون علامت ۱۶ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | عدد صحیح علامت‌دار ۱۶ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | عدد صحیح علامت‌دار ۳۲ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | عدد صحیح علامت‌دار ۶۴ بیتی مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | عدد شناور float مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | عدد double مشخص‌شده را به عدد دسیمال معادل تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | عدد دسیمال مشخص‌شده را برمی‌گرداند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | رشتهٔ تهی مشخص‌شده را به مقدار معادل [Decimal](../decimal/) تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | رشتهٔ C حاوی نمایش عددی را به مقدار معادل [Decimal](../decimal/) تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | رشتهٔ حاوی نمایش عددی را به مقدار معادل [Decimal](../decimal/) تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار معادل [Decimal](../decimal/) تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی را با استفاده از سبک‌های عددی و اطلاعات قالب‌بندی مشخص‌شده به مقدار معادل [Decimal](../decimal/) تبدیل می‌کند. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص‌شده را به مقدار معادل [Decimal](../decimal/) تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | مقدار بولی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | عدد صحیح علامت‌دار ۸ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | عدد صحیح بدون علامت ۱۶ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | عدد صحیح علامت‌دار ۱۶ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | عدد صحیح علامت‌دار ۳۲ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | عدد صحیح علامت‌دار ۶۴ بیتی مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | عدد تک‌دقت (single-precision) مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | عدد double مشخص‌شده را برمی‌گرداند. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | عدد دسیمال مشخص‌شده را به عدد شناور دو دقت معادل تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(char_t) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | رشتهٔ تهی مشخص‌شده را به مقدار شناور دو دقت معادل تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(const char_t *) | رشتهٔ C حاوی نمایش عددی را به مقدار شناور دو دقت معادل تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | رشتهٔ حاوی نمایش عددی را به مقدار شناور دو دقت معادل تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار شناور دو دقت معادل تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی را با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده به مقدار شناور دو دقت معادل تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص‌شده را به مقدار شناور دو دقت تبدیل می‌کند. اگر نوع مقدار جعبه‌شده [String](../string/) باشد، قالب رشتهٔ مشخص‌شده در طول تبدیل استفاده می‌شود. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | مقدار بولی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | عدد صحیح علامت‌دار ۸ بیتی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | عدد صحیح بدون علامت ۱۶ بیتی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | عدد صحیح ۱۶ بیتی علامت‌دار مشخص‌شده را برمی‌گرداند. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | عدد صحیح علامت‌دار ۳۲ بیتی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | عدد صحیح علامت‌دار ۶۴ بیتی مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | عدد شناور float مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | عدد double مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | عدد دسیمال مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | کاراکتر یونیکد مشخص‌شده را به عدد صحیح ۱۶ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | رشتهٔ تهی مشخص‌شده را به مقدار عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | رشتهٔ C حاوی نمایش عددی را به مقدار عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | رشتهٔ حاوی نمایش عددی را به مقدار عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | رشتهٔ حاوی نمایش عددی را در پایهٔ مشخص‌شده به مقدار عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی را با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده به مقدار عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص‌شده را به مقدار عدد صحیح ۱۶ بیتی معادل تبدیل می‌کند. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | مقدار بولی مشخص‌شده را به عدد صحیح ۳۲ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به عدد صحیح ۳۲ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | مقدار صحیح ۸ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | مقدار صحیح ۱۶ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | مقدار صحیح ۱۶ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(**uint32_t**) | مقدار صحیح ۳۲ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | عدد صحیح ۳۲ بیتی مشخص شده را برمی‌گرداند. |
| static int [ToInt32](./toint32/)(**uint64_t**) | مقدار صحیح ۶۴ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(**int64_t**) | مقدار صحیح ۶۴ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(**float**) | عدد float مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(**double**) | عدد double مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | عدد اعشاری مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static constexpr int [ToInt32](./toint32/)(char_t) | کاراکتر یونیکد مشخص شده را به یک عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همواره InvalidCastException پرتاب می‌شود. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | رشته تهی (null-string) مشخص شده را به مقدار عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const char_t *) | رشته C حاوی نمایه عددی را به مقدار عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | رشته حاوی نمایه عددی را به مقدار عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | رشته حاوی نمایه عددی در پایهٔ مشخص شده را به مقدار عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته حاوی نمایه عددی را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته حاوی نمایه عددی را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به مقدار عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار بسته‌بندی شدهٔ مشخص شده را به مقدار عدد صحیح ۳۲ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | مقدار بولی مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | مقدار صحیح ۸ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | مقدار صحیح ۸ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | مقدار صحیح ۱۶ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | مقدار صحیح ۱۶ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | مقدار صحیح ۳۲ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | مقدار صحیح ۳۲ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | مقدار صحیح ۶۴ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | عدد صحیح ۶۴ بیتی مشخص شده را برمی‌گرداند. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | عدد float مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | عدد double مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | عدد اعشاری مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | کاراکتر یونیکد مشخص شده را به یک عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همواره InvalidCastException پرتاب می‌شود. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | رشته تهی (null-string) مشخص شده را به مقدار عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | رشته C حاوی نمایه عددی را به مقدار عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | رشته حاوی نمایه عددی را به مقدار عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | رشته حاوی نمایه عددی در پایهٔ مشخص شده را به مقدار عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته حاوی نمایه عددی را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته حاستهٔ نمایه عددی را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به مقدار عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار بسته‌بندی شدهٔ مشخص شده را به مقدار عدد صحیح ۶۴ بیتی معادل تبدیل می‌کند. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | مقدار بولی مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | مقدار صحیح ۸ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | عدد صحیح ۸ بیتی علامت‌دار مشخص شده را برمی‌گرداند. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | مقدار صحیح ۱۶ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | مقدار صحیح ۱۶ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | مقدار صحیح ۳۲ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | مقدار صحیح ۳۲ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | مقدار صحیح ۶۴ بیتی بدون علامت مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | مقدار صحیح ۶۴ بیتی علامت‌دار مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | عدد float مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | عدد double مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | عدد اعشاری مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | کاراکتر یونیکد مشخص شده را به یک عدد صحیح ۸ بیتی علامت‌دار معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همواره InvalidCastException پرتاب می‌شود. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | رشته تهی (null-string) مشخص شده را به مقدار عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | رشته C حاوی نمایه عددی را به مقدار عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | رشته حاوی نمایه عددی را به مقدار عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | رشته حاوی نمایه عددی در پایهٔ مشخص شده را به مقدار عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته حاوی نمایه عددی را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار عدد صحیح ۸ بیتی بدون علامت معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته حاوی نمایه عددی را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به مقدار عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار بسته‌بندی‌شدهٔ مشخص شده را به مقدار عدد صحیح ۸ بیتی معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | مقدار بولی مشخص شده را به یک عدد شناور تک‌دقت (single-precision) معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | مقدار صحیح ۸ بیتی بدون علامت مشخص شده را به یک عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | مقدار صحیح ۸ بیتی علامت‌دار مشخص شده را به یک عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | مقدار صحیح ۱۶ بیتی بدون علامت مشخص شده را به یک عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | مقدار صحیح ۱۶ بیتی علامت‌دار مشخص شده را به یک عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | مقدار صحیح ۳۲ بیتی بدون علامت مشخص شده را به یک عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | مقدار صحیح ۳۲ بیتی علامت‌دار مشخص شده را به یک عدد شناور تک‌دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | عدد صحیح بی‌علامت 64-بیتی مشخص شده را به عدد شناور تک دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | عدد صحیح 64-بیتی با علامت مشخص شده را به عدد شناور تک دقت معادل تبدیل می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | عدد float مشخص شده را برمی‌گرداند. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | عدد double-دقت مشخص شده را به عدد شناور تک دقت معادل تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | عدد اعشاری مشخص شده را به عدد شناور تک دقت معادل تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(char_t) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | رشتهٔ null-string مشخص شده را به مقدار شناور تک دقت معادل تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | رشتهٔ c-string شامل نمایش متنی یک عدد را به مقدار شناور تک دقت معادل تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | رشته‌ای که نمایش متنی یک عدد را دارد را به مقدار شناور تک دقت معادل تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایش متنی یک عدد را دارد را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار شناور تک دقت معادل تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایش متنی یک عدد را دارد را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به مقدار شناور تک دقت معادل تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار جعبه‌شدهٔ مشخص شده را به مقدار شناور تک دقت تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**float**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**double**) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | مقدار مشخص شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌بندی مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) مشخص به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌بندی مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) مشخص به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌بندی مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) مشخص به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌بندی مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) مشخص به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌بندی مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) مشخص به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص شده را با استفاده از قالب رشته‌ای مشخص و اطلاعات قالب‌بندی مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) مشخص به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را با استفاده از قالب رشتهٔ مشخص و اطلاعات قالب‌گذاری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را با استفاده از قالب رشتهٔ مشخص و اطلاعات قالب‌گذاری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را با استفاده از قالب رشتهٔ مشخص و اطلاعات قالب‌گذاری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را با استفاده از قالب رشتهٔ مشخص و اطلاعات قالب‌گذاری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را با استفاده از قالب رشتهٔ مشخص و اطلاعات قالب‌گذاری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را با استفاده از قالب رشتهٔ مشخص و اطلاعات قالب‌گذاری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | مقدار مشخص‌شده را به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | مقدار مشخص‌شده را با استفاده از قالب رشتهٔ مشخص به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | آرایهٔ مشخص‌شده از کاراکترهای یونیکد را به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | آرایهٔ مشخص‌شده از کاراکترهای یونیکد را با استفاده از اطلاعات قالب‌گذاری مخصوص فرهنگ ارائه‌شده توسط شیء [IFormatProvider](../iformatprovider/) به رشته تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلى انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | مقدار مشخص‌شده را برمی‌گرداند؛ هیچ تبدیلی انجام نمی‌شود. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | مقدار مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | مقدار مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | مقدار مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | مقدار مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | مقدار مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | مقدار عدد صحیح مشخص‌شده را در پایهٔ مشخص‌شده به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | مقدار عدد صحیح مشخص‌شده را در پایهٔ مشخص‌شده به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | مقدار عدد صحیح مشخص‌شده را در پایهٔ مشخص‌شده به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | مقدار عدد صحیح مشخص‌شده را در پایهٔ مشخص‌شده به نمایهٔ رشته‌ای خود تبدیل می‌کند. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار بسته‌بندی‌شدهٔ مشخص‌شده را به نمایهٔ رشته‌ای خود تبدیل می‌کند. اگر نوع مقدار بسته‌بندی‌شده [String](../string/) باشد، قالب رشتهٔ مشخص‌شده در زمان تبدیل استفاده می‌شود. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | مقدار بولی مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | عدد صحیح بدون علامت 8-بیتی مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | عدد صحیح 8-بیتی علامت‌دار مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | عدد صحیح بدون علامت 16-بیتی مشخص‌شده را برمی‌گرداند. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | عدد صحیح 16-بیتی علامت‌دار مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | عدد صحیح بدون علامت 32-بیتی مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | عدد صحیح 32-بیتی علامت‌دار مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | عدد صحیح بدون علامت 64-بیتی مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | عدد صحیح 64-بیتی علامت‌دار مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | عدد شناور مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | عدد double مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | عدد دهدهی مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | کاراکتر یونیکد مشخص‌شده را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException پرتاب می‌شود. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | رشتهٔ تهی مشخص‌شده را به مقدار عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | رشتهٔ C-style حاوی نمایش عددی یک مقدار را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | رشتهٔ حاوی نمایش عددی یک مقدار را به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | رشتهٔ حاوی نمایش عددی یک مقدار را در پایهٔ مشخص‌شده به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی یک مقدار را با استفاده از اطلاعات قالب‌گذاری ارائه‌شده به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشتهٔ حاوی نمایش عددی یک مقدار را با استفاده از اطلاعات قالب‌گذاری و سبک عدد ارائه‌شده به عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار بسته‌بندی‌شدهٔ مشخص‌شده را به مقدار عدد صحیح بدون علامت 16-بیتی معادل تبدیل می‌کند. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | مقدار بولی مشخص‌شده را به عدد صحیح بدون علامت 32-بیتی معادل تبدیل می‌کند. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | عدد صحیح بدون علامت 8-بیتی مشخص‌شده را به عدد صحیح بدون علامت 32-بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | عدد صحیح 8-بیتی علامت‌دار مشخص‌شده را به عدد صحیح بدون علامت 32-بیتی معادل تبدیل می‌کند. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | عدد صحیح بدون علامت 16-بیتی مشخص‌شده را به عدد صحیح بدون علامت 32-بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | عدد صحیح 16-بیتی علامت‌دار مشخص‌شده را به عدد صحیح بدون علامت 32-بیتی معادل تبدیل می‌کند. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | عدد صحیح بدون علامت 32-بیتی مشخص‌شده را برمی‌گرداند. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | عدد صحیح 32 بیتی مشخص‌شده را به عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | عدد صحیح بدون علامت 64 بیتی مشخص‌شده را به عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | عدد صحیح 64 بیتی مشخص‌شده را به عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | عدد شناور مشخص‌شده را به عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | عدد دوگانه مشخص‌شده را به عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | عدد اعشاری مشخص‌شده را به عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | کاراکتر یونیکد مشخص‌شده را به عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | رشته تهی (null-string) مشخص‌شده را به مقدار عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | رشته C که نمایش عددی را به صورت رشته‌ای دارد را به مقدار عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | رشته‌ای که نمایش عددی را به صورت رشته‌ای دارد را به مقدار عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | رشته‌ای که نمایش عددی را در پایهٔ مشخص‌شده به صورت رشته‌ای دارد را به مقدار عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایش عددی را به صورت رشته‌ای دارد را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایش عددی را به صورت رشته‌ای دارد را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به مقدار عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار بسته‌بندی‌شدهٔ مشخص‌شده را به مقدار عدد صحیح بدون علامت 32 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | مقدار منطقی (boolean) مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | عدد صحیح بدون علامت 8 بیتی مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | عدد صحیح 8 بیتی مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | عدد صحیح بدون علامت 16 بیتی مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | عدد صحیح 16 بیتی مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | عدد صحیح بدون علامت 32 بیتی مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | عدد صحیح 32 بیتی مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | عدد صحیح بدون علامت 64 بیتی مشخص‌شده را برمی‌گرداند. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | عدد صحیح 64 بیتی مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | عدد شناور مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | عدد دوگانه مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | عدد اعشاری مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | کاراکتر یونیکد مشخص‌شده را به عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | تبدیل پشتیبانی نمی‌شود. همیشه InvalidCastException را پرتاب می‌کند. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | رشته تهی (null-string) مشخص‌شده را به مقدار عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | رشته C که نمایش عددی را به صورت رشته‌ای دارد را به مقدار عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | رشته‌ای که نمایش عددی را به صورت رشته‌ای دارد را به مقدار عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | رشته‌ای که نمایش عددی را در پایهٔ مشخص‌شده به صورت رشته‌ای دارد را به مقدار عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایش عددی را به صورت رشته‌ای دارد را با استفاده از اطلاعات قالب‌بندی ارائه‌شده به مقدار عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | رشته‌ای که نمایش عددی را به صورت رشته‌ای دارد را با استفاده از اطلاعات قالب‌بندی و سبک عدد ارائه‌شده به مقدار عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | مقدار بسته‌بندی‌شدهٔ مشخص‌شده را به مقدار عدد صحیح بدون علامت 64 بیتی معادل تبدیل می‌کند. |
## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)