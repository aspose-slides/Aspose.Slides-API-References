---
title: XmlNodeReader
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک خواننده که دسترسی سریع، بدون کش و فقط به جلو به داده‌های XML در یک XmlNode را فراهم می‌کند.
type: docs
weight: 365
url: /fa/system.xml/xmlnodereader/
---
## XmlNodeReader کلاس

نمایانگر یک خواننده است که دسترسی سریع، بدون ذخیره‌سازی کش و فقط به پیش برای داده‌های XML در یک [XmlNode](../xmlnode/) فراهم می‌کند.

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Close](./close/)() override | مقدار [XmlNodeReader::get_ReadState](./get_readstate/) را به [ReadState::Closed](../readstate/) تغییر می‌دهد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](../xmlreader/) با URI مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از URI و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از URI، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از استریم مشخص و تنظیمات پیش‌فرض ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استریم و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از استریم، URI پایه و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از استریم، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خواننده متن مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خواننده متن و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خواننده متن، تنظیمات و URI پایه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خواننده متن، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خواننده XML و تنظیمات مشخص ایجاد می‌کند. |
| void [Dispose](../xmlreader/dispose/)() override | تمام منابع استفاده‌شده توسط نمونهٔ فعلی کلاس [XmlReader](../xmlreader/) را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | تعداد ویژگی‌های گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | URI پایهٔ گرهٔ فعلی را برمی‌گرداند. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlNodeReader](./) روش‌های خواندن محتوای باینری را پیاده‌سازی می‌کند یا خیر. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlReader](../xmlreader/) متد [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) را پیاده‌سازی می‌کند یا خیر. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا این خواننده می‌تواند موجودیت‌ها را تجزیه و حل کند یا خیر. |
| **int32_t** [get_Depth](./get_depth/)() override | عمق گرهٔ فعلی در سند XML را برمی‌گرداند. |
| **bool** [get_EOF](./get_eof/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا خواننده در انتهای استریم قرار دارد یا خیر. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی هیچ ویژگی‌ای دارد یا خیر. |
| **bool** [get_HasValue](./get_hasvalue/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی می‌تواند مقدار [XmlNodeReader::get_Value](./get_value/) داشته باشد یا خیر. |
| **bool** [get_IsDefault](./get_isdefault/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی یک ویژگی است که از مقدار پیش‌فرض تعریف‌شده در DTD یا Schema تولید شده است یا خیر. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی یک عنصر خالی است (به عنوان مثال, **<MyElement/>**) یا خیر. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | نام محلی گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_Name](./get_name/)() override | نام کامل (Qualified) گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | URI فضای نام (همان‌طور که در مشخصات فضای نام W3C تعریف شده) گره‌ای که خواننده بر روی آن قرار دارد را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | مقدار [XmlNameTable](../xmlnametable/) مرتبط با این پیاده‌سازی را برمی‌گرداند. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | نوع گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | پیشوند فضای نام مرتبط با گرهٔ فعلی را برمی‌گرداند. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | در کلاس مشتق‌شده که بازنویسی می‌شود، کاراکتر علامت نقل‌قولی را برمی‌گرداند که برای محصور کردن مقدار یک گره ویژگی استفاده می‌شود. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | وضعیت خواننده را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | اطلاعات طرح (Schema) که به گرهٔ فعلی اختصاص یافته است را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | شیء [XmlReaderSettings](../xmlreadersettings/) را که برای ایجاد این نمونهٔ [XmlReader](../xmlreader/) استفاده شده است برمی‌گرداند. |
| [String](../../system/string/) [get_Value](./get_value/)() override | مقدار متنی گرهٔ فعلی را برمی‌گرداند. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | نوع گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | قابلیت **xml:lang** فعلی را برمی‌گرداند. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | قابلیت **xml:space** فعلی را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | مقدار ویژگی با نام محلی و URI فضای نام مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | مقدار ویژگی با اندیس مشخص‌شده را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | در کلاس مشتق‌شده که بازنویسی می‌شود، مقدار ویژگی با اندیس مشخص‌شده را برمی‌گرداند. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | در کلاس مشتق‌شده که بازنویسی می‌شود، مقدار ویژگی با مقدار [XmlReader::get_Name](../xmlreader/get_name/) مشخص‌شده را برمی‌گرداند. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | در کلاس مشتق‌شده که بازنویسی می‌شود، مقدار ویژگی با مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) مشخص‌شده را برمی‌گرداند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | مقداری را برمی‌گرداند که نشان می‌دهد آیا رشتهٔ ورودی یک نام XML معتبر است یا خیر. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | مقداری را برمی‌گرداند که نشان می‌دهد آیا رشتهٔ ورودی یک توکن نام XML معتبر است یا خیر. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | متد [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند آیا گرهٔ محتوا فعلی یک تگ شروع یا تگ عنصر خالی است. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | متد [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند آیا گرهٔ محتوا فعلی یک تگ شروع یا تگ عنصر خالی است و آیا مقدار [XmlReader::get_Name](../xmlreader/get_name/) عنصر یافت شده با آرگومان داده شده مطابقت دارد. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | متد [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند آیا گرهٔ محتوا فعلی یک تگ شروع یا تگ عنصر خالی است و آیا مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) عنصر یافت شده با رشته‌های داده شده مطابقت دارد. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌ صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | پیشوند فضای نام را در دامنهٔ عنصر فعلی حل می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلونینگ انواع سفارشی را فراهم می‌کند. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | به ویژگی با نام مشخص‌شده می‌رود. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | به ویژگی با نام محلی و URI فضای نام مشخص‌شده می‌رود. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | به ویژگی با اندیس مشخص‌شده می‌رود. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | بررسی می‌کند آیا گرهٔ فعلی یک گرهٔ محتوا (متن غیر فضای سفید، **CDATA**, **Element**, **EndElement**, **EntityReference**, یا **EndEntity**) است. اگر گره محتوا نباشد، خواننده به گرهٔ محتوا بعدی یا انتهای فایل می‌پرد. این کار باعث عبور از گره‌های نوع زیر می‌شود: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, یا **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | به عنصری که گره ویژگی فعلی را شامل می‌شود می‌رود. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | به اولین ویژگی می‌رود. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | به ویژگی بعدی می‌رود. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| **bool** [Read](./read/)() override | گرهٔ بعدی را از استریم می‌خواند. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | مقدار ویژگی را به یک یا چند گره **[Text](../../system.text/)**, **EntityReference** یا **EndEntity** تجزیه می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتوا را به عنوان شیء از نوع مشخص‌شده می‌خواند. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | محتوا را می‌خواند و بایت‌های دودویی رمزگشایی‌شده Base64 را برمی‌گرداند. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | محتوا را می‌خواند و بایت‌های دودویی رمزگشایی‌شده BinHex را برمی‌گرداند. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان [Boolean](../../system/boolean/) می‌خواند. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان شیء [DateTime](../../system/datetime/) می‌خواند. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان شیء [DateTimeOffset](../../system/datetimeoffset/) می‌خواند. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان شیء [Decimal](../../system/decimal/) می‌خواند. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان عدد شناور دو رمزی (double) می‌خواند. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان عدد شناور تک رمزی (float) می‌خواند. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان عدد صحیح ۳۲ بیتی با علامت می‌خواند. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان عدد صحیح ۶۴ بیتی با علامت می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | محتوای متنی موجود در موقعیت فعلی را به عنوان [Object](../../system/object/) می‌خواند. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | متن محتوا را در موقعیت فعلی به عنوان یک شیء [String](../../system/string/) می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتویات عنصر را به عنوان نوع درخواست‌شده می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس محتوای عنصر را به عنوان نوع درخواست‌شده می‌خواند. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | عنصر را می‌خواند و محتوای BinHex را رمزگشایی می‌کند. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | عنصر جاری را می‌خواند و محتواها را به عنوان شیء [Boolean](../../system/boolean/) برمی‌گرداند. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان شیء [Boolean](../../system/boolean/) برمی‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | عنصر جاری را می‌خواند و محتواها را به عنوان شیء [DateTime](../../system/datetime/) برمی‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان شیء [DateTime](../../system/datetime/) برمی‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | عنصر جاری را می‌خواند و محتواها را به عنوان شیء [Decimal](../../system/decimal/) برمی‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان شیء [Decimal](../../system/decimal/) برمی‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | عنصر جاری را می‌خواند و محتواها را به عنوان عدد اعشاری دوبل دقیق برمی‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان عدد اعشاری دوبل دقیق برمی‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | عنصر جاری را می‌خواند و محتواها را به عنوان عدد اعشاری تک‌دقت برمی‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان عدد اعشاری تک‌دقت برمی‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | عنصر جاری را می‌خواند و محتواها را به عنوان یک عدد صحیح ۳۲ بیتی با علامت برمی‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان یک عدد صحیح ۳۲ بیتی با علامت برمی‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | عنصر جاری را می‌خواند و محتواها را به عنوان یک عدد صحیح ۶۴ بیتی با علامت برمی‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان یک عدد صحیح ۶۴ بیتی با علامت برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | عنصر جاری را می‌خواند و محتواها را به عنوان یک [Object](../../system/object/) برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان یک [Object](../../system/object/) برمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | عنصر جاری را می‌خواند و محتواها را به عنوان یک شیء [String](../../system/string/) برمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر جاری مطابقت دارد، سپس عنصر جاری را می‌خواند و محتواها را به عنوان یک شیء [String](../../system/string/) برمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | یک عنصر فقط-متنی را می‌خواند. با این حال، توصیه می‌شود به‌جای آن از متد [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) استفاده کنید، زیرا راه‌حل ساده‌تری برای انجام این عملیات ارائه می‌دهد. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | بررسی می‌کند که مقدار [XmlReader::get_Name](../xmlreader/get_name/) عنصر یافت‌شده با رشتهٔ داده‌شده مطابقت دارد قبل از خواندن یک عنصر فقط-متنی. با این حال، توصیه می‌شود به‌جای آن از متد [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) استفاده کنید، زیرا راه‌حل ساده‌تری برای انجام این عملیات ارائه می‌دهد. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که مقدار [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) عنصر یافت‌شده با رشته‌های داده‌شده مطابقت دارد قبل از خواندن یک عنصر فقط-متنی. با این حال، توصیه می‌شود به‌جای آن از متد [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) استفاده کنید، زیرا راه‌حل ساده‌تری برای انجام این عملیات ارائه می‌دهد. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | بررسی می‌کند که گرهٔ محتوای جاری یک برچسب انتهایی است و خواننده را به گرهٔ بعدی پیش می‌برد. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | هنگامی که در کلاس مشتق‌شده بازنویسی شود، تمام محتوا شامل علامت‌گذاری را به‌صورت رشته‌ای می‌خواند. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | هنگامی که در کلاس مشتق‌شده بازنویسی شود، محتوا، شامل علامت‌گذاری، که نمایانگر این گره و تمام فرزندان آن است را می‌خواند. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | بررسی می‌کند که گرهٔ جاری یک عنصر است و خواننده را به گرهٔ بعدی پیش می‌برد. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | بررسی می‌کند که گرهٔ محتوای جاری یک عنصر با مقدار [XmlReader::get_Name](../xmlreader/get_name/) داده‌شده است و خواننده را به گرهٔ بعدی پیش می‌برد. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که گرهٔ محتوای جاری یک عنصر با مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) داده‌شده است و خواننده را به گرهٔ بعدی پیش می‌برد. |
| [String](../../system/string/) [ReadString](./readstring/)() override | محتویات یک عنصر یا گرهٔ متنی را به‌صورت رشته می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | یک نمونهٔ جدید [XmlReader](../xmlreader/) را برمی‌گرداند که می‌تواند برای خواندن گرهٔ جاری و تمام نوادگان آن استفاده شود. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر نوادگان بعدی با نام واجد شرایط مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر نوادگان بعدی با نام محلی و URI فضای‌نام مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | تا زمانی که عنصری با نام واجد شرایط مشخص پیدا شود، می‌خواند. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | تا زمانی که عنصری با نام محلی و URI فضای‌نام مشخص پیدا شود، می‌خواند. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر خواهر بعدی با نام واجد شرایط مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر خواهر بعدی با نام محلی و URI فضای‌نام مشخص‌شده پیش می‌برد. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | جریان‌های بزرگ متن جاسازی‌شده در سند XML را می‌خواند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را برحسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را برحسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | آبجکت‌های نوع مقدار را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [ResolveEntity](./resolveentity/)() override | مرجع موجودیت را برای گره‌های **EntityReference** حل می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [Skip](./skip/)() override | فرزندان گرهٔ جاری را نادیده می‌گیرد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل آبجکت‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند-اشاره‌گرها یا ThisProtector استفاده کنید. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | یک نمونه از کلاس [XmlNodeReader](./) را با استفاده از [XmlNode](../xmlnode/) مشخص‌شده ایجاد می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | آبجکت را از بین می‌برد. تمام ساختارهای داخلی داده را آزاد می‌کند. |

## تعریف‌نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## یادداشت‌ها

اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌های این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. 

## همچنین ببینید

* کلاس [XmlReader](../xmlreader/)
* کلاس [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* فضای‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)