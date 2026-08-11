---
title: XmlNodeReader
second_title: مرجع واجهة برمجة التطبيقات لـ Aspose.Slides للـ C++
description: يمثل قارئًا يوفّر وصولًا سريعًا غير مخزّن إلى البيانات XML في XmlNode بطريقة تقدمية فقط.
type: docs
weight: 365
url: /ar/system.xml/xmlnodereader/
---
## XmlNodeReader فئة

يمثل قارئًا يوفر وصولًا سريعًا غير مؤقت إلى بيانات XML في [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Close](./close/)() override | يقوم بتغيير [XmlNodeReader::get_ReadState](./get_readstate/) إلى [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) مع عنوان URI محدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام عنوان URI والإعدادات المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام عنوان URI والإعدادات ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام الدفق المحدد مع الإعدادات الافتراضية. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) مع الدفق والإعدادات المحددين. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام الدفق، عنوان URI الأساسي، والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام الدفق، الإعدادات، ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد، الإعدادات، وعنوان URI الأساسي. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد، الإعدادات، ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | ينشئ كائنًا جديدًا من نوع [XmlReader](../xmlreader/) باستخدام قارئ XML المحدد والإعدادات. |
| void [Dispose](../xmlreader/dispose/)() override | يطلق جميع الموارد المستخدمة بواسطة الكائن الحالي من فئة [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | يعيد عدد السمات على العقدة الحالية. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | يعيد عنوان URI الأساسي للعقدة الحالية. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | يعيد قيمة تشير إلى ما إذا كان [XmlNodeReader](./) يدعم طرق قراءة المحتوى الثنائي. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | يعيد قيمة تشير إلى ما إذا كان [XmlReader](../xmlreader/) يدعم طريقة [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | يعيد قيمة تشير إلى ما إذا كان هذا القارئ قادرًا على تحليل الكيانات وحلها. |
| **int32_t** [get_Depth](./get_depth/)() override | يعيد عمق العقدة الحالية في مستند XML. |
| **bool** [get_EOF](./get_eof/)() override | يعيد قيمة تشير إلى ما إذا كان القارئ في نهاية الدفق. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية تحتوي على أي سمات. |
| **bool** [get_HasValue](./get_hasvalue/)() override | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية يمكن أن تحتوي على قيمة [XmlNodeReader::get_Value](./get_value/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية سمة تم إنشاؤها من القيمة الافتراضية المعرفة في تعريف نوع المستند (DTD) أو المخطط. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية عنصرًا فارغًا (على سبيل المثال، **<MyElement/>**). |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | يعيد الاسم المحلي للعقدة الحالية. |
| [String](../../system/string/) [get_Name](./get_name/)() override | يعيد الاسم المؤهل للعقدة الحالية. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | يعيد URI مساحة الاسم (كما هو معرف في مواصفة مساحة الاسم الخاصة بـ W3C) للعقدة التي يقع عليها القارئ. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | يعيد [XmlNameTable](../xmlnametable/) المرتبط بهذا التنفيذ. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | يعيد نوع العقدة الحالية. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | يعيد بادئة مساحة الاسم المرتبطة بالعقدة الحالية. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | عند تجاوزها في فئة مشتقة، تحصل على حرف علامات الاقتباس المستخدم لإحاطة قيمة عقدة السمة. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | يعيد حالة القارئ. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | يعيد معلومات المخطط التي تم تعيينها للعقدة الحالية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | يعيد الكائن [XmlReaderSettings](../xmlreadersettings/) المستخدم لإنشاء هذا الكائن من نوع [XmlReader](../xmlreader/). |
| [String](../../system/string/) [get_Value](./get_value/)() override | يعيد القيمة النصية للعقدة الحالية. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | يعيد النوع للعقدة الحالية. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | يعيد نطاق **xml:lang** الحالي. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | يعيد نطاق **xml:space** الحالي. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | يعيد قيمة السمة بالاسم المحدد. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | يعيد قيمة السمة بالاسم المحلي المحدد وURI مساحة الاسم. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | يعيد قيمة السمة ذات الفهرس المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح التجزئة للكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات الفهرس المحدد. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة بالقيمة [XmlReader::get_Name](../xmlreader/get_name/) المحددة. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة بالقيمتين [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) المحددتين. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق ما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بواسطة targetType. تناظر لمعامل 'is' في C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | يعيد قيمة تشير إلى ما إذا كان معامل السلسلة اسم XML صالح. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | يعيد قيمة تشير إلى ما إذا كان معامل السلسلة رمز اسم XML صالح أو لا. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويفحص ما إذا كانت عقدة المحتوى الحالية هي علامة بداية أو علامة عنصر فارغ. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويفحص ما إذا كانت عقدة المحتوى الحالية هي علامة بداية أو عنصر فارغ وما إذا كانت قيمة [XmlReader::get_Name](../xmlreader/get_name/) للعنصر المُعثر يطابق الوسيط المُعطى. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويفحص ما إذا كانت عقدة المحتوى الحالية هي علامة بداية أو عنصر فارغ وما إذا كانت قيمتي [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) للعنصر المُعثر تطابق السلاسل المعطاة. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | يحلّ صفة مساحة الاسم في نطاق العنصر الحالي. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | ينتقل إلى السمة بالاسم المحدد. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | ينتقل إلى السمة بالاسم المحلي وURI مساحة الاسم المحددين. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | ينتقل إلى السمة ذات الفهرس المحدد. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | يتحقق مما إذا كانت العقدة الحالية عقدة محتوى (نص غير مسافة بيضاء، **CDATA**، **Element**، **EndElement**، **EntityReference** أو **EndEntity**). إذا لم تكن العقدة عقدة محتوى، يتخطى القارئ إلى عقدة المحتوى التالية أو إلى نهاية الملف. يتخطى العقد من الأنواع التالية: **ProcessingInstruction**، **DocumentType**، **Comment**، **Whitespace** أو **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | ينتقل إلى العنصر الذي يحتوي على عقدة السمة الحالية. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | ينتقل إلى السمة الأولى. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | ينتقل إلى السمة التالية. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | منشئ النسخة. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| **bool** [Read](./read/)() override | يقرا العقدة التالية من الدفق. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | يقوم بتحليل قيمة السمة إلى واحد أو أكثر من عقد **[Text](../../system.text/)** أو **EntityReference** أو **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ المحتوى ككائن من النوع المحدد. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ المحتوى ويعيد بايتات الثنائي المُفكّك من Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ المحتوى ويعيد بايتات الثنائي المُفكّك من BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | يقرأ النص الموجود في الموضع الحالي كـ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | يقرأ النص الموجود في الموضع الحالي ككائن [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | يقرأ النص الموجود في الموضع الحالي ككائن [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | يقرأ النص الموجود في الموضع الحالي ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | يقرأ النص الموجود في الموضع الحالي كعدد عائم بدقة مزدوجة. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | يقرأ النص الموجود في الموضع الحالي كعدد عائم بدقة أحادية. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | يقرأ النص الموجود في الموضع الحالي كعدد صحيح مُوقع 32-بت. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | يقرأ النص الموجود في الموضع الحالي كعدد صحيح مُوقع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | يقرأ النص الموجود في الموضع الحالي كـ [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | يقرأ محتوى النص في الموضع الحالي ككائن [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ محتوى العنصر كنوع الطلب. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ محتوى العنصر كنوع الطلب. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ العنصر ويُفكّ شفرة محتوى Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ العنصر ويُفكّ شفرة محتوى BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | يقرأ العنصر الحالي ويُعيد المحتويات ككائن [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات ككائن [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | يقرأ العنصر الحالي ويُعيد المحتويات ككائن [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات ككائن [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | يقرأ العنصر الحالي ويُعيد المحتويات ككائن [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | يقرأ العنصر الحالي ويُعيد المحتويات كرقم عائم ذو دقة مزدوجة. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات كرقم عائم ذو دقة مزدوجة. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | يقرأ العنصر الحالي ويُعيد المحتويات كرقم عائم ذو دقة أحادية. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات كرقم عائم ذو دقة أحادية. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | يقرأ العنصر الحالي ويُعيد المحتويات كعدد صحيح موقع 32-بت. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات كعدد صحيح موقع 32-بت. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | يقرأ العنصر الحالي ويُعيد المحتويات كعدد صحيح موقع 64-بت. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات كعدد صحيح موقع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | يقرأ العنصر الحالي ويُعيد المحتويات كـ[Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات كـ[Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | يقرأ العنصر الحالي ويُعيد المحتويات ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار URI للمساحة الاسمية يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويُعيد المحتويات ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | يقرأ عنصرًا يحتوي على نص فقط. ومع ذلك، يُنصَح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | يتحقق من أن قيمة [XmlReader::get_Name](../xmlreader/get_name/) للعنصر المكتشف تطابق السلسلة المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصَح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن قيمتي [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) للعنصر المكتشف تطابقان السلاسل المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصَح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | يتحقق من أن عقدة المحتوى الحالية هي علامة إغلاق ويتقدّم القارئ إلى العقدة التالية. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | عند إعادة تعريفها في فئة مشتقة، تقرأ كل المحتوى، بما في ذلك العلامات، كسلسلة نصية. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | عند إعادة تعريفها في فئة مشتقة، تقرأ المحتوى، بما في ذلك العلامات، التي تمثّل هذه العقدة وجميع أطفالها. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | يتحقق من أن العقدة الحالية عنصر ويتقدّم القارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية عنصر بالقيمة [XmlReader::get_Name](../xmlreader/get_name/) المعطاة ويتقدّم القارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية عنصر بالقيمتين [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) المعطاة ويتقدّم القارئ إلى العقدة التالية. |
| [String](../../system/string/) [ReadString](./readstring/)() override | يقرأ محتويات عنصر أو عقدة نصية كسلسلة نصية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | يعيد نسخة جديدة من [XmlReader](../xmlreader/) يمكن استخدامها لقراءة العقدة الحالية وجميع الفروع التابعة لها. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | يتقدّم الـ[XmlReader](../xmlreader/) إلى العنصر الفرعي التالي بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | يتقدّم الـ[XmlReader](../xmlreader/) إلى العنصر الفرعي التالي بالاسم المحلي ومسار URI للمساحة الاسمية المحددين. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المحلي ومسار URI للمساحة الاسمية المحددين. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | يتقدّم الـ[XmlReader](../xmlreader/) إلى العنصر الشقيق التالي بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | يتقدّم الـ[XmlReader](../xmlreader/) إلى العنصر الشقيق التالي بالاسم المحلي ومسار URI للمساحة الاسمية المحددين. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يقرأ تدفقات نصية كبيرة مدمجة في مستند XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ[Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ[Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| void [ResolveEntity](./resolveentity/)() override | يحلّ مرجع الكيان لعقد **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويُعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [Skip](./skip/)() override | يتخطى أطفال العقدة الحالية. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُطبق إلغاء قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | ينشئ نسخة من فئة [XmlNodeReader](./) باستخدام [XmlNode](../xmlnode/) المحدد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع هياكل البيانات الداخلية. |
## التعريفات

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |
## ملاحظات

يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء نسخ من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل أو أعطال تأكيدية. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. 

## انظر أيضًا

* الفئة [XmlReader](../xmlreader/)
* الفئة [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* الفضاء الاسمي [System::Xml](../)
* المكتبة [Aspose.Slides](../../)