---
title: XmlReader
second_title: Aspose.Slides برای C++ مرجع API
description: یک خواننده را نشان می‌دهد که دسترسی سریع، بدون کش، فقط به جلو به داده‌های XML را فراهم می‌کند.
type: docs
weight: 430
url: /fa/system.xml/xmlreader/
---
## XmlReader class

نمایشی از یک خواننده که دسترسی سریع، بدون کش، فقط-به-سوی-جلو به داده‌های XML فراهم می‌کند.

```cpp
class XmlReader : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، [XmlReader::get_ReadState](./get_readstate/) را به [ReadState::Closed](../readstate/) تغییر می‌دهد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](./) را با URI مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از URI و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از URI، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از جریان مشخص و تنظیمات پیش‌فرض ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](./) را با جریان و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از جریان، URI پایه و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از جریان، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از خواننده متن مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از خواننده متن و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از خواننده متن، تنظیمات و URI پایه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](./) را با استفاده از خواننده متن، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | یک نمونه جدید از [XmlReader](./) را با استفاده از خواننده XML و تنظیمات مشخص ایجاد می‌کند. |
| void [Dispose](./dispose/)() override | تمام منابع مورد استفاده توسط نمونه فعلی کلاس [XmlReader](./) را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، تعداد ویژگی‌های گره فعلی را به دست می‌آورد. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، URI پایه گره فعلی را به دست می‌آورد. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlReader](./) متدهای خواندن محتوای باینری را پیاده‌سازی می‌کند یا نه. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlReader](./) متد [XmlReader::ReadValueChunk](./readvaluechunk/) را پیاده‌سازی می‌کند یا نه. |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا این خواننده می‌تواند موجودیت‌ها را تجزیه و حل کند یا نه. |
| virtual **int32_t** [get_Depth](./get_depth/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، عمق گره فعلی در سند XML را به دست می‌آورد. |
| virtual **bool** [get_EOF](./get_eof/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقداری را که نشان می‌دهد آیا خواننده در انتهای جریان موقعیت دارد یا نه، به دست می‌آورد. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا گره فعلی دارای هر گونه ویژگی است یا نه. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقداری را که نشان می‌دهد آیا گره فعلی می‌تواند مقدار [XmlReader::get_Value](./get_value/) داشته باشد یا نه، به دست می‌آورد. |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقداری را که نشان می‌دهد آیا گره فعلی یک ویژگی است که از مقدار پیش‌فرض تعریف‌شده در DTD یا اسکیمای مرتبط تولید شده یا نه، به دست می‌آورد. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقداری را که نشان می‌دهد آیا گره فعلی یک عنصر خالی است (به عنوان مثال، **<MyElement/>**) یا نه، به دست می‌آورد. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، نام محلی گره فعلی را به دست می‌آورد. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، نام معین گره فعلی را به دست می‌آورد. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، URI فضای‌نام (همان‌طور که در مشخصات فضای‌نام W3C تعریف شده) گره‌ای که خواننده در آن موقعیت دارد را به دست می‌آورد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، [XmlNameTable](../xmlnametable/) مرتبط با این پیاده‌سازی را به دست می‌آورد. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، نوع گره فعلی را به دست می‌آورد. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، پیشوند فضای‌نام مرتبط با گره فعلی را به دست می‌آورد. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، کاراکتر علامت نقل‌قولی را که برای محصور کردن مقدار یک گره ویژگی استفاده می‌شود به دست می‌آورد. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، وضعیت خواننده را به دست می‌آورد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | اطلاعات طرح‌واره‌ای که به عنوان نتیجهٔ اعتبارسنجی طرح‌واره به گره فعلی اختصاص داده شده است را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | شیء [XmlReaderSettings](../xmlreadersettings/) مورد استفاده برای ایجاد این نمونهٔ [XmlReader](./) را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار متنی گرهٔ فعلی را به دست می‌آورد. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | نوع گرهٔ فعلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، حوزهٔ **xml:lang** فعلی را به دست می‌آورد. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، حوزهٔ **xml:space** فعلی را به دست می‌آورد. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار ویژگی با مقدار [XmlReader::get_Name](./get_name/) مشخص شده را به دست می‌آورد. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار ویژگی با مقادیر [XmlReader::get_LocalName](./get_localname/) و [XmlReader::get_NamespaceURI](./get_namespaceuri/) مشخص شده را به دست می‌آورد. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار ویژگی با اندیس مشخص شده را به دست می‌آورد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را به‌دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به‌دست می‌آورد. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار ویژگی با اندیس مشخص شده را به دست می‌آورد. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار ویژگی با مقدار [XmlReader::get_Name](./get_name/) مشخص شده را به دست می‌آورد. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار ویژگی با مقادیر [XmlReader::get_LocalName](./get_localname/) و [XmlReader::get_NamespaceURI](./get_namespaceuri/) مشخص شده را به دست می‌آورد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | مقداری را برمی‌گرداند که نشان می‌دهد آیا آرگومان رشته یک نام XML معتبر است یا نه. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | مقداری را برمی‌گرداند که نشان می‌دهد آیا آرگومان رشته یک توکن نام XML معتبر است یا نه. |
| virtual **bool** [IsStartElement](./isstartelement/)() | متد [XmlReader::MoveToContent](./movetocontent/) را فراخوانی می‌کند و آزمون می‌کند آیا گره محتوای فعلی یک برچسب شروع یا برچسب عنصر خالی است. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | متد [XmlReader::MoveToContent](./movetocontent/) را فراخوانی می‌کند و آزمون می‌کند آیا گره محتوای فعلی یک برچسب شروع یا برچسب عنصر خالی است و آیا مقدار [XmlReader::get_Name](./get_name/) عنصر پیدا‌شده با آرگومان داده‌شده مطابقت دارد. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | متد [XmlReader::MoveToContent](./movetocontent/) را فراخوانی می‌کند و آزمون می‌کند آیا گره محتوای فعلی یک برچسب شروع یا برچسب عنصر خالی است و آیا مقادیر [XmlReader::get_LocalName](./get_localname/) و [XmlReader::get_NamespaceURI](./get_namespaceuri/) عنصر پیدا‌شده با رشته‌های داده‌شده مطابقت دارند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیانیه lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، پیشوند فضای‌نام را در حوزهٔ عنصر فعلی حل می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، به ویژگی با مقدار [XmlReader::get_Name](./get_name/) مشخص حرکت می‌کند. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، به ویژگی با مقادیر [XmlReader::get_LocalName](./get_localname/) و [XmlReader::get_NamespaceURI](./get_namespaceuri/) مشخص حرکت می‌کند. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | هنگامی که در یک کلاس مشتق شده بازنویسی شود، به ویژگی با اندیس مشخص حرکت می‌کند. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | بررسی می‌کند آیا گره فعلی یک گره محتوا است (متن غیر فضای‌سفید، **CDATA**, **Element**, **EndElement**, **EntityReference** یا **EndEntity**). اگر گره یک گره محتوا نباشد، خواننده به گره محتوا بعدی یا انتهای فایل می‌پرد. این عمل گره‌های نوع زیر را نادیده می‌گیرد: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** یا **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، به عنصری که گره ویژگی فعلی را شامل می‌شود حرکت می‌کند. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، به اولین ویژگی حرکت می‌کند. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، به ویژگی بعدی حرکت می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از کلاس‌های فرزند را فراهم می‌کند. |
| virtual **bool** [Read](./read/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، گره بعدی را از جریان می‌خواند. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | هنگامی که در یک کلاس مشتق شده بازنویسی شود، مقدار ویژگی را به یک یا چند گره **[Text](../../system.text/)**, **EntityReference** یا **EndEntity** تجزیه می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتوا را به عنوان یک شیء از نوع مشخص‌شده می‌خواند. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده Base64 را برمی‌گرداند. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شده **BinHex** را برمی‌گرداند. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | متن محتوا را در موقعیت فعلی به عنوان [Boolean](../../system/boolean/) می‌خواند. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | محتوای متنی در موقعیت فعلی را به عنوان شیء [DateTime](../../system/datetime/) می‌خواند. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | محتوای متنی در موقعیت فعلی را به عنوان شیء [DateTimeOffset](../../system/datetimeoffset/) می‌خواند. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | محتوای متنی در موقعیت فعلی را به عنوان شیء [Decimal](../../system/decimal/) می‌خواند. |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | محتوای متنی در موقعیت فعلی را به عنوان عدد نقطه شناور با دقت دو برابر می‌خواند. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | محتوای متنی در موقعیت فعلی را به عنوان عدد نقطه شناور با دقت تک‌باره می‌خواند. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | محتوای متنی در موقعیت فعلی را به عنوان عدد صحیح ۳۲-بیتی می‌خواند. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | محتوای متنی در موقعیت فعلی را به عنوان عدد صحیح ۶۴-بیتی می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | محتوای متنی در موقعیت فعلی را به عنوان یک [Object](../../system/object/) می‌خواند. |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | محتوای متنی در موقعیت فعلی را به عنوان شیء [String](../../system/string/) می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتوای عنصر را به‌عنوان نوع درخواست‌شده می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس محتوای عنصر را به‌عنوان نوع درخواست‌شده می‌خواند. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | عنصر را می‌خواند و محتوای **Base64** را رمزگشایی می‌کند. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | عنصر را می‌خواند و محتوای **BinHex** را رمزگشایی می‌کند. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [Boolean](../../system/boolean/) بازمی‌گرداند. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [Boolean](../../system/boolean/) بازمی‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [DateTime](../../system/datetime/) بازمی‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [DateTime](../../system/datetime/) بازمی‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [Decimal](../../system/decimal/) بازمی‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [Decimal](../../system/decimal/) بازمی‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان عدد نقطه شناور با دقت دو برابر بازمی‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان عدد نقطه شناور با دقت دو برابر بازمی‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان عدد نقطه شناور با دقت تک‌باره بازمی‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان عدد نقطه شناور با دقت تک‌باره بازمی‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان عدد صحیح ۳۲-بیتی بازمی‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان عدد صحیح ۳۲-بیتی بازمی‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان عدد صحیح ۶۴-بیتی بازمی‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان عدد صحیح ۶۴-بیتی بازمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان یک [Object](../../system/object/) بازمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان یک [Object](../../system/object/) بازمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [String](../../system/string/) بازمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتویات را به عنوان شیء [String](../../system/string/) بازمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | عنصری فقط-متنی را می‌خواند. با این حال، توصیه می‌شود به‌جای آن از متد [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) استفاده شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | بررسی می‌کند که مقدار [XmlReader::get_Name](./get_name/) عنصر یافت‌شده با رشتهٔ داده‌شده مطابقت دارد قبل از خواندن عنصر فقط-متنی. با این حال، توصیه می‌شود به‌جای آن از متد [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) استفاده شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که مقادیر [XmlReader::get_LocalName](./get_localname/) و [XmlReader::get_NamespaceURI](./get_namespaceuri/) عنصر یافت‌شده با رشته‌های داده‌شده مطابقت دارد قبل از خواندن عنصر فقط-متنی. با این حال، توصیه می‌شود به‌جای آن از متد [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) استفاده شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual void [ReadEndElement](./readendelement/)() | بررسی می‌کند که گره محتوا فعلی یک برچسب انتهایی است و خواننده را به گره بعدی پیش می‌برد. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | وقتی در کلاس مشتق‌شده بازنویسی شود، تمام محتوا را به‌همراه نشانه‌گذاری به‌صورت رشته می‌خواند. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | وقتی در کلاس مشتق‌شده بازنویسی شود، محتوا را به‌همراه نشانه‌گذاری که این گره و تمام فرزندانش را نشان می‌دهد می‌خواند. |
| virtual void [ReadStartElement](./readstartelement/)() | بررسی می‌کند که گره فعلی یک عنصر است و خواننده را به گره بعدی پیش می‌برد. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | بررسی می‌کند که گره محتوا فعلی یک عنصر با مقدار [XmlReader::get_Name](./get_name/) داده‌شده است و خواننده را به گره بعدی پیش می‌برد. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که گره محتوا فعلی یک عنصر با مقادیر [XmlReader::get_LocalName](./get_localname/) و [XmlReader::get_NamespaceURI](./get_namespaceuri/) داده‌شده است و خواننده را به گره بعدی پیش می‌برد. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | وقتی در کلاس مشتق‌شده بازنویسی شود، محتواهای یک عنصر یا گره متنی را به‌صورت رشته می‌خواند. با این حال، توصیه می‌شود به‌جای آن از متد [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) استفاده شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | نمونهٔ جدیدی از [XmlReader](./) بر می‌گرداند که می‌توان از آن برای خواندن گره فعلی و تمام نوادگانش استفاده کرد. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | [XmlReader](./) را به عنصر نوادگان بعدی با نام معتبر مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](./) را به عنصر نوادگان بعدی با نام محلی و URI فضای‌نام مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | تا یافتن عنصری با نام معتبر مشخص‌شده می‌خواند. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | تا یافتن عنصری با نام محلی و URI فضای‌نام مشخص‌شده می‌خواند. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | [XmlReader](./) را به عنصر همسایه بعدی با نام معتبر مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](./) را به عنصر همسایه بعدی با نام محلی و URI فضای‌نام مشخص‌شده پیش می‌برد. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | جریان‌های بزرگ متن تعبیه‌شده در سند XML را می‌خواند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر پایهٔ ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر پایهٔ ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقادیر با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [ResolveEntity](./resolveentity/)() | وقتی در کلاس مشتق‌شده بازنویسی شود، مرجع موجودیت برای گره‌های **EntityReference** را حل می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به‌عنوان اشاره‌گر ضعیف تنظیم می‌کند (به‌جای Shared). امکان تغییر اشاره‌گرها در مجموعه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را بر می‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [Skip](./skip/)() | فرزندان گرهٔ فعلی را نادیده می‌گیرد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). تبدیل اشیای سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی عبارت C# lock() برای آزادسازی قفل. به‌صورت مستقیم فراخوانی کنید یا از شیء سرپرست [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## تعاریف نوع

| تعری‌ف‌نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## مراجع

* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)