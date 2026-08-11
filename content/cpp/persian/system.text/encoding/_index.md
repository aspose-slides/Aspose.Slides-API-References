---
title: Encoding
second_title: مرجع API Aspose.Slides برای C++
description: خدمات رمزگذاری.
type: docs
weight: 222
url: /fa/system.text/encoding/
---
## کلاس Encoding

[Encoding](./) سرویس‌ها.

```cpp
class Encoding : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | یک شیء رمزگذاری را کلون می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بایت‌ها را بین دو رمزگذاری تبدیل می‌کند. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | رمزگذاری‌ها را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | رمزگذاری ASCII را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | شیء رمزگذاری Unicode با اندیس بزرگ (big-endian) استاندارد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | شیء رمزگذاری UTF-32 با اندیس بزرگ استاندارد را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | نام رمزگذاری سازگار با بدنهٔ عامل ایمیل را دریافت می‌کند. |
| virtual int [get_CodePage](./get_codepage/)() | شناسهٔ صفحه کد [Windows](../../system.windows/) را دریافت می‌کند. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | بازگشت‌پذیری رمزگشای را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | رمزگذاری پیش‌فرض را دریافت می‌کند. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | بازگشت‌پذیری رمزگذار را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | نام رمزگذاری قابل خواندن برای انسان را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | نام رمزگذاری سازگار با سرصفحهٔ عامل ایمیل را دریافت می‌کند. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | بررسی می‌کند که آیا می‌توان از رمزگذاری در مرورگر برای نمایش محتوا استفاده کرد یا خیر. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | بررسی می‌کند که آیا می‌توان از رمزگذاری در مرورگر برای ذخیرهٔ محتوا استفاده کرد یا خیر. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | بررسی می‌کند که آیا می‌توان از رمزگذاری در کلاینت ایمیل برای نمایش محتوا استفاده کرد یا خیر. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | بررسی می‌کند که آیا می‌توان از رمزگذاری در کلاینت ایمیل برای ذخیرهٔ محتوا استفاده کرد یا خیر. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | بررسی می‌کند که آیا رمزگذاری فقط‌خواندنی است یا خیر. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | بررسی می‌کند که آیا رمزگذاری تک‌بایتی است یا خیر. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | رمزگذاری Latin1 را دریافت می‌کند. برای استفاده داخلی. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | شیء رمزگذاری Unicode استاندارد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | شیء رمزگذاری UTF-7 استاندارد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | شیء رمزگذاری UTF-8 استاندارد را دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | فقط برای استفاده داخلی، توسط کتابخانه‌های کلاس: بدون علامت و بدون اعتبارسنجی ورودی. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | نام رمزگذاری سازگار با IANA را دریافت می‌کند. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | شناسهٔ صفحه کد [Windows](../../system.windows/) را دریافت می‌کند. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | تعداد کاراکترهای مورد نیاز برای رمزگذاری یک رشته را دریافت می‌کند. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | بایت‌هایی که از رمزگذاری یک بافر کاراکتر به‌دست می‌آیند را دریافت می‌کند. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | تعداد کاراکترهای مورد نیاز برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تعداد کاراکترهای مورد نیاز برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | تعداد کاراکترهای مورد نیاز برای رمزگشایی یک بافر بایت را دریافت می‌کند. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مربوط به شیء را دریافت می‌کند. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | یک رمزگشا که درخواست‌ها را به این شیء هدایت می‌کند دریافت می‌کند. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | یک رمزگذار که درخواست‌ها را به این شیء هدایت می‌کند دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | رمزگذاری را با نام دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | رمزگذاری را با صفحه کد دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را با صفحه کد دریافت می‌کند. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | رمزگذاری را با نام دریافت می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | فهرست رمزگذاری‌های شناخته‌شده را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | کد هش رمزگذاری را محاسبه می‌کند. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | حداکثر تعداد بایت‌های مورد نیاز برای رمزگذاری تعداد مشخصی کاراکتر را دریافت می‌کند. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | حداکثر تعداد کاراکترهای مورد نیاز برای رمزگشایی تعداد مشخصی بایت را دریافت می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | دنباله‌ای از بایت‌ها که نشان‌دهنده رمزگذاری است (مثلاً BOM) را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | یک بافر بایت را به رشته‌ای رمزگشایی می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نماد یک نمونه از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن با عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# را شبیه‌سازی می‌کند. امکان کلون‌کردن انواع سفارشی را فراهم می‌آورد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء ارزش‌نوع را با nullptr مقایسه مرجعی می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | بازگشت‌پذیری رمزگشا را تنظیم می‌کند. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | بازگشت‌پذیری رمزگذار را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | متد [Object.ToString()](../../system/object/tostring/) در C# را شبیه‌سازی می‌کند. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌آورد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | بازکردن قفل عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | مقدار پیش‌فرض صفحه کد. |

## تعاریف نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)