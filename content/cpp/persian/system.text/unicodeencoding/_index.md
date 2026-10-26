---
title: UnicodeEncoding
second_title: "مرجع API Aspose.Slides برای C++"
description: "رمزگذاری یونیکد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() ایجاد شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 339
url: /fa/system.text/unicodeencoding/
---
## کلاس UnicodeEncoding

Unicode encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```
## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک شیء رمزگذاری را کلون می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | رمزگذاری‌ها را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنی‌گذاری C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | رمزگذاری ASCII را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | شیء رمزگذاری استاندارد یونیکد بزرگ‌اند (big-endian) را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | شیء رمزگذاری استاندارد UTF-32 بزرگ‌اند را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | نام رمزگذاری سازگار با بدنهٔ عامل پست الکترونیکی را دریافت می‌کند. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | شناسه کد صفحه [Windows](../../system.windows/) را دریافت می‌کند. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | فالبِ رمزگشای را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | رمزگذاری پیش‌فرض را دریافت می‌کند. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | فالبِ رمزگذار را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | نام رمزگذاری قابل خواندن برای انسان را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | نام رمزگذاری سازگار با سرآیند عامل پست الکترونیکی را دریافت می‌کند. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای نمایش محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای ذخیرهٔ محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در کلاینت ایمیل برای نمایش محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در کلاینت ایمیل برای ذخیرهٔ محتوا استفاده شود یا نه. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | بررسی می‌کند که آیا رمزگذاری فقط-خواندنی است یا نه. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | بررسی می‌کند که آیا رمزگذاری تک‌بایتی است یا نه. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | رمزگذاری Latin1 را دریافت می‌کند. فقط برای استفادهٔ داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | شیء رمزگذاری استاندارد یونیکد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | شیء رمزگذاری استاندارد UTF-7 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | شیء رمزگذاری استاندارد UTF-8 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | فقط داخلی، برای استفاده توسط کتابخانه‌های کلاس: بدون علامت و بدون اعتبارسنجی ورودی. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | نام رمزگذاری سازگار با IANA را دریافت می‌کند. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | شناسه کد صفحه [Windows](../../system.windows/) را دریافت می‌کند. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | تعداد کاراکترهای لازم برای رمزگذاری یک بافر کاراکتر را برمی‌گرداند. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر حاصل می‌شوند را برمی‌گرداند. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | تعداد کاراکترهای لازم برای رمزگشای یک بافر بایت را برمی‌گرداند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد کاراکترهای لازم برای رمزگشای یک بافر بایت را برمی‌گرداند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تعداد کاراکترهای لازم برای رمزگشای یک بافر بایت را برمی‌گرداند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | تعداد کاراکترهای لازم برای رمزگشای یک بافر بایت را برمی‌گرداند. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | کاراکترهایی که از رمزگشای یک بافر بایت حاصل می‌شوند را برمی‌گرداند. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | کاراکترهایی که از رمزگشای یک بافر بایت حاصل می‌شوند را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | کاراکترهایی که از رمزگشای یک بافر بایت حاصل می‌شوند را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | کاراکترهایی که از رمزگشای یک بافر بایت حاصل می‌شوند را برمی‌گرداند. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | کاراکترهایی که از رمزگشای یک بافر بایت حاصل می‌شوند را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | یک رمزگشا که درخواست‌ها را به این شیء منتقل می‌کند را برمی‌گرداند. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | یک رمزگذار که درخواست‌ها را به این شیء منتقل می‌کند را برمی‌گرداند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | رمزگذاری را با نام دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | رمزگذاری را با کد صفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را با کد صفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را با نام دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | فهرست رمزگذاری‌های شناخته‌شده را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | هش رمزگذاری را محاسبه می‌کند. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | حداکثر تعداد بایت‌های لازم برای رمزگذاری تعداد مشخصی کاراکتر را برمی‌گرداند. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | حداکثر تعداد کاراکترهای لازم برای رمزگشای تعداد مشخصی بایت را برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | دنباله‌ای از بایت‌ها که رمزگذاری را نشان می‌دهد (مثلاً BOM) را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | یک بافر بایت را به رشته‌ای رمزگشا می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | سازنده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه اپراتور C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(const [UnicodeEncoding](./)\&) const | رمزگذاری‌ها را با کد صفحه و پرچم‌ها مقایسه می‌کند. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | رمزگذاری‌ها را با استفاده از کد صفحه مقایسه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌گونهٔ شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع به‌اشتراک‌گذاری‌شده را به مقدار مشخصی کاهش می‌دهد. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | فالبِ رمزگشا را تنظیم می‌کند. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | فالبِ رمزگذار را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارندهٔ مرجع به‌اشتراک‌گذاری‌شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع به‌اشتراک‌گذاری‌شده را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع به‌اشتراک‌گذاری‌شده را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| [UnicodeEncoding](./unicodeencoding/)() | سازنده. |
| [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**) | سازنده. |
| [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**, **bool**) | سازنده. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری دستور C# lock() را باز می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داخلی را آزاد می‌سازد. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | شمارهٔ کد صفحه بزرگ‌اند. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | مقدار پیش‌فرض کد صفحه. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | شمارهٔ کد صفحه کوچک‌اند. |

## مراجع

* کلاس [ICUEncoding](../icuencoding/)
* فضای‌نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)