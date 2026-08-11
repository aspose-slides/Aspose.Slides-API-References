---
title: XmlReader
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل قارئًا يوفر وصولًا سريعًا وغير مخزن مؤقتًا وإلى الأمام فقط إلى بيانات XML.
type: docs
weight: 430
url: /ar/system.xml/xmlreader/
---
## فئة XmlReader

يمثل قارئًا يوفر وصولًا سريعًا غير مخزن مؤقتًا وإلى الأمام فقط إلى بيانات XML.

```cpp
class XmlReader : public System::IDisposable
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Close](./close/)() | عند تجاوزها في فئة مشتقة، تغير [XmlReader::get_ReadState](./get_readstate/) إلى [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام URI المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام URI والإعدادات المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام URI المحدد والإعدادات ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام الدفق المحدد مع الإعدادات الافتراضية. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام الدفق والإعدادات المحددين. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام الدفق المحدد، URI الأساسي، والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام الدفق المحدد، الإعدادات، ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام قارئ النص المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام قارئ النص والإعدادات المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام قارئ النص المحدد، الإعدادات، وURI الأساسي. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام قارئ النص المحدد، الإعدادات، ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | ينشئ كائنًا جديدًا من [XmlReader](./) باستخدام قارئ XML المحدد والإعدادات. |
| void [Dispose](./dispose/)() override | يفرج جميع الموارد المستخدمة بواسطة المثال الحالي من الفئة [XmlReader](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN ين متساويين بالرغم من أن IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN ين متساويين بالرغم من أن IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | عند تجاوزها في فئة مشتقة، يحصل على عدد السمات في العقدة الحالية. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | عند تجاوزها في فئة مشتقة، يحصل على URI الأساسي للعقدة الحالية. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | يرجع قيمة تُظهر ما إذا كان [XmlReader](./) يدعم أساليب قراءة المحتوى الثنائي. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | يرجع قيمة تُظهر ما إذا كان [XmlReader](./) يدعم طريقة [XmlReader::ReadValueChunk](./readvaluechunk/). |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | يرجع قيمة تُظهر ما إذا كان هذا القارئ يستطيع تحليل الكيانات وحلها. |
| virtual **int32_t** [get_Depth](./get_depth/)() | عند تجاوزها في فئة مشتقة، يحصل على عمق العقدة الحالية في مستند XML. |
| virtual **bool** [get_EOF](./get_eof/)() | عند تجاوزها في فئة مشتقة، يحصل على قيمة تُظهر ما إذا كان القارئ في نهاية الدفق. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | يرجع قيمة تُظهر ما إذا كانت العقدة الحالية تحتوي على أي سمات. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | عند تجاوزها في فئة مشتقة، يحصل على قيمة تُظهر ما إذا كانت العقدة الحالية يمكن أن تحتوي على قيمة [XmlReader::get_Value](./get_value/). |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | عند تجاوزها في فئة مشتقة، يحصل على قيمة تُظهر ما إذا كانت العقدة الحالية سمة تم توليدها من القيمة الافتراضية المعرفة في DTD أو المخطط. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | عند تجاوزها في فئة مشتقة، يحصل على قيمة تُظهر ما إذا كانت العقدة الحالية عنصرًا فارغًا (مثال: **<MyElement/>**). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | عند تجاوزها في فئة مشتقة، يحصل على الاسم المحلي للعقدة الحالية. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | عند تجاوزها في فئة مشتقة، يحصل على الاسم المؤهل للعقدة الحالية. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | عند تجاوزها في فئة مشتقة، يحصل على URI مساحة الاسم (كما هو معرف في مواصفة مساحة أسماء W3C) للعقدة التي يقع عليها القارئ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | عند تجاوزها في فئة مشتقة، يحصل على [XmlNameTable](../xmlnametable/) المرتبط بهذا التنفيذ. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | عند تجاوزها في فئة مشتقة، يحصل على نوع العقدة الحالية. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | عند تجاوزها في فئة مشتقة، يحصل على بادئة مساحة الاسم المرتبطة بالعقدة الحالية. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | عند تجاوزها في فئة مشتقة، يحصل على حرف علامات الاقتباس المستخدم لتغليف قيمة عقدة السمة. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | عند تجاوزها في فئة مشتقة، يحصل على حالة القارئ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | يرجع معلومات المخطط التي تم تعيينها للعقدة الحالية نتيجةً للتحقق من صحة المخطط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | يرجع كائن [XmlReaderSettings](../xmlreadersettings/) المستخدم لإنشاء هذا المثال من [XmlReader](./). |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | عند تجاوزها في فئة مشتقة، يحصل على القيمة النصية للعقدة الحالية. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | يرجع النوع للعقدة الحالية. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | عند تجاوزها في فئة مشتقة، يحصل على نطاق **xml:lang** الحالي. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | عند تجاوزها في فئة مشتقة، يحصل على نطاق **xml:space** الحالي. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمة [XmlReader::get_Name](./get_name/) المحددة. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمتين [XmlReader::get_LocalName](./get_localname/) و[XmlReader::get_NamespaceURI](./get_namespaceuri/) المحددتين. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات الفهرس المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية البيانات لعداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات الفهرس المحدد. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمة [XmlReader::get_Name](./get_name/) المحددة. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمتين [XmlReader::get_LocalName](./get_localname/) و[XmlReader::get_NamespaceURI](./get_namespaceuri/) المحددتين. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | يرجع قيمة تُظهر ما إذا كان النص المُعطى اسم XML صالح. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | يرجع قيمة تُظهر ما إذا كان النص المُعطى رمز اسم XML صالح. |
| virtual **bool** [IsStartElement](./isstartelement/)() | ينادى [XmlReader::MoveToContent](./movetocontent/) ويفحص ما إذا كانت عقدة المحتوى الحالية بداية علامة أو علامة عنصر فارغ. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | ينادى [XmlReader::MoveToContent](./movetocontent/) ويفحص ما إذا كانت عقدة المحتوى الحالية بداية علامة أو علامة عنصر فارغ وإذا كانت قيمة [XmlReader::get_Name](./get_name/) للعنصر المطابق تتطابق مع الوسيط المعطى. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | ينادى [XmlReader::MoveToContent](./movetocontent/) ويفحص ما إذا كانت عقدة المحتوى الحالية بداية علامة أو علامة عنصر فارغ وإذا كانت قيمتي [XmlReader::get_LocalName](./get_localname/) و[XmlReader::get_NamespaceURI](./get_namespaceuri/) للعنصر المطابق تتطابق مع السلاسل المعطاة. |
| void [Lock](../../system/object/lock/)() | يُطبق قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | عند تجاوزها في فئة مشتقة، يحل بادئة مساحة الاسم في نطاق العنصر الحالي. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، ينتقل إلى السمة ذات القيمة [XmlReader::get_Name](./get_name/) المحددة. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | عند تجاوزها في فئة مشتقة، ينتقل إلى السمة ذات القيمتين [XmlReader::get_LocalName](./get_localname/) و[XmlReader::get_NamespaceURI](./get_namespaceuri/) المحددتين. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | عند تجاوزها في فئة مشتقة، ينتقل إلى السمة ذات الفهرس المحدد. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | يتحقق مما إذا كانت العقدة الحالية عقدة محتوى (نص غير مساحة بيضاء، **CDATA**، **Element**، **EndElement**، **EntityReference** أو **EndEntity**). إذا لم تكن العقدة عقدة محتوى، يتخطى القارئ إلى العقدة المحتوى التالية أو نهاية الملف. يتخطى العقد من الأنواع التالية: **ProcessingInstruction**، **DocumentType**، **Comment**، **Whitespace** أو **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | عند تجاوزها في فئة مشتقة، ينتقل إلى العنصر الذي يحتوي على عقدة السمة الحالية. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | عند تجاوزها في فئة مشتقة، ينتقل إلى السمة الأولى. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | عند تجاوزها في فئة مشتقة، ينتقل إلى السمة التالية. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| virtual **bool** [Read](./read/)() | عند تجاوزها في فئة مشتقة، يقرأ العقدة التالية من الدفق. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | عند تجاوزها في فئة مشتقة، يحلل قيمة السمة إلى واحد أو أكثر من عقد **[Text](../../system.text/)** أو **EntityReference** أو **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ المحتوى ككائن من النوع المحدد. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يقرأ المحتوى ويعيد بايتات ثنائية مفكوكة الترميز Base64. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يقرأ المحتوى ويعيد بايتات ثنائية مفكوكة الترميز **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | يقرأ محتوى النص في الموضع الحالي كـ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | يقرأ محتوى النص في الموضع الحالي ككائن [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | يقرأ محتوى النص في الموضع الحالي ككائن [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | يقرأ محتوى النص في الموضع الحالي ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | يقرأ محتوى النص في الموضع الحالي كرقم عائم مزدوج الدقة. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | يقرأ محتوى النص في الموضع الحالي كرقم عائم أحادي الدقة. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | يقرأ محتوى النص في الموضع الحالي كعدد صحيح موقّع 32-بت. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | يقرأ محتوى النص في الموضع الحالي كعدد صحيح موقّع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | يقرأ محتوى النص في الموضع الحالي كـ [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | يقرأ محتوى النص في الموضع الحالي ككائن [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ محتوى العنصر بالنوع المطلوب. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يطابقان العنصر الحالي، ثم يقرأ محتوى العنصر بالنوع المطلوب. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يقرأ العنصر ويفك تشفير محتوى **Base64**. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | يقرأ العنصر ويفك تشفير محتوى **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | يقرأ العنصر الحالي ويعيد المحتوى كرقم عائم مزدوج الدقة. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كرقم عائم مزدوج الدقة. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | يقرأ العنصر الحالي ويعيد المحتوى كرقم عائم أحادي الدقة. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كرقم عائم أحادي الدقة. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقّع 32-بت. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقّع 32-بت. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقّع 64-بت. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقّع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | يقرأ العنصر الحالي ويعيد المحتوى كـ [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كـ [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد وعنوان مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | يقرا عنصرًا نصيًا فقط. مع ذلك، يفضَّل استخدام طريقة [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | يتحقق من أن قيمة [XmlReader::get_Name](./get_name/) للعنصر الموجود تتطابق مع السلسلة المعطاة قبل قراءة عنصر نصي فقط. مع ذلك، يفضَّل استخدام طريقة [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن قيمتي [XmlReader::get_LocalName](./get_localname/) و[XmlReader::get_NamespaceURI](./get_namespaceuri/) للعنصر الموجود تتطابقان مع السلاسل المعطاة قبل قراءة عنصر نصي فقط. مع ذلك، يفضَّل استخدام طريقة [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual void [ReadEndElement](./readendelement/)() | يتحقق من أن عقدة المحتوى الحالية هي وسم إغلاق ويتقدم بالقارئ إلى العقدة التالية. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | عند إعادة تعريفه في فئة مشتقة، يقرأ كل المحتوى، بما في ذلك العلامات، كسلسلة نصية. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | عند إعادة تعريفه في فئة مشتقة، يقرأ المحتوى، بما في ذلك العلامات، الذي يمثل هذه العقدة وجميع أبنائها. |
| virtual void [ReadStartElement](./readstartelement/)() | يتحقق من أن العقدة الحالية عنصر ويتقدم بالقارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية عنصر بقيمة [XmlReader::get_Name](./get_name/) المعطاة ويتقدم بالقارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية عنصر بالقيمتين [XmlReader::get_LocalName](./get_localname/) و[XmlReader::get_NamespaceURI](./get_namespaceuri/) المعطاة ويتقدم بالقارئ إلى العقدة التالية. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | عند إعادة تعريفه في فئة مشتقة، يقرأ محتويات عنصر أو عقدة نصية كسلسلة. مع ذلك، يفضَّل استخدام طريقة [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | إرجاع نسخة جديدة من [XmlReader](./) يمكن استخدامها لقراءة العقدة الحالية وجميع فروعها. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | يقوم بتحريك [XmlReader](./) إلى العنصر الفرعي التالي بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | يقوم بتحريك [XmlReader](./) إلى العنصر الفرعي التالي بالاسم المحلي وعنوان مساحة الاسم المحددين. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المحلي وعنوان مساحة الاسم المحددين. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | يقوم بتحريك [XmlReader](./) إلى العنصر الشقيق التالي بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | يقوم بتحريك [XmlReader](./) إلى العنصر الشقيق التالي بالاسم المحلي وعنوان مساحة الاسم المحددين. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يقرأ تدفقات نصية كبيرة مدمجة في مستند XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن قيمة النوع بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [ResolveEntity](./resolveentity/)() | عند إعادة تعريفه في فئة مشتقة، يحل مرجع الكيان لعقد **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ضبط الوسيط النوني من القالب كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدد المراجع المشتركة ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| virtual void [Skip](./skip/)() | يتخطى أبناء العقدة الحالية. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## الأنواع المعرفية

| النوع المعرف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |

## انظر أيضًا

* الفئة [IDisposable](../../system/idisposable/)
* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)