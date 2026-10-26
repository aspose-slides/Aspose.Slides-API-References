---
title: UTF7Encoding
second_title: مرجع API Aspose.Slides برای C++
description: "کدگذاری UTF-7. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، چون منجر به خطاهای زمان اجرا و/یا نقص‌های صحت‌سنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 365
url: /fa/system.text/utf7encoding/
---
## UTF7Encoding کلاس

کدگذاری UTF-7. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، چون منجر به خطاهای زمان اجرا و/یا نقص‌های صحت‌سنجی می‌شود. همیشه این کلاس را در یک نشانگر [System::SmartPtr](../../system/smartptr/) بپیچید و از این نشانگر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | شیء کدگذاری را تکثیر می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | بایت‌ها را بین دو کدگذاری تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بایت‌ها را بین دو کدگذاری تبدیل می‌کند. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | با شیء مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با semantics [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# که دو NaN را برابر در نظر می‌گیرد، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# که دو NaN را برابر در نظر می‌گیرد، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | کدگذاری ASCII را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | شیء کدگذاری استاندارد Unicode بزرگ‌اند (big-endian) را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | شیء کدگذاری استاندارد UTF-32 بزرگ‌اند را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | نام کدگذاری سازگار با بدنهٔ عامل ایمیل را دریافت می‌کند. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | شناسهٔ codepage [Windows](../../system.windows/) را دریافت می‌کند. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | بازگشت fallback رمزگشای. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | کدگذاری پیش‌فرض را دریافت می‌کند. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | بازگشت fallback رمزگذار. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | نام قابل خواندن کدگذاری را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | نام کدگذاری سازگار با هدر عامل ایمیل را دریافت می‌کند. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | بررسی می‌کند که آیا می‌توان از این کدگذاری در مرورگر برای نمایش محتوا استفاده کرد. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | بررسی می‌کند که آیا می‌توان از این کدگذاری در مرورگر برای ذخیرهٔ محتوا استفاده کرد. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | بررسی می‌کند که آیا می‌توان از این کدگذاری در کلاینت ایمیل برای نمایش محتوا استفاده کرد. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | بررسی می‌کند که آیا می‌توان از این کدگذاری در کلاینت ایمیل برای ذخیرهٔ محتوا استفاده کرد. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | بررسی می‌کند که آیا کدگذاری فقط-خواندنی است. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | بررسی می‌کند که آیا کدگذاری تک-بایتی است. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | کدگذاری Latin1 را دریافت می‌کند. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | شیء کدگذاری استاندارد Unicode را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | شیء کدگذاری استاندارد UTF-7 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | شیء کدگذاری استاندارد UTF-8 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | فقط داخلی، برای استفاده توسط کتابخانه‌های کلاس: بدون علامت و بدون اعتبارسنجی ورودی. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | نام کدگذاری سازگار با IANA را دریافت می‌کند. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | شناسهٔ codepage [Windows](../../system.windows/) را دریافت می‌کند. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | تعداد کاراکترهای لازم برای کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | تعداد کاراکترهای لازم برای کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | تعداد کاراکترهای لازم برای کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | تعداد کاراکترهای لازم برای کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | تعداد کاراکترهای لازم برای کدگذاری یک رشته را برمی‌گرداند. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | تعداد کاراکترهای لازم برای کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | تعداد کاراکترهای لازم برای کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | بایت‌های حاصل از کدگذاری یک بافر کاراکتر را برمی‌گرداند. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را برمی‌گرداند. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را برمی‌گرداند. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را برمی‌گرداند. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را برمی‌گرداند. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را برمی‌گرداند. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | کاراکترهای حاصل از رمزگشایی یک بافر بایت را برمی‌گرداند. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | کاراکترهای حاصل از رمزگشایی یک بافر بایت را برمی‌گرداند. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را برمی‌گرداند. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | رمزگشایی را که درخواست‌ها را به این شیء می‌فرستد، دریافت می‌کند. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | رمزگذار را که درخواست‌ها را به این شیء می‌فرستد، دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | کدگذاری را بر اساس نام دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | کدگذاری را بر اساس صفحه کد دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | کدگذاری را بر اساس صفحه کد دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | کدگذاری را بر اساس نام دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | فهرست کدگذاری‌های شناخته‌شده را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | کد hash کدگذاری را دریافت می‌کند. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | حداکثر تعداد بایت لازم برای کدگذاری تعداد مشخصی کاراکتر را دریافت می‌کند. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | حداکثر تعداد کاراکتر لازم برای رمزگشایی تعداد مشخصی بایت را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | دنبالهٔ بایت‌هایی که کدگذاری را نشان می‌دهند (مثلاً BOM) را برمی‌گرداند. |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر ‘is’ در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری عبارت lock() در C#. مستقیم فراخوانی یا استفاده از شیء [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ نسخه‌برداری. هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان نسخه‌برداری زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان نسخه‌برداری زیرکلاس‌ها را فراهم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | پارامترهای کدگذاری را مقایسه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | fallback رمزگشای را تنظیم می‌کند. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | fallback رمزگذار را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل شیءهای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی قفل‌گذاری عبارت lock() در C# برای باز کردن قفل. مستقیم فراخوانی یا استفاده از شیء [LockContext](../../system/lockcontext/). |
|  [UTF7Encoding](./utf7encoding/)() | سازنده. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | سازنده. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | مقدار پیش‌فرض صفحه کد. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | عدد جادویی استفاده‌شده توسط [Windows](../../system.windows/) برای شناسهٔ صفحه کد UTF-7. |

## موارد مرتبط

* Class [Encoding](../encoding/)
* Namespace [System::Text](../)
* Library [Aspose.Slides](../../)