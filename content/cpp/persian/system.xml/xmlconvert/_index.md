---
title: XmlConvert
second_title: Aspose.Slides برای C++ مرجع API
description: نام‌های XML را رمزگذاری و رمزگشایی می‌کند و متدهایی برای تبدیل بین انواع زمان اجرا و انواع زبان تعریف طرح‌واره XML (XSD) فراهم می‌کند. هنگام تبدیل انواع داده، مقادیر بازگردانده شده مستقل از تنظیمات محلی هستند.
type: docs
weight: 157
url: /fa/system.xml/xmlconvert/
---
## کلاس XmlConvert

Encodes and decodes XML names, and provides methods for converting between runtime types and XML [Schema](../../system.xml.schema/) definition language (XSD) types. When converting data types, the values returned are locale-independent.

```cpp
class XmlConvert : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | نامی را رمزگشایی می‌کند. این متد معکوس متدهای XmlConvert::EncodeName(String) و XmlConvert::EncodeLocalName(String) است. |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | نام را به یک نام محلی XML معتبر تبدیل می‌کند. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | نام را به یک نام XML معتبر تبدیل می‌کند. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | بررسی می‌کند که نام بر اساس مشخصات XML معتبر است. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ‌مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ‌مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | هماهنگی با متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. هماهنگی با فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. هماهنگی با عملگر C# 'is'. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | بررسی می‌کند که آیا کاراکتر ورودی یک نوع کاراکتر غیر-کولن معتبر است. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | اگر کاراکتر ورودی یک کاراکتر شناسه عمومی معتبر باشد، همان کاراکتر را برمی‌گرداند، در غیر این صورت **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | بررسی می‌کند که آیا کاراکتر ورودی یک نوع Start Name Character معتبر است. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | بررسی می‌کند که آیا کاراکتر ورودی یک کاراکتر فضای خالی XML معتبر است. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | بررسی می‌کند که آیا کاراکتر ورودی یک کاراکتر XML معتبر است. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | بررسی می‌کند که آیا جفت کاراکترهای جایگزین ورودی یک کاراکتر XML معتبر هستند. |
| void [Lock](../../system/object/lock/)() | عملکرد قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | هماهنگی با متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ساختمان کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌نماید و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌نماید و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | [String](../../system/string/) را به معادل [Boolean](../../system/boolean/) تبدیل می‌کند. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [Byte](../../system/byte/) تبدیل می‌کند. |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [Char](../../system/char/) تبدیل می‌کند. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [DateTime](../../system/datetime/) تبدیل می‌کند. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [DateTime](../../system/datetime/) تبدیل می‌کند. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | [String](../../system/string/) را به معادل [DateTime](../../system/datetime/) تبدیل می‌کند. |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [String](../../system/string/) را به [DateTime](../../system/datetime/) تبدیل می‌کند با استفاده از XmlDateTimeSerializationMode مشخص‌شده. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | [String](../../system/string/) ارائه‌شده را به معادل [DateTimeOffset](../../system/datetimeoffset/) تبدیل می‌کند. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | [String](../../system/string/) ارائه‌شده را به معادل [DateTimeOffset](../../system/datetimeoffset/) تبدیل می‌کند. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | [String](../../system/string/) ارائه‌شده را به معادل [DateTimeOffset](../../system/datetimeoffset/) تبدیل می‌کند. |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [Decimal](../../system/decimal/) تبدیل می‌کند. |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | [String](../../system/string/) را به معادل [Double](../../system/double/) تبدیل می‌کند. |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [Guid](../../system/guid/) تبدیل می‌کند. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [Int16](../../system/int16/) تبدیل می‌کند. |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [Int32](../../system/int32/) تبدیل می‌کند. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [Int64](../../system/int64/) تبدیل می‌کند. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [SByte](../../system/sbyte/) تبدیل می‌کند. |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | [String](../../system/string/) را به معادل [Single](../../system/single/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | [Boolean](../../system/boolean/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | [Char](../../system/char/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | [SByte](../../system/sbyte/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | [Int16](../../system/int16/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | [Int32](../../system/int32/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | [Int64](../../system/int64/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | [Byte](../../system/byte/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | [UInt16](../../system/uint16/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | [UInt32](../../system/uint32/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | [UInt64](../../system/uint64/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | [Single](../../system/single/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | [Double](../../system/double/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | [TimeSpan](../../system/timespan/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | [DateTime](../../system/datetime/) را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | [DateTime](../../system/datetime/) را به [String](../../system/string/) تبدیل می‌کند با استفاده از XmlDateTimeSerializationMode مشخص‌شده. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) ارائه‌شده را به [String](../../system/string/) تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | [DateTimeOffset](../../system/datetimeoffset/) ارائه‌شده را به [String](../../system/string/) در قالب مشخص‌شده تبدیل می‌کند. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | [Guid](../../system/guid/) را به [String](../../system/string/) تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | هماهنگی با متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [TimeSpan](../../system/timespan/) تبدیل می‌کند. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [UInt16](../../system/uint16/) تبدیل می‌کند. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [UInt32](../../system/uint32/) تبدیل می‌کند. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | [String](../../system/string/) را به معادل [UInt64](../../system/uint64/) تبدیل می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | عملکرد باز کردن قفل دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | تأیید می‌کند که نام بر اساس توصیه‌نامهٔ W3C Extended Markup Language یک نام معتبر است. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | تأیید می‌کند که نام بر اساس توصیه‌نامهٔ W3C Extended Markup Language یک **NCName** معتبر است. **NCName** نامی است که نمی‌تواند شامل کولن باشد. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | تأیید می‌کند که رشته بر اساس توصیه‌نامهٔ W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes یک NMTOKEN معتبر است. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | اگر تمام کاراکترهای آرگومان رشته کاراکترهای شناسه عمومی معتبر باشند، همان رشتهٔ ورودی را باز می‌گرداند. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | تأیید می‌کند که رشته بر اساس توصیه‌نامهٔ W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes یک توکن معتبر است. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | اگر تمام کاراکترهای آرگومان رشته کاراکترهای فضای خالی معتبر باشند، همان رشتهٔ ورودی را باز می‌گرداند. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | اگر تمام کاراکترها و جفت کاراکترهای جایگزین در آرگومان رشته کاراکترهای XML معتبر باشند، همان رشتهٔ ورودی را باز می‌گرداند؛ در غیر این صورت XmlException با اطلاعات اولین کاراکتر نامعتبر رخ داده پرتاب می‌شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس است. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)