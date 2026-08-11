---
title: Latin1Encoding
second_title: Aspose.Slides برای مرجع API C++
description: "پشتیبانی از رمزگذاری Latin1. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 313
url: /fa/system.text/latin1encoding/
---
## Latin1Encoding کلاس

پشتیبانی از رمزگذاری Latin1. شیء‌های این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class Latin1Encoding : public System::Text::ICUEncoding
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | یک نسخه از شیء رمزگذاری ایجاد می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | رمزگذاری‌ها را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیء‌ها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیء‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، شامل NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، شامل NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | رمزگذاری ASCII را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | شیء رمزگذاری استاندارد یونیکد بزرگ‌اند (big-endian) را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | شیء رمزگذاری استاندارد UTF-32 بزرگ‌اند را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | نام رمزگذاری سازگار با بدنهٔ عامل ایمیل را دریافت می‌کند. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | شناسهٔ صفحه‌کد [Windows](../../system.windows/) را دریافت می‌کند. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | پشت‌صحنهٔ دیکودر را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | رمزگذاری پیش‌فرض را دریافت می‌کند. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | پشت‌صحنهٔ انکودر را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | نام رمزگذاری قابل خواندن توسط انسان را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | نام رمزگذاری سازگار با هدر عامل ایمیل را دریافت می‌کند. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | بررسی می‌کند آیا رمزگذاری می‌تواند در مرورگر برای نمایش محتوا استفاده شود. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | بررسی می‌کند آیا رمزگذاری می‌تواند در مرورگر برای ذخیرهٔ محتوا استفاده شود. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | بررسی می‌کند آیا رمزگذاری می‌تواند در کلاینت ایمیل برای نمایش محتوا استفاده شود. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | بررسی می‌کند آیا رمزگذاری می‌تواند در کلاینت ایمیل برای ذخیرهٔ محتوا استفاده شود. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | بررسی می‌کند آیا رمزگذاری فقط-خواندنی است. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | بررسی می‌کند آیا رمزگذاری تک بایتی است. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | رمزگذاری Latin1 را دریافت می‌کند. فقط برای استفاده داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | شیء رمزگذاری استاندارد یونیکد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | شیء رمزگذاری استاندارد UTF-7 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | شیء رمزگذاری استاندارد UTF-8 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | فقط داخلی، برای استفاده توسط کتابخانه‌های کلاس: بدون علامت و بدون اعتبارسنجی ورودی. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | نام رمزگذاری سازگار با IANA را دریافت می‌کند. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | شناسهٔ صفحه‌کد [Windows](../../system.windows/) را دریافت می‌کند. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | تعداد کاراکترهای لازم برای رمزگذاری یک بافر کاراکتری را به‌دست می‌آورد. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتری حاصل می‌شوند را دریافت می‌کند. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایتی را به‌دست می‌آورد. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایتی را به‌دست می‌آورد. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایتی را به‌دست می‌آورد. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایتی را به‌دست می‌آورد. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | کاراکترهایی که از رمزگشایی یک بافر بایتی حاصل می‌شوند را دریافت می‌کند. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | کاراکترهایی که از رمزگشایی یک بافر بایتی حاصل می‌شوند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | کاراکترهایی که از رمزگشایی یک بافر بایتی حاصل می‌شوند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | کاراکترهایی که از رمزگشایی یک بافر بایتی حاصل می‌شوند را دریافت می‌کند. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | کاراکترهایی که از رمزگشایی یک بافر بایتی حاصل می‌شوند را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | یک دیکودر که درخواست‌ها را به این شیء می‌سپارد، دریافت می‌کند. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | یک انکودر که درخواست‌ها را به این شیء می‌سپارد، دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | رمزگذاری را بر اساس صفحه‌کد دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس صفحه‌کد دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | لیست رمزگذاری‌های شناخته‌شده را دریافت می‌کند. |
| int [GetHashCode](../encoding/gethashcode/)() const override | هَش رمزگذاری را محاسبه می‌کند. |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | حداکثر تعداد بایت‌های لازم برای رمزگذاری تعداد مشخصی کاراکتر را به‌دست می‌آورد. |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | حداکثر تعداد کاراکترهای لازم برای رمزگشایی تعداد مشخصی بایت را به‌دست می‌آورد. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | دنباله‌ای از بایت‌ها که نشانگر رمزگذاری است (مثلاً BOM) را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | یک بافر بایت‌ها را به رشته‌ای رمزگشایی می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | سازنده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
|  [Latin1Encoding](./latin1encoding/)() | سازنده. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کپی‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | رمزگذاری‌ها را با استفاده از صفحه‌کدها مقایسه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیء‌ها را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیء‌ها را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | پشت‌صحنهٔ دیکودر را تنظیم می‌کند. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | پشت‌صحنهٔ انکودر را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل شیء‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | مقدار پیش‌فرض صفحه‌کد. |
| static constexpr [LATIN1_CODE_PAGE](./latin1_code_page/) | صفحه‌کد. |

## مراجع

* کلاس [ICUEncoding](../icuencoding/)
* فضای‌نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)