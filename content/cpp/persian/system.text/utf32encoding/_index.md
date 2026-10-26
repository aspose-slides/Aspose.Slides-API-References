---
title: UTF32Encoding
second_title: مرجع API Aspose.Slides برای C++
description: "رمزگذاری UTF-32. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 352
url: /fa/system.text/utf32encoding/
---
## UTF32Encoding کلاس

رمزگذاری UTF-32. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا باعث خطاهای زمان اجرا و/یا خطای ادعای (assertion) می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class UTF32Encoding : public System::Text::ICUEncoding
```

## متدها

| متد | توضیحات |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | شیء رمزگذاری را کلون می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | با شیء مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه double به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | رمزگذاری ASCII را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | شیء رمزگذاری استاندارد یونیکد بزرگ‌اند (big-endian) را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | شیء رمزگذاری استاندارد UTF-32 بزرگ‌اند را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | نام رمزگذاری سازگار با بدنهٔ کلاینت ایمیل را دریافت می‌کند. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | شناسه صفحه‌کد [Windows](../../system.windows/) را دریافت می‌کند. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | fallback decoder را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | رمزگذاری پیش‌فرض را دریافت می‌کند. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | fallback encoder را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | نام رمزگذاری قابل خواندن را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | نام رمزگذاری سازگار با هدر کلاینت ایمیل را دریافت می‌کند. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای نمایش محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای ذخیره محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در کلاینت ایمیل برای نمایش محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در کلاینت ایمیل برای ذخیره محتوا استفاده شود یا نه. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | بررسی می‌کند که آیا رمزگذاری فقط-خواندنی است یا نه. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | بررسی می‌کند که آیا رمزگذاری تک‌بایتی است یا نه. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | رمزگذاری Latin1 را دریافت می‌کند. برای استفاده داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | شیء رمزگذاری استاندارد یونیکد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | شیء رمزگذاری استاندارد UTF-7 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | شیء رمزگذاری استاندارد UTF-8 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | فقط برای استفاده داخلی، برای کتابخانه‌های کلاس: بدون علامت و بدون اعتبارسنجی ورودی. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | نام رمزگذاری سازگار با IANA را دریافت می‌کند. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | شناسه صفحه‌کد [Windows](../../system.windows/) را دریافت می‌کند. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | تعداد کاراکترهای لازم برای رمزگذاری بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | بایت‌هایی که نتیجهٔ رمزگذاری بافر کاراکتر هستند را دریافت می‌کند. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | تعداد کاراکترهای لازم برای دیکد بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد کاراکترهای لازم برای دیکد بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تعداد کاراکترهای لازم برای دیکد بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | تعداد کاراکترهای لازم برای دیکد بافر بایت را دریافت می‌کند. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | کاراکترهایی که نتیجهٔ دیکد بافر بایت هستند را دریافت می‌کند. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | کاراکترهایی که نتیجهٔ دیکد بافر بایت هستند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | کاراکترهایی که نتیجهٔ دیکد بافر بایت هستند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | کاراکترهایی که نتیجهٔ دیکد بافر بایت هستند را دریافت می‌کند. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | کاراکترهایی که نتیجهٔ دیکد بافر بایت هستند را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | یک decoder که درخواست‌ها را به این شیء منتقل می‌کند را دریافت می‌کند. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | یک encoder که درخواست‌ها را به این شیء منتقل می‌کند را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | رمزگذاری را بر اساس کد صفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس کد صفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | فهرست رمزگذاری‌های شناخته‌شده را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | کد هش رمزگذاری را دریافت می‌کند. |
| int [GetMaxByteCount](../icuencoding/getmaxbytecount/)(int) override | حداکثر تعداد بایت‌های لازم برای رمزگذاری تعداد مشخصی از کاراکترها را دریافت می‌کند. |
| int [GetMaxCharCount](../icuencoding/getmaxcharcount/)(int) override | حداکثر تعداد کاراکترهای لازم برای دیکد تعداد مشخصی از بایت‌ها را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | پریمبل صفحه‌کد را دریافت می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | یک بافر بایت را به رشته‌ای دیکد می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | سازنده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرا کنندهٔ قفل‌گذاری (lock) در C#. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF32Encoding](./)\&) const | پارامترهای رمزگذاری‌ها را مقایسه می‌کند. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | رمزگذاری‌ها را با استفاده از کدصفحات مقایسه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | fallback decoder را تنظیم می‌کند. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | fallback encoder را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرا کنندهٔ باز کردن قفل (unlock) در C#. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| [UTF32Encoding](./utf32encoding/)() | سازنده. |
| [UTF32Encoding](./utf32encoding/)(**bool**, **bool**) | سازنده. |
| [UTF32Encoding](./utf32encoding/)(**bool**, **bool**, **bool**) | سازنده. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیحات |
| --- | --- |
| static constexpr [BIG_UTF32_CODE_PAGE](./big_utf32_code_page/) | عدد جادویی استفاده‌شده توسط [Windows](../../system.windows/) برای شناسه صفحه‌کد UTF-32 بزرگ‌اند. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | مقدار پیش‌فرض صفحه‌کد. |
| static constexpr [UTF32_CODE_PAGE](./utf32_code_page/) | عدد جادویی استفاده‌شده توسط [Windows](../../system.windows/) برای شناسه صفحه‌کد UTF-32 کوچک‌اند. |

## همچنین ببینید

* کلاس [ICUEncoding](../icuencoding/)
* فضای‌نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)