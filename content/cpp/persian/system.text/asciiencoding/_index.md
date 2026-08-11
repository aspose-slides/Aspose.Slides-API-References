---
title: ASCIIEncoding
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر رمزگذاری ASCII است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا باعث خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 1
url: /fa/system.text/asciiencoding/
---
## کلاس ASCIIEncoding

نمایانگر رمزگذاری ASCII است. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ASCIIEncoding : public System::Text::ICUEncoding
```
## متدها

| متد | توضیح |
| --- | --- |
|  [ASCIIEncoding](./asciiencoding/)() | سازنده. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](../encoding/clone/)() | یک نسخهٔ جدید از شیء رمزگذاری ایجاد می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| **bool** [Equals](../encoding/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | رمزگذاری‌ها را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفهوم [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه‌ نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه‌ نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | رمزگذاری ASCII را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | شیء رمزگذاری استاندارد Unicode با ترتیب بزرگ‌اند (big-endian) را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | شیء رمزگذاری استاندارد UTF-32 با ترتیب بزرگ‌اند را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | نام رمزگذاری سازگار با محتوای ایمیل را دریافت می‌کند. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | شناسه کدصفحه [Windows](../../system.windows/) را دریافت می‌کند. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | پشتیبان‌گر دیکودر را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | رمزگذاری پیش‌فرض را دریافت می‌کند. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | پشتیبان‌گر کدگذار را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | نام رمزگذاری قابل خواندن توسط انسان را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | نام رمزگذاری سازگار با سرآیند ایمیل را دریافت می‌کند. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای نمایش محتوا استفاده شود یا خیر. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در مرورگر برای ذخیره محتوا استفاده شود یا خیر. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در برنامهٔ ایمیل برای نمایش محتوا استفاده شود یا خیر. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | بررسی می‌کند که آیا رمزگذاری می‌تواند در برنامهٔ ایمیل برای ذخیره محتوا استفاده شود یا خیر. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | بررسی می‌کند که آیا رمزگذاری فقط‌خواندنی است یا خیر. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | بررسی می‌کند که آیا رمزگذاری تک‌بایتی است یا خیر. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | رمزگذاری Latin1 را دریافت می‌کند. برای استفاده داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | شیء رمزگذاری استاندارد Unicode را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | شیء رمزگذاری استاندارد UTF-7 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | شیء رمزگذاری استاندارد UTF-8 را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | فقط برای استفاده داخلی، توسط کتابخانه‌های کلاس استفاده می‌شود: بدون علامت و بدون اعتبارسنجی ورودی. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | نام رمزگذاری سازگار با IANA را دریافت می‌کند. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | شناسه کدصفحه [Windows](../../system.windows/) را دریافت می‌کند. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | تعداد کاراکترهای لازم برای کدگذاری یک بافر کاراکتری را دریافت می‌کند. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | بایت‌هایی که از کدگذاری یک بافر کاراکتری به دست می‌آید را دریافت می‌کند. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | تعداد کاراکترهای لازم برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آید را دریافت می‌کند. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آید را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آید را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آید را دریافت می‌کند. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آید را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | دیکودر را دریافت می‌کند که درخواست‌ها را به این شیء می‌فرستد. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | کدگذار را دریافت می‌کند که درخواست‌ها را به این شیء می‌فرستد. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | رمزگذاری را بر اساس کدصفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس کدصفحه دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را بر اساس نام دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | فهرست رمزگذاری‌های شناخته شده را دریافت می‌کند. |
| int [GetHashCode](../encoding/gethashcode/)() const override | رمزگذاری را هش می‌کند. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | حداکثر تعداد بایت ممکن برای نگهداری رشته‌ای با شمارش کاراکترهای شناخته‌شده را دریافت می‌کند. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | حداکثر تعداد کاراکترهای لازم برای رمزگشای یک تعداد بایت مشخص را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../icuencoding/getpreamble/)() override | دنباله‌ای از بایت‌ها که رمزگذاری را نشان می‌دهد (مثلاً BOM) را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | بافر بایت‌ها را به یک رشته دی‌کد می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | سازنده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. مشابه اپراتور 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در کلاس‌های فرزند را فراهم می‌کند. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | رمزگذاری‌ها را با استفاده از کدصفحه‌ها مقایسه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌وار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | پشتیبان‌گر دیکودر را تنظیم می‌کند. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | پشتیبان‌گر کدگذار را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک weak pointer (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() در C# را باز می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع weak را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع weak را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |
## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [ASCII_CODE_PAGE](./ascii_code_page/) | RTTI. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | مقدار پیش‌فرض کدصفحه. |
## موارد مرتبط

* کلاس [ICUEncoding](../icuencoding/)
* فضای نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)