---
title: XmlValidatingReader
second_title: Aspose.Slides للغة C++ - مرجع API
description: يمثل القارئ الذي يوفر التحقق من تعريف نوع المستند (DTD) ومخطط XML-Data Reduced (XDR) ولغة تعريف مخطط XML (XSD).
type: docs
weight: 547
url: /ar/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader فئة

يمثّل قارئًا يقدم تعريف نوع المستند (DTD)، مخطط XML-Data Reduced (XDR)، وتعريف لغة XML [Schema](../../system.xml.schema/) (XSD) للتحقق.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## الطرق

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | يغيّر [XmlReader::get_ReadState](../xmlreader/get_readstate/) إلى Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) بالمعرّف المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام المعرّف المحدد والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام المعرّف المحدد، الإعدادات، ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام الدفق المحدد مع الإعدادات الافتراضية. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام الدفق المحدد والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام الدفق المحدد، المعرّف الأساسي، والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام الدفق المحدد، الإعدادات، ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد، الإعدادات، والمرّف الأساسي. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد، الإعدادات، ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | ينشئ كائنًا جديدًا من النوع [XmlReader](../xmlreader/) باستخدام قارئ XML المحدد والإعدادات. |
| void [Dispose](../xmlreader/dispose/)() override | يحرّر جميع الموارد المستخدمة من قبل الكائن الحالي من الفئة [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | يعيد عدد السمات في العقدة الحالية. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | يعيد المعرّف الأساسي للعقدة الحالية. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | يعيد قيمة تشير إلى ما إذا كان [XmlValidatingReader](./) يُنفّذ طرق قراءة المحتوى الثنائي. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | يعيد قيمة تشير إلى ما إذا كان [XmlReader](../xmlreader/) يُنفّذ طريقة [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | يعيد قيمة تشير إلى ما إذا كان هذا القارئ يستطيع تحليل الكيانات وحلّها. |
| **int32_t** [get_Depth](./get_depth/)() override | يعيد عمق العقدة الحالية في مستند XML. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | يعيد سمة الترميز للوثيقة. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | يعيد قيمة تحدد كيفية تعامل القارئ مع الكيانات. |
| **bool** [get_EOF](./get_eof/)() override | يعيد قيمة تشير إلى ما إذا كان القارئ في موضع نهاية الدفق. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية لديها أي سمات. |
| **bool** [get_HasValue](./get_hasvalue/)() override | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية يمكن أن تحتوي على [XmlValidatingReader::get_Value](./get_value/) مختلف عن [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية سمة تم إنشاؤها من القيمة الافتراضية المعرفة في تعريف نوع المستند (DTD) أو المخطط. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | يعيد قيمة تشير إلى ما إذا كانت العقدة الحالية عنصرًا فارغًا (مثال: **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | يعيد رقم السطر الحالي. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | يعيد موضع السطر الحالي. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | يعيد الاسم المحلي للعقدة الحالية. |
| [String](../../system/string/) [get_Name](./get_name/)() override | يعيد الاسم المُؤهل للعقدة الحالية. |
| **bool** [get_Namespaces](./get_namespaces/)() | يعيد قيمة تشير إلى ما إذا كان يجب تمكين دعم النطاق الاسمي. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | يعيد معرف المورد العالمي (URI) للنطاق الاسمي (كما هو معرف في اتحاد الويب العالمية [Web](../../system.web/) (W3C) لمواصفة النطاق الاسمي) للعقدة التي يقع عليها القارئ. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | يعيد [XmlNameTable](../xmlnametable/) المرتبط بهذا التطبيق. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | يعيد نوع العقدة الحالية. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | يعيد بادئة النطاق الاسمي المرتبط بالعقدة الحالية. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | يعيد حرف علامة الاقتباس المستخدم لتغليف قيمة عقدة السمة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | يعيد [XmlReader](../xmlreader/) المستخدم لإنشاء هذا [XmlValidatingReader](./). |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | يعيد حالة القارئ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | يعيد معلومات المخطط التي تم تعيينها للعقدة الحالية نتيجة للتحقق من صحة المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | يعيد XmlSchemaCollection لاستخدامه في التحقق. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | يعيد كائن نوع مخطّط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | يعيد كائن [XmlReaderSettings](../xmlreadersettings/) المستخدم لإنشاء هذا المثيل من [XmlReader](../xmlreader/). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | يعيد قيمة تشير إلى نوع التحقق المطلوب إجراؤه. |
| [String](../../system/string/) [get_Value](./get_value/)() override | يعيد القيمة النصية للعقدة الحالية. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | يعيد النوع للعقدة الحالية. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | يعيد نطاق **xml:lang** الحالي. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | يعيد نطاق **xml:space** الحالي. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | يعيد قيمة السمة بالاسم المحدد. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | يعيد قيمة السمة بالاسم المحلي المحدد ومعرف المورد العالمي (URI) للنطاق الاسمي. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | يعيد قيمة السمة بالمؤشر المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثلة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن من تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثلة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | يعيد قيمة تشير إلى ما إذا كانت الفئة يمكنها إرجاع معلومات السطر. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة بالمؤشر المحدد. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة بالقيمة المحددة [XmlReader::get_Name](../xmlreader/get_name/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة بالقيم المحددة [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. مماثلة لمشغل C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | يعيد قيمة تشير إلى ما إذا كان معامل السلسلة اسم XML صالح. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | يعيد قيمة تشير إلى ما إذا كان معامل السلسلة رمز اسم XML صالح. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويختبر ما إذا كانت عقدة المحتوى الحالية علامة بدء أو علامة عنصر فارغ. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويختبر ما إذا كانت عقدة المحتوى الحالية علامة بدء أو علامة عنصر فارغ وإذا كانت قيمة [XmlReader::get_Name](../xmlreader/get_name/) للعنصر الموجود مطابقة للمعامل المحدد. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويختبر ما إذا كانت عقدة المحتوى الحالية علامة بدء أو عنصر فارغ وإذا كانت قيم [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) للعنصر الموجود تطابق السلاسل المعطاة. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | يحلّ بادئة النطاق الاسمي في نطاق العنصر الحالي. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثلة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن من استنساخ الأنواع المخصصة. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | ينتقل إلى السمة بالاسم المحدد. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | ينتقل إلى السمة بالاسم المحلي المحدد ومعرف المورد العالمي (URI) للنطاق الاسمي. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | ينتقل إلى السمة بالمؤشر المحدد. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | يفحص ما إذا كانت العقدة الحالية عقدة محتوى (نص غير فراغ، **CDATA**، **Element**، **EndElement**، **EntityReference** أو **EndEntity**). إذا لم تكن العقدة عقدة محتوى، يتجاوز القارئ إلى عقدة المحتوى التالية أو إلى نهاية الملف. يتخطى العقد من الأنواع التالية: **ProcessingInstruction**، **DocumentType**، **Comment**، **Whitespace** أو **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | ينتقل إلى العنصر الذي يحتوي على عقدة السمة الحالية. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | ينتقل إلى أول سمة. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | ينتقل إلى السمة التالية. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيّء كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | معامل إسناد. لا ينسخ شيئًا فعليًا، فقط يهيّء كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| **bool** [Read](./read/)() override | يقرأ العقدة التالية من الدفق. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | يُحلّل قيمة السمة إلى واحدة أو أكثر من العقد **[Text](../../system.text/)**، **EntityReference** أو **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ المحتوى ككائن من النوع المحدد. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ المحتوى ويعيد بايتات البيانات الثنائية المفكوكة من Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ المحتوى ويعيد بايتات البيانات الثنائية المفكوكة من BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | يقرأ محتوى النص في الموضع الحالي كـ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | يقرأ محتوى النص في الموضع الحالي ككائن [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | يقرأ محتوى النص في الموضع الحالي ككائن [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | يقرأ محتوى النص في الموضع الحالي ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | يقرأ محتوى النص في الموضع الحالي كعدد عائم بدقة مزدوجة. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | يقرأ محتوى النص في الموضع الحالي كعدد عائم بدقة مفردة. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | يقرأ محتوى النص في الموضع الحالي كعدد صحيح موقّع 32-بت. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | يقرأ محتوى النص في الموضع الحالي كعدد صحيح موقّع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | يقرأ محتوى النص في الموضع الحالي كـ [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | يقرأ محتوى النص في الموضع الحالي ككائن [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ محتوى العنصر بالنوع المطلوب. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ محتوى العنصر بالنوع المطلوب. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ العنصر ويقوم بفك ترميز محتوى Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ العنصر ويقوم بفك ترميز محتوى BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | يقرأ العنصر الحالي ويعيد المحتويات ككائن [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات ككائن [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | يقرأ العنصر الحالي ويعيد المحتويات ككائن [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات ككائن [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | يقرأ العنصر الحالي ويعيد المحتويات ككائن [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | يقرأ العنصر الحالي ويعيد المحتويات كعدد عائم بدقة مزدوجة. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات كعدد عائم بدقة مزدوجة. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | يقرأ العنصر الحالي ويعيد المحتويات كعدد عائم بدقة مفردة. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات كعدد عائم بدقة مفردة. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | يقرأ العنصر الحالي ويعيد المحتويات كعدد صحيح موقّع 32-بت. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات كعدد صحيح موقّع 32-بت. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | يقرأ العنصر الحالي ويعيد المحتويات كعدد صحيح موقّع 64-بت. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات كعدد صحيح موقّع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | يقرأ العنصر الحالي ويعيد المحتويات كـ [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات كـ [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | يقرأ العنصر الحالي ويعيد المحتويات ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الأسماء يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتويات ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | يقرأ عنصرًا نصيًا فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أبسط للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | يتحقق من أن قيمة [XmlReader::get_Name](../xmlreader/get_name/) للعنصر الذي تم العثور عليه تتطابق مع السلسلة المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أبسط للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن قيمتي [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) للعنصر الذي تم العثور عليه تتطابقان مع السلاسل المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أبسط للتعامل مع هذه العملية. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | يتحقق من أن عقدة المحتوى الحالية هي علامة إغلاق ويتقدم القارئ إلى العقدة التالية. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | عند تجاوزها في فئة مشتقة، تقرأ كل المحتوى، بما في ذلك العلامات، كسلسلة نصية. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | عند تجاوزها في فئة مشتقة، تقرأ المحتوى، بما في ذلك العلامات، التي تمثل هذه العقدة وجميع أطفالها. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | يتحقق من أن العقدة الحالية هي عنصر ويتقدم القارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية هي عنصر مع القيمة [XmlReader::get_Name](../xmlreader/get_name/) المعطاة ويتقدم القارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية هي عنصر مع القيمتين [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) المعطاة ويتقدم القارئ إلى العقدة التالية. |
| [String](../../system/string/) [ReadString](./readstring/)() override | يقرأ محتويات عنصر أو عقدة نصية كسلسلة نصية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | يعيد نسخة جديدة من [XmlReader](../xmlreader/) يمكن استخدامها لقراءة العقدة الحالية وجميع الفروع التابعة لها. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | يتقدم [XmlReader](../xmlreader/) إلى العنصر الفرعي التالي بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | يتقدم [XmlReader](../xmlreader/) إلى العنصر الفرعي التالي بالاسم المحلي ومسار مساحة الأسماء المحددين. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المحلي ومسار مساحة الأسماء المحددين. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | يتقدم [XmlReader](../xmlreader/) إلى العنصر الشقيق التالي بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | يتقدم [XmlReader](../xmlreader/) إلى العنصر الشقيق التالي بالاسم المحلي ومسار مساحة الأسماء المحددين. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | يعيد نوع وقت التشغيل للنوع المحدد من تعريف لغة XML [Schema](../../system.xml.schema/) (XSD). |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يقرأ تدفقات نصية كبيرة مدمجة في مستند XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن الكائن القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [ResolveEntity](./resolveentity/)() override | يحل مرجع الكيان لعقد **EntityReference**. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | يضبط قيمة تحدد كيفية تعامل القارئ مع الكيانات. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان سيتم دعم مساحة الأسماء. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | يضبط قيمة تشير إلى نوع التحقق الذي يجب إجراؤه. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | يضبط [XmlResolver](../xmlresolver/) المستخدم لحل مراجع تعريف نوع المستند الخارجي (DTD) ومواقع المخطط. كما يستخدم [XmlResolver](../xmlresolver/) للتعامل مع أي عناصر استيراد أو تضمين تُوجد في مخططات لغة تعريف XML [Schema](../../system.xml.schema/) (XSD). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد مرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدد مرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | يتخطى أبناء العقدة الحالية. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | يضيف معالج حدث لتلقي معلومات حول تعريف نوع المستند (DTD)، مخطط XML-Data Reduced (XDR)، وأخطاء التحقق من مخطط لغة تعريف XML [Schema](../../system.xml.schema/) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | يزيل معالج حدث لتلقي معلومات حول تعريف نوع المستند (DTD)، مخطط XML-Data Reduced (XDR)، وأخطاء التحقق من مخطط لغة تعريف XML [Schema](../../system.xml.schema/) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | ينشئ نسخة جديدة من صنف [XmlValidatingReader](./) الذي يتحقق من صحة المحتوى المسترجع من [XmlReader](../xmlreader/) المعطى. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ نسخة جديدة من صنف [XmlValidatingReader](./) بالقيم المحددة. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ نسخة جديدة من صنف [XmlValidatingReader](./) بالقيم المحددة. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحذف جميع هياكل البيانات الداخلية. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذا الصنف. |
## ملاحظات

مهمل
:   هذه الفئة مهجورة. يُنصح باستخدام الفئة [XmlReaderSettings](../xmlreadersettings/) والطريقة [XmlReader::Create](../xmlreader/create/) لإنشاء قارئ XML يتحقق من صحة.
Objects of this **الفئة** should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this **الفئة** into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## انظر أيضًا

* الفئة [XmlReader](../xmlreader/)
* الفئة [IXmlLineInfo](../ixmllineinfo/)
* الفئة [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)