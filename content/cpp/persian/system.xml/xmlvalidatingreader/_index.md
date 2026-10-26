---
title: XmlValidatingReader
second_title: Aspose.Slides برای C++ - مرجع API
description: نمایشی از یک خواننده که اعتبارسنجی تعریف نوع سند (DTD)، طرح‌واره XML-Data Reduced (XDR) و زبان تعریف طرح‌واره XML (XSD) را فراهم می‌کند.
type: docs
weight: 547
url: /fa/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader کلاس

نمایانگر یک خواننده است که اعتبارسنجی تعریف نوع سند (DTD)، طرح‌واره XML-Data Reduced (XDR) و زبان تعریف XML [Schema](../../system.xml.schema/) (XSD) را فراهم می‌کند.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## متدها

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | مقدار [XmlReader::get_ReadState](../xmlreader/get_readstate/) را به Closed تغییر می‌دهد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با URI مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از URI و تنظیمات مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از URI، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از جریان مشخص شده و تنظیمات پیش‌فرض ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از جریان و تنظیمات مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از جریان، URI پایه و تنظیمات مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از جریان، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خوانندهٔ متنی مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خوانندهٔ متنی و تنظیمات مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خوانندهٔ متنی، تنظیمات و URI پایه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خوانندهٔ متنی، تنظیمات و اطلاعات زمینه برای تجزیه ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | یک نمونه جدید از [XmlReader](../xmlreader/) را با استفاده از خوانندهٔ XML و تنظیمات مشخص شده ایجاد می‌کند. |
| void [Dispose](../xmlreader/dispose/)() override | تمام منابع استفاده شده توسط نمونهٔ فعلی کلاس [XmlReader](../xmlreader/) را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | تعداد صفات موجود در گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | URI پایهٔ گرهٔ فعلی را برمی‌گرداند. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | ارزشی را برمی‌گرداند که نشان می‌دهد آیا [XmlValidatingReader](./) متدهای خواندن محتوای باینری را پیاده‌سازی می‌کند یا خیر. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | ارزشی را برمی‌گرداند که نشان می‌دهد آیا [XmlReader](../xmlreader/) متد [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) را پیاده‌سازی می‌کند یا خیر. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | ارزشی را برمی‌گرداند که نشان می‌دهد آیا این خواننده می‌تواند واحدها را تجزیه و حل کند. |
| **int32_t** [get_Depth](./get_depth/)() override | عمق گرهٔ فعلی در سند XML را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | ویژگی رمزگذاری سند را برمی‌گرداند. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | مقداری را برمی‌گرداند که مشخص می‌کند خواننده واحدها را چگونه مدیریت می‌کند. |
| **bool** [get_EOF](./get_eof/)() override | ارزشی را برمی‌گرداند که نشان می‌دهد آیا خواننده در انتهای جریان قرار دارد یا نه. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | ارزشی را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی دارای هر گونه صفتی است یا نه. |
| **bool** [get_HasValue](./get_hasvalue/)() override | ارزشی را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی می‌تواند یک [XmlValidatingReader::get_Value](./get_value/) به جز [String::Empty](../../system/string/empty/) داشته باشد یا نه. |
| **bool** [get_IsDefault](./get_isdefault/)() override | ارزشی را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی صفتی است که از مقدار پیش‌فرض تعریف‌شده در DTD یا طرح‌واره تولید شده است یا نه. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | ارزشی را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی یک عنصر خالی است (به عنوان مثال **<MyElement/>**) یا نه. |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | شمارهٔ خط فعلی را برمی‌گرداند. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | موقعیت کاراکتر در خط فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | نام محلی گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_Name](./get_name/)() override | نام معتبر گرهٔ فعلی را برمی‌گرداند. |
| **bool** [get_Namespaces](./get_namespaces/)() | ارزشی را برمی‌گرداند که نشان می‌دهد آیا پشتیبانی از فضاهای نام فعال باشد یا نه. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | URI فضای نام (به‌عنوان تعریف‌شده در مشخصات نام‌فضای کنسرسیوم جهانی [Web](../../system.web/) (W3C)) گره‌ای که خواننده بر روی آن قرار دارد را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | [XmlNameTable](../xmlnametable/) مرتبط با این پیاده‌سازی را برمی‌گرداند. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | نوع گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | پیشوند فضای نام مرتبط با گرهٔ فعلی را برمی‌گرداند. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | کاراکتر علامت نقل قولی که برای محصور کردن مقدار گرهٔ صفت استفاده می‌شود را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | [XmlReader](../xmlreader/) مورد استفاده برای ساخت این [XmlValidatingReader](./) را برمی‌گرداند. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | وضعیت خواننده را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | اطلاعات طرح‌واره‌ای که به دلیل اعتبارسنجی طرح‌واره به گرهٔ فعلی اختصاص یافته را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | یک XmlSchemaCollection برای استفاده در اعتبارسنجی را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | یک شیء نوع طرح‌واره را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | شیء [XmlReaderSettings](../xmlreadersettings/) مورد استفاده برای ایجاد این نمونهٔ [XmlReader](../xmlreader/) را برمی‌گرداند. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | ارزشی را برمی‌گرداند که نوع اعتبارسنجی انجام‌شده را نشان می‌دهد. |
| [String](../../system/string/) [get_Value](./get_value/)() override | مقدار متنی گرهٔ فعلی را برمی‌گرداند. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | نوع گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | حوزهٔ **xml:lang** فعلی را برمی‌گرداند. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | حوزهٔ **xml:space** فعلی را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | مقدار صفاتی با نام مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | مقدار صفاتی با نام محلی و URI فضای نام مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | مقدار صفاتی با اندیس مشخص‌شده را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را برمی‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌کردن اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گیرد. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| **bool** [HasLineInfo](./haslineinfo/)() override | ارزشی را برمی‌گرداند که نشان می‌دهد آیا کلاس می‌تواند اطلاعات خط را برگرداند یا نه. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | هنگام بازنویسی در یک کلاس مشتق‌شده، مقدار صفات با اندیس مشخص‌شده را برمی‌گرداند. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | هنگام بازنویسی در یک کلاس مشتق‌شده، مقدار صفاتی با مقدار [XmlReader::get_Name](../xmlreader/get_name/) مشخص‌شده را برمی‌گرداند. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | هنگام بازنویسی در یک کلاس مشتق‌شده، مقدار صفاتی با مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) مشخص‌شده را برمی‌گرداند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نشان‌دهندهٔ یک نمونه از نوع شرح‌داده‌شده توسط targetType است یا نه. مشابه عملگر {{}} در C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | ارزشی را برمی‌گرداند که نشان می‌دهد آیا آرگومان رشته یک نام XML معتبر است یا نه. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | ارزشی را برمی‌گرداند که نشان می‌دهد آیا آرگومان رشته یک توکن نام XML معتبر است یا نه. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند که آیا گرهٔ محتوای فعلی یک برچسب شروع یا عنصر خالی است. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند که آیا گرهٔ محتوای فعلی یک برچسب شروع یا عنصر خالی است و آیا مقدار [XmlReader::get_Name](../xmlreader/get_name/) عنصر یافت‌شده با آرگومان داده‌شده مطابقت دارد. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند که آیا گرهٔ محتوای فعلی یک برچسب شروع یا عنصر خالی است و آیا مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) عنصر یافت‌شده با رشته‌های داده‌شده مطابقت دارند. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌کردن دستور C# lock() را انجام می‌دهد. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | پیشوند فضای نام در حوزهٔ عنصر فعلی را حل می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | به صفت با نام مشخص‌شده جابه‌جا می‌شود. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | به صفت با نام محلی و URI فضای نام مشخص‌شده جابه‌جا می‌شود. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | به صفت با اندیس مشخص‌شده جابه‌جا می‌شود. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | بررسی می‌کند که آیا گرهٔ فعلی یک گرهٔ محتوا (متن غیر‌خالی، **CDATA**, **Element**, **EndElement**, **EntityReference**, یا **EndEntity**) است. اگر گره محتوا نباشد، خواننده به گرهٔ محتوا بعدی یا پایان فایل می‌پرد. این عمل گره‌های نوع **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, یا **SignificantWhitespace** را می‌گذرد. |
| **bool** [MoveToElement](./movetoelement/)() override | به عنصری که صفت گرهٔ فعلی را شامل می‌شود جابه‌جا می‌شود. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | به اولین صفت جابه‌جا می‌شود. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | به صفت بعدی جابه‌جا می‌شود. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| **bool** [Read](./read/)() override | گرهٔ بعدی را از جریان می‌خواند. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | مقدار صفت را به یک یا چند گرهٔ **[Text](../../system.text/)**, **EntityReference**, یا **EndEntity** تجزیه می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتوا را به عنوان شیء‌ای از نوع مشخص‌شده می‌خواند. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شدهٔ Base64 را برمی‌گرداند. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | محتوا را می‌خواند و بایت‌های باینری رمزگشایی‌شدهٔ BinHex را برمی‌گرداند. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | متن محتوا را در موقعیت فعلی به عنوان یک [Boolean](../../system/boolean/) می‌خواند. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | متن محتوا را در موقعیت فعلی به عنوان یک شیء [DateTime](../../system/datetime/) می‌خواند. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | متن محتوا را در موقعیت فعلی به عنوان یک شیء [DateTimeOffset](../../system/datetimeoffset/) می‌خواند. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | متن محتوا را در موقعیت فعلی به عنوان یک شیء [Decimal](../../system/decimal/) می‌خواند. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | متن محتوا را در موقعیت فعلی به عنوان یک عدد شناور با دقت دوگانه می‌خواند. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | متن محتوا را در موقعیت فعلی به عنوان یک عدد شناور با دقت تک‌گانه می‌خواند. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | متن محتوا را در موقعیت فعلی به عنوان یک عدد صحیح علامت‌دار ۳۲ بیتی می‌خواند. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | متن محتوا را در موقعیت فعلی به عنوان یک عدد صحیح علامت‌دار ۶۴ بیتی می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | متن محتوا را در موقعیت فعلی به عنوان یک [Object](../../system/object/) می‌خواند. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | متن محتوا را در موقعیت فعلی به عنوان یک شیء [String](../../system/string/) می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتوای عنصر را به‌عنوان نوع درخواست‌شده می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس محتوای عنصر را به نوع درخواست‌شده می‌خواند. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | عنصر را می‌خواند و محتوای Base64 را رمزگشایی می‌کند. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | عنصر را می‌خواند و محتوای BinHex را رمزگشایی می‌کند. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [Boolean](../../system/boolean/) باز می‌گرداند. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [Boolean](../../system/boolean/) باز می‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [DateTime](../../system/datetime/) باز می‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [DateTime](../../system/datetime/) باز می‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [Decimal](../../system/decimal/) باز می‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [Decimal](../../system/decimal/) باز می‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد شناور با دقت دوگانه باز می‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد شناور با دقت دوگانه باز می‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد شناور با دقت تک‌گانه باز می‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد شناور با دقت تک‌گانه باز می‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد صحیح علامت‌دار ۳۲ بیتی باز می‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد صحیح علامت‌دار ۳۲ بیتی باز می‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد صحیح علامت‌دار ۶۴ بیتی باز می‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک عدد صحیح علامت‌دار ۶۴ بیتی باز می‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک [Object](../../system/object/) باز می‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک [Object](../../system/object/) باز می‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [String](../../system/string/) باز می‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [String](../../system/string/) باز می‌گرداند. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | یک عنصر فقط متنی را می‌خواند. البته توصیه می‌شود به جای آن از روش [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) استفاده شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | بررسی می‌کند که مقدار [XmlReader::get_Name](../xmlreader/get_name/) عنصر یافت‌شده با رشتهٔ داده‌شده مطابقت داشته باشد، سپس یک عنصر فقط متنی را می‌خواند. البته توصیه می‌شود به جای آن از روش [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) استفاده شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) عنصر یافت‌شده با رشته‌های داده‌شده مطابقت داشته باشد، سپس یک عنصر فقط متنی را می‌خواند. البته توصیه می‌شود به جای آن از روش [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) استفاده شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | بررسی می‌کند که گره محتوا فعلی یک برچسب پایان باشد و خواننده را به گره بعدی پیش می‌برد. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | زمانی که در یک کلاس مشتق شده بازنویسی شود، تمام محتوا، از جمله نشانه‌گذاری‌ها، را به‌عنوان یک رشته می‌خواند. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | زمانی که در یک کلاس مشتق شده بازنویسی شود، محتوا، شامل نشانه‌گذاری‌ها، که این گره و تمام فرزندان آن را نشان می‌دهد، می‌خواند. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | بررسی می‌کند که گره فعلی یک عنصر باشد و خواننده را به گره بعدی پیش می‌برد. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | بررسی می‌کند که گره محتوا فعلی یک عنصر با مقدار [XmlReader::get_Name](../xmlreader/get_name/) داده‌شده باشد و خواننده را به گره بعدی پیش می‌برد. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که گره محتوا فعلی یک عنصر با مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) داده‌شده باشد و خواننده را به گره بعدی پیش می‌برد. |
| [String](../../system/string/) [ReadString](./readstring/)() override | محتویات یک عنصر یا گره متنی را به‌عنوان یک رشته می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | یک نمونه جدید [XmlReader](../xmlreader/) را برمی‌گرداند که می‌توان از آن برای خواندن گره جاری و تمام نوادگان آن استفاده کرد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر تو‌دستی بعدی با نام کیفی مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر تو‌دستی بعدی با نام محلی و URI فضای نام مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | تا یافتن یک عنصر با نام کیفی مشخص‌شده می‌خواند. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | تا یافتن یک عنصر با نام محلی و URI فضای نام مشخص‌شده می‌خواند. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر برادر بعدی با نام کیفی مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر برادر بعدی با نام محلی و URI فضای نام مشخص‌شده پیش می‌برد. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | نوع زمان اجرا را برای نوع زبان تعریف XML [Schema](../../system.xml.schema/) (XSD) مشخص‌شده برمی‌گرداند. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | جریان‌های بزرگ متن تعبیه‌شده در یک سند XML را می‌خواند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مقایسه مرجع انجام می‌دهد. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را با مقدار مشخص کاهش می‌دهد. |
| void [ResolveEntity](./resolveentity/)() override | مرجع موجودیت برای گره‌های **EntityReference** را حل می‌کند. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | مقداری را تنظیم می‌کند که نحوه‌ی پردازش موجودیت‌ها توسط خواننده را مشخص می‌سازد. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا پشتیبانی از فضای نام انجام شود یا نه. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | مقداری را تنظیم می‌کند که نوع اعتبارسنجی را که باید انجام شود، نشان می‌دهد. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | [XmlResolver](../xmlresolver/) مورد استفاده برای حل مراجع تعریف نوع سند خارجی (DTD) و موقعیت‌های طرح‌واره را تنظیم می‌کند. همچنین [XmlResolver](../xmlresolver/) برای پردازش هر عنصر import یا include موجود در طرح‌واره‌های زبان تعریف XML [Schema](../../system.xml.schema/) (XSD) استفاده می‌شود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [Skip](../xmlreader/skip/)() | فراز فرزندان گره فعلی را رد می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) زبان C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی دستور lock() زبان C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | یک handler رویداد برای دریافت اطلاعات درباره تعریف نوع سند (DTD)، طرح‌واره XML-Data Reduced (XDR) و خطاهای اعتبارسنجی طرح‌واره زبان تعریف XML [Schema](../../system.xml.schema/) (XSD) اضافه می‌کند. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | یک handler رویداد برای دریافت اطلاعات درباره تعریف نوع سند (DTD)، طرح‌واره XML-Data Reduced (XDR) و خطاهای اعتبارسنجی طرح‌واره زبان تعریف XML [Schema](../../system.xml.schema/) (XSD) حذف می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | یک نمونه جدید از کلاس [XmlValidatingReader](./) که محتوا را از [XmlReader](../xmlreader/) داده‌شده اعتبارسنجی می‌کند، مقداردهی اولیه می‌کند. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از کلاس [XmlValidatingReader](./) را با مقادیر مشخص‌شده مقداردهی اولیه می‌کند. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از کلاس [XmlValidatingReader](./) را با مقادیر مشخص‌شده مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس. |
## ملاحظات

منسوخ
:   این کلاس منقضی‌شده است. توصیه می‌شود از کلاس [XmlReaderSettings](../xmlreadersettings/) و متد [XmlReader::Create](../xmlreader/create/) برای ایجاد یک خواننده XML اعتبارسنجی استفاده شود.
شیء‌های این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا خواهد شد. همیشه این کلاس را در داخل یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال آن به توابع به عنوان آرگومان استفاده کنید. 

## موارد مرتبط

* کلاس [XmlReader](../xmlreader/)
* کلاس [IXmlLineInfo](../ixmllineinfo/)
* کلاس [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* فضای نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)