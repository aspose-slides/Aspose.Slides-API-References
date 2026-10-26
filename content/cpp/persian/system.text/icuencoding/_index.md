---
title: ICUEncoding
second_title: مرجع API Aspose.Slides برای C++
description: "پیاده‌سازی رمزگذاری مبتنی بر ICU. فقط برای استفاده داخلی. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های assert می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 300
url: /fa/system.text/icuencoding/
---
## ICUEncoding کلاس

پیاده‌سازی رمزگذاری مبتنی بر ICU. فقط برای استفاده داخلی. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ICUEncoding : public System::Text::Encoding
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | یک شیء رمزگذاری را کلون می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | رمزگذاری‌ها را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | رمزگذاری ASCII را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | شیء رمزگذاری استاندارد یونیکد بزرگ‌اندی ک را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | شیء رمزگذاری استاندارد UTF-32 بزرگ‌اندی ک را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | نام رمزگذاری سازگار با بدنهٔ عامل ایمیل را دریافت می‌کند. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | شناسه کد صفحه [Windows](../../system.windows/) را دریافت می‌کند. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | بازگشت‌پذیری رمزگشا را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | رمزگذاری پیش‌فرض را دریافت می‌کند. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | بازگشت‌پذیری رمزگذار را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | نام رمزگذاری قابل خواندن برای انسان را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | نام رمزگذاری سازگار با هدر عامل ایمیل را دریافت می‌کند. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای نمایش محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای ذخیره محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در سرویس‌گیرنده ایمیل برای نمایش محتوا استفاده شود یا نه. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در سرویس‌گیرنده ایمیل برای ذخیره محتوا استفاده شود یا نه. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | بررسی می‌کند که آیا رمزگذاری فقط-خواندنی است یا نه. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | بررسی می‌کند که آیا رمزگذاری تک بایتی است یا نه. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | رمزگذاری Latin1 را دریافت می‌کند. فقط برای استفاده داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | شیء رمزگذاری استاندارد یونیکد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | شیء رمزگذاری استاندارد UTF-7 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | شیء رمزگذاری استاندارد UTF-8 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | فقط برای استفاده داخلی، توسط کتابخانه‌های کلاس: بدون علامت و بدون اعتبارسنجی ورودی. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | نام رمزگذاری سازگار با IANA را دریافت می‌کند. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | شناسه کد صفحه [Windows](../../system.windows/) را دریافت می‌کند. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | تعداد کاراکترهای لازم برای رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | کاراکترهای حاصل از رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | کاراکترهای حاصل از رمزگشایی یک بافر بایت را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | یک رمزگشا که درخواست‌ها را به این شیء forwards می‌کند دریافت می‌کند. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | یک رمزگذار که درخواست‌ها را به این شیء forwards می‌کند دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | رمزگذاری را بر اساس کد صفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس کد صفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | لیست رمزگذاری‌های شناخته‌شده را دریافت می‌کند. |
| int [GetHashCode](../encoding/gethashcode/)() const override | هش رمزگذاری را محاسبه می‌کند. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | حداکثر تعداد بایت‌های لازم برای رمزگذاری تعداد مشخصی کاراکتر را دریافت می‌کند. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | حداکثر تعداد کاراکترهای لازم برای رمزگشایی تعداد مشخصی بایت را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | دنبالی از بایت‌ها که نشانگر رمزگذاری است (مثلاً BOM) را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](./icuencoding/)(const Details::EncodingInfoInternal *) | سازنده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان C# lock() . مستقیم فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) . امکان کلون‌گذاری انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختارهای فرعی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختارهای فرعی را فراهم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(const [ICUEncoding](./)\&) const | رمزگذاری‌ها را با استفاده از کد صفحه‌ها مقایسه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء مقداردهی با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای موارد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | بازگشت‌پذیری رمزگشا را تنظیم می‌کند. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | بازگشت‌پذیری رمزگذار را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو n'th را به یک اشاره‌گر ضعیف تنظیم می‌کند (به جای shared). امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/) . امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../../system/object/)) . |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل بیان C# lock() . مستقیم فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | مقدار پیش‌فرض کد صفحه. |

## سایر موارد

* کلاس [Encoding](../encoding/)
* فضای‌نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)