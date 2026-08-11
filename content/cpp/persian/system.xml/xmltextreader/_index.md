---
title: XmlTextReader
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک خواننده است که دسترسی سریع، بدون کش و فقط-به-پیش به داده‌های XML را فراهم می‌کند.
type: docs
weight: 508
url: /fa/system.xml/xmltextreader/
---
## کلاس XmlTextReader

یک خواننده را نشان می‌دهد که دسترسی سریع، بدون‌کش و فقط-جهت‌دار به داده‌های XML را فراهم می‌کند.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Close](./close/)() override | [XmlReader::get_ReadState](../xmlreader/get_readstate/) را به **Closed** تغییر می‌دهد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | یک نمونه جدید از [XmlReader](../xmlreader/) با URI مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | با استفاده از URI و تنظیمات مشخص، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | با استفاده از URI، تنظیمات و اطلاعات زمینه برای تجزیه، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | با استفاده از جریان مشخص و تنظیمات پیش‌فرض، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | یک نمونه جدید از [XmlReader](../xmlreader/) را با جریان و تنظیمات مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | با استفاده از جریان، URI پایه و تنظیمات مشخص، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | با استفاده از جریان، تنظیمات و اطلاعات زمینه برای تجزیه، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | با استفاده از خوانندهٔ متن مشخص، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | با استفاده از خوانندهٔ متن و تنظیمات مشخص، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | با استفاده از خوانندهٔ متن، تنظیمات و URI پایهٔ مشخص، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | با استفاده از خوانندهٔ متن، تنظیمات و اطلاعات زمینه برای تجزیه، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | با استفاده از خوانندهٔ XML و تنظیمات مشخص، یک نمونه جدید از [XmlReader](../xmlreader/) ایجاد می‌کند. |
| void [Dispose](../xmlreader/dispose/)() override | تمام منابع مورد استفاده توسط نمونهٔ فعلی کلاس [XmlReader](../xmlreader/) را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشار شبیه به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشار شبیه به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | تعداد ویژگی‌های گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | URI پایهٔ گرهٔ فعلی را برمی‌گرداند. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlTextReader](./) متدهای خواندن محتوی باینری را پیاده‌سازی می‌کند یا نه. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlTextReader](./) متد [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) را پیاده‌سازی می‌کند یا نه. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | مقدار را برمی‌گرداند که نشان می‌دهد آیا این خواننده می‌تواند موجودیت‌ها را تجزیه و حل کند یا نه. |
| **int32_t** [get_Depth](./get_depth/)() override | عمق گرهٔ فعلی در سند XML را برمی‌گرداند. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | شیء شمارشی DtdProcessing را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | کدگذاری سند را برمی‌گرداند. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | مقداری را برمی‌گرداند که مشخص می‌کند خواننده موجودیت‌ها را چگونه مدیریت می‌کند. |
| **bool** [get_EOF](./get_eof/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا خواننده در انتهای جریان قرار دارد یا نه. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی دارای هر گونه ویژگی‌ای است یا نه. |
| **bool** [get_HasValue](./get_hasvalue/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی می‌تواند یک [XmlTextReader::get_Value](./get_value/) غیر از [String::Empty](../../system/string/empty/) داشته باشد یا نه. |
| **bool** [get_IsDefault](./get_isdefault/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی یک ویژگی است که از مقدار پیش‌فرض تعریف‌شده در DTD یا طرحواره تولید شده است یا نه. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی یک عنصر خالی است (برای مثال، **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | شمارهٔ خط فعلی را برمی‌گرداند. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | موقعیت فعلی خط را برمی‌گرداند. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | نام محلی گرهٔ فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_Name](./get_name/)() override | نام جامع گرهٔ فعلی را برمی‌گرداند. |
| **bool** [get_Namespaces](./get_namespaces/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا پشتیبانی از فضای نام انجام شود یا نه. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | URI فضای نام (طبق تعریف مشخصات فضای نام W3C) گره‌ای که خواننده بر روی آن قرار دارد را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | [XmlNameTable](../xmlnametable/) مرتبط با این پیاده‌سازی را برمی‌گرداند. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | نوع گرهٔ فعلی را برمی‌گرداند. |
| **bool** [get_Normalization](./get_normalization/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا فاصله‌سفید و مقادیر ویژگی‌ها نرمال شوند یا نه. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | پیشوند فضای نام مرتبط با گرهٔ فعلی را برمی‌گرداند. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا پردازش DTD مجاز باشد یا نه. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | کاراکتر علامت نقل قولی که برای محصور کردن مقدار یک گرهٔ ویژگی استفاده می‌شود را برمی‌گرداند. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | وضعیت خواننده را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | اطلاعات طرح‌بندی که به‌دلیل اعتبارسنجی طرح‌بندی به گرهٔ فعلی اختصاص داده شده است را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | شیء [XmlReaderSettings](../xmlreadersettings/) مورد استفاده برای ایجاد این نمونهٔ [XmlReader](../xmlreader/) را برمی‌گرداند. |
| [String](../../system/string/) [get_Value](./get_value/)() override | مقدار متنی گرهٔ فعلی را برمی‌گرداند. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | نوع گرهٔ فعلی را برمی‌گرداند. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | مقداری را برمی‌گرداند که مشخص می‌کند فاصله‌سفید چگونه مدیریت شود. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | محدودهٔ **xml:lang** فعلی را برمی‌گرداند. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | محدودهٔ **xml:space** فعلی را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | مقدار ویژگی با نام مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | مقدار ویژگی با نام محلی و URI فضای نام مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | مقدار ویژگی با اندیس مشخص‌شده را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | مجموعه‌ای را برمی‌گرداند که شامل تمام فضاهای نامی است که در حال حاضر در-دامنه هستند. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | باقیماندهٔ XML بافرشده را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| **bool** [HasLineInfo](./haslineinfo/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا کلاس می‌تواند اطلاعات خط را برگرداند یا نه. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، مقدار ویژگی با اندیس مشخص‌شده را دریافت می‌کند. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، مقدار ویژگی با مقدار [XmlReader::get_Name](../xmlreader/get_name/) مشخص‌شده را دریافت می‌کند. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، مقدار ویژگی با مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) مشخص‌شده را دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | مقداری را برمی‌گرداند که نشان می‌دهد آیا آرگومان رشته یک نام XML معتبر است یا نه. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | مقداری را برمی‌گرداند که نشان می‌دهد آیا آرگومان رشته یک توکن نام XML معتبر است یا نه. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | متد [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند آیا گرهٔ محتوای فعلی یک برچسب شروع یا برچسب عنصر خالی است. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | متد [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند آیا گرهٔ محتوای فعلی یک برچسب شروع یا برچسب عنصر خالی است و آیا مقدار [XmlReader::get_Name](../xmlreader/get_name/) عنصر یافت‌شده با آرگومان داده‌شده مطابقت دارد. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | متد [XmlReader::MoveToContent](../xmlreader/movetocontent/) را فراخوانی می‌کند و بررسی می‌کند آیا گرهٔ محتوای فعلی یک برچسب شروع یا برچسب عنصر خالی است و آیا مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) عنصر یافت‌شده با رشته‌های داده‌شده مطابقت دارند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | پیشوند فضای نام را در دامنه عنصر فعلی حل می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | به ویژگی با نام مشخص‌شده می‌رود. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | به ویژگی با نام محلی و URI فضای نام مشخص‌شده می‌رود. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | به ویژگی با اندیس مشخص‌شده می‌رود. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | بررسی می‌کند آیا گرهٔ فعلی یک گرهٔ محتوا (متن غیر فاصله‌سفید، **CDATA**، **Element**، **EndElement**، **EntityReference** یا **EndEntity**) است. اگر گره محتوا نیست، خواننده به گرهٔ محتوا بعدی یا انتهای فایل می‌پرد. گره‌های نوع زیر را نادیده می‌گیرد: **ProcessingInstruction**، **DocumentType**، **Comment**، **Whitespace** یا **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | به عنصری که گرهٔ ویژگی فعلی را شامل می‌شود می‌رود. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | به اولین ویژگی می‌رود. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | به ویژگی بعدی می‌رود. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌سازد. |
| **bool** [Read](./read/)() override | گرهٔ بعدی را از جریان می‌خواند. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | مقدار ویژگی را به یک یا چند گرهٔ **[Text](../../system.text/)**، **EntityReference** یا **EndEntity** تجزیه می‌کند. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Base64 را رمزگشایی کرده و بایت‌های باینری رمزگشایی‌شده را برمی‌گرداند. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | **BinHex** را رمزگشایی کرده و بایت‌های باینری رمزگشایی‌شده را برمی‌گرداند. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | متن محتوای یک عنصر را در یک بافر کاراکتری می‌خواند. این متد برای خواندن جریان‌های بزرگ متن توکار با فراخوانی متوالی طراحی شده است. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتوا را به‌عنوان یک شیء از نوع مشخص‌شده می‌خواند. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | محتوا را می‌خواند و بایت‌های باینری دیکد شده **Base64** را برمی‌گرداند. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | محتوا را می‌خواند و بایت‌های باینری دیکد شده **BinHex** را برمی‌گرداند. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | متن محتوا را در موقعیت فعلی به‌عنوان یک [Boolean](../../system/boolean/) می‌خواند. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | متن محتوا را در موقعیت فعلی به‌عنوان یک شیء [DateTime](../../system/datetime/) می‌خواند. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | متن محتوا را در موقعیت فعلی به‌عنوان یک شیء [DateTimeOffset](../../system/datetimeoffset/) می‌خواند. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | متن محتوا را در موقعیت فعلی به‌عنوان یک شیء [Decimal](../../system/decimal/) می‌خواند. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | متن محتوا را در موقعیت فعلی به‌عنوان عدد شناور با دقت دو برابر می‌خواند. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | متن محتوا را در موقعیت فعلی به‌عنوان عدد ممیز شناور تک‌دقت می‌خواند. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | متن محتوا را در موقعیت فعلی به‌عنوان عدد صحیح 32 بیتی با علامت می‌خواند. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | متن محتوا را در موقعیت فعلی به‌عنوان عدد صحیح 64 بیتی با علامت می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | متن محتوا را در موقعیت فعلی به‌عنوان یک [Object](../../system/object/) می‌خواند. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | متن محتوا را در موقعیت فعلی به‌عنوان یک شیء [String](../../system/string/) می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | محتوای عنصر را به‌عنوان نوع درخواست‌شده می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس محتوای عنصر را به‌عنوان نوع درخواست‌شده می‌خواند. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | عنصر را می‌خواند و محتوای Base64 را دیکد می‌کند. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | عنصر را می‌خواند و محتوای **BinHex** را دیکد می‌کند. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان یک شیء [Boolean](../../system/boolean/) برمی‌گرداند. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [Boolean](../../system/boolean/) برمی‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان یک شیء [DateTime](../../system/datetime/) برمی‌گرداند. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [DateTime](../../system/datetime/) برمی‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان یک شیء [Decimal](../../system/decimal/) برمی‌گرداند. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [Decimal](../../system/decimal/) برمی‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان عدد شناور با دقت دو برابر برمی‌گرداند. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان عدد شناور با دقت دو برابر برمی‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان عدد ممیز شناور تک‌دقت برمی‌گرداند. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان عدد ممیز شناور تک‌دقت برمی‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان عدد صحیح 32 بیتی با علامت برمی‌گرداند. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان عدد صحیح 32 بیتی با علامت برمی‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان عدد صحیح 64 بیتی با علامت برمی‌گرداند. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان عدد صحیح 64 بیتی با علامت برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان یک [Object](../../system/object/) برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک [Object](../../system/object/) برمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | عنصر جاری را می‌خواند و محتوا را به‌عنوان یک شیء [String](../../system/string/) برمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که نام محلی و URI فضای‌نام مشخص‌شده با عنصر فعلی مطابقت دارد، سپس عنصر فعلی را می‌خواند و محتوا را به‌عنوان یک شیء [String](../../system/string/) برمی‌گرداند. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | یک عنصر فقط متنی را می‌خواند. با این حال، استفاده از متد [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) توصیه می‌شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | قبل از خواندن یک عنصر فقط متنی، بررسی می‌کند که مقدار [XmlReader::get_Name](../xmlreader/get_name/) عنصر یافت‌شده با رشته‌ی داده‌شده مطابقت داشته باشد. با این حال، استفاده از متد [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) توصیه می‌شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | قبل از خواندن یک عنصر فقط متنی، بررسی می‌کند که مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) عنصر یافت‌شده با رشته‌های داده‌شده مطابقت داشته باشند. با این حال، استفاده از متد [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) توصیه می‌شود، زیرا راهی ساده‌تر برای انجام این عملیات فراهم می‌کند. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | بررسی می‌کند که گره محتوا فعلی یک برچسب انتهایی است و خواننده را به گره بعدی پیش می‌برد. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، تمام محتوا شامل نشانه‌گذاری را به‌عنوان یک رشته می‌خواند. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، محتوا را شامل نشانه‌گذاری که این گره و تمام فرزندان آن را نشان می‌دهد می‌خواند. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | بررسی می‌کند که گره فعلی یک عنصر باشد و خواننده را به گره بعدی پیش می‌برد. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | بررسی می‌کند که گره محتوا فعلی یک عنصر با مقدار [XmlReader::get_Name](../xmlreader/get_name/) داده‌شده باشد و خواننده را به گره بعدی پیش می‌برد. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | بررسی می‌کند که گره محتوا فعلی یک عنصر با مقادیر [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) داده‌شده باشد و خواننده را به گره بعدی پیش می‌برد. |
| [String](../../system/string/) [ReadString](./readstring/)() override | محتواهای یک عنصر یا گره متن را به‌عنوان یک رشته می‌خواند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | یک نمونه جدید از [XmlReader](../xmlreader/) باز می‌گرداند که می‌توان برای خواندن گره فعلی و تمام فرزندانش استفاده کرد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر فرزند بعدی با نام معتبر مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر فرزند بعدی با نام محلی و URI فضای‌نام مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | تا زمانی که عنصری با نام معتبر مشخص‌شده یافت شود، می‌خواند. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | تا زمانی که عنصری با نام محلی و URI فضای‌نام مشخص‌شده یافت شود، می‌خواند. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر همسایه بعدی با نام معتبر مشخص‌شده پیش می‌برد. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) را به عنصر همسایه بعدی با نام محلی و URI فضای‌نام مشخص‌شده پیش می‌برد. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | جریان‌های بزرگ متن توکار در یک سند XML را می‌خواند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌های مشترک را به‌وسیلۀ مقدار مشخص‌شده کاهش می‌دهد. |
| void [ResetState](./resetstate/)() | وضعیت خواننده را به [ReadState::Initial](../readstate/) بازنشانی می‌کند. |
| void [ResolveEntity](./resolveentity/)() override | مرجع نهاد (**EntityReference**) را حل می‌کند. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | مقدار شمارش DtdProcessing را تنظیم می‌کند. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | مقداری را تنظیم می‌کند که نحوهٔ پردازش نهادها توسط خواننده را تعیین می‌کند. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | مقداری را تنظیم می‌کند که نشان‌دهنده این است که آیا پشتیبانی از فضای‌نام فعال باشد یا خیر. |
| void [set_Normalization](./set_normalization/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا فضاهای خالی و مقادیر ویژگی‌ها نرمال‌سازی شوند یا خیر. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا پردازش DTD اجازه داده شود یا خیر. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | مقداری را تنظیم می‌کند که نحوهٔ پردازش فضاهای خالی را مشخص می‌کند. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | [XmlResolver](../xmlresolver/) مورد استفاده برای حل مراجع DTD را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع‌های مشترک را برمی‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع‌های مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع‌های مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Skip](./skip/)() override | فرزندان گره فعلی را نادیده می‌گیرد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بی‌قفل C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده نمایید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش مرجع‌های ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش مرجع‌های ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با جریان مشخص شده مقداردهی اولیه می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با URL و جریان مشخص شده مقداردهی اولیه می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با جریان و [XmlNameTable](../xmlnametable/) مشخص شده مقداردهی اولیه می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با URL، جریان و [XmlNameTable](../xmlnametable/) مشخص شده مقداردهی اولیه می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با TextReader مشخص شده ایجاد می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با URL و TextReader مشخص شده ایجاد می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با TextReader و [XmlNameTable](../xmlnametable/) مشخص شده ایجاد می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با URL، TextReader و [XmlNameTable](../xmlnametable/) مشخص شده ایجاد می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با stream، XmlNodeType و [XmlParserContext](../xmlparsercontext/) مشخص شده ایجاد می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با string، XmlNodeType و [XmlParserContext](../xmlparsercontext/) مشخص شده ایجاد می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با file مشخص شده ایجاد می‌کند. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | یک نمونه جدید از کلاس [XmlTextReader](./) را با file و [XmlNameTable](../xmlnametable/) مشخص شده ایجاد می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای shared pointer به یک نمونه از این کلاس است. |
## ملاحظات



توصیه می‌شود به جای آن از کلاس [XmlReader](../xmlreader/) استفاده شود. 

اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌های این نوع را روی стек یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید. 

## مراجع مرتبط

* کلاس [XmlReader](../xmlreader/)
* کلاس [IXmlLineInfo](../ixmllineinfo/)
* کلاس [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* فضای نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)