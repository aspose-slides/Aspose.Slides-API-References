---
title: XmlTextReader
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل القارئ الذي يوفر وصولًا سريعًا غير مخزن ومباشر إلى بيانات XML.
type: docs
weight: 508
url: /ar/system.xml/xmltextreader/
---
## XmlTextReader فئة

يمثل قارئًا يوفر وصولًا سريعًا وغير مخبَّأ وإلى الأمام فقط إلى بيانات XML.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## الأساليب

| طريقة | الوصف |
| --- | --- |
| void [Close](./close/)() override | يغيّر [XmlReader::get_ReadState](../xmlreader/get_readstate/) إلى **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام URI المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام URI والإعدادات المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام URI والإعدادات ومعلومات السياق المطلوبة للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام التدفق المحدد مع الإعدادات الافتراضية. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام التدفق والإعدادات المحددة. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام التدفق المحدد وURI الأساسي والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام التدفق والإعدادات ومعلومات السياق المطلوبة للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد والإعدادات. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد والإعدادات وURI الأساسي. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام قارئ النص المحدد والإعدادات ومعلومات السياق للتحليل. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | ينشئ نسخة جديدة من [XmlReader](../xmlreader/) باستخدام قارئ XML المحدد والإعدادات. |
| void [Dispose](../xmlreader/dispose/)() override | يطلق جميع الموارد المستخدمة من قبل النسخة الحالية من فئة [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع على طريقة C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة على طريقة C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُ considered NaNانان متساوين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُ considered NaNانان متساوين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | يرجع عدد السمات في العقدة الحالية. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | يرجع URI الأساسي للعقدة الحالية. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | يرجع قيمة تشير إلى ما إذا كان [XmlTextReader](./) يطبق طرق قراءة المحتوى الثنائي. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | يرجع قيمة تشير إلى ما إذا كان [XmlTextReader](./) يطبق طريقة [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/). |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | يرجع قيمة تشير إلى ما إذا كان هذا القارئ يستطيع تحليل الكيانات وحلها. |
| **int32_t** [get_Depth](./get_depth/)() override | يرجع عمق العقدة الحالية في مستند XML. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | يرجع تعداد DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | يرجع ترميز المستند. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | يرجع قيمة تحدد كيفية تعامل القارئ مع الكيانات. |
| **bool** [get_EOF](./get_eof/)() override | يرجع قيمة تشير إلى ما إذا كان القارئ في نهاية التدفق. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | يرجع قيمة تشير إلى ما إذا كانت العقدة الحالية تحتوي على أي سمات. |
| **bool** [get_HasValue](./get_hasvalue/)() override | يرجع قيمة تشير إلى ما إذا كانت العقدة الحالية يمكن أن تحتوي على [XmlTextReader::get_Value](./get_value/) غير [String::Empty](../../system/string/empty/). |
| **bool** [get_IsDefault](./get_isdefault/)() override | يرجع قيمة تشير إلى ما إذا كانت العقدة الحالية سمة تم إنشاؤها من القيمة الافتراضية المعرفة في DTD أو المخطط. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | يرجع قيمة تشير إلى ما إذا كانت العقدة الحالية عنصرًا فارغًا (مثال: **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | يرجع رقم السطر الحالي. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | يرجع موضع السطر الحالي. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | يرجع الاسم المحلي للعقدة الحالية. |
| [String](../../system/string/) [get_Name](./get_name/)() override | يرجع الاسم المؤهل للعقدة الحالية. |
| **bool** [get_Namespaces](./get_namespaces/)() | يرجع قيمة تشير إلى ما إذا كان يجب دعم النطاقات. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | يرجع URI النطاق (كما هو معرف في مواصفة نطاقات W3C) للعقدة التي يقع عليها القارئ. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | يرجع [XmlNameTable](../xmlnametable/) المرتبط بهذا التنفيذ. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | يرجع نوع العقدة الحالية. |
| **bool** [get_Normalization](./get_normalization/)() | يرجع قيمة تشير إلى ما إذا كان يجب تطبيع المسافات البيضاء وقيم السمات. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | يرجع بادئة النطاق المرتبطة بالعقدة الحالية. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | يرجع قيمة تشير إلى ما إذا كان يجب السماح بمعالجة DTD. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | يرجع حرف علامة الاقتباس المستخدم لتغليف قيمة عقدة السمة. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | يرجع حالة القارئ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | يرجع معلومات المخطط التي تم تعيينها للعقدة الحالية نتيجة للتحقق من صحة المخطط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | يرجع كائن [XmlReaderSettings](../xmlreadersettings/) المستخدم لإنشاء نسخة [XmlReader](../xmlreader/) هذه. |
| [String](../../system/string/) [get_Value](./get_value/)() override | يرجع القيمة النصية للعقدة الحالية. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | يرجع نوع العقدة الحالية. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | يرجع قيمة تحدد كيفية معالجة المسافات البيضاء. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | يرجع نطاق **xml:lang** الحالي. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | يرجع نطاق **xml:space** الحالي. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | يرجع قيمة السمة ذات الاسم المحدد. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | يرجع قيمة السمة ذات الاسم المحلي والـ URI النطاق المحددين. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | يرجع قيمة السمة ذات الفهرس المحدد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | يرجع مجموعة تحتوي على جميع النطاقات الحالية في النطاق. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | يرجع المتبقي من XML المخزن مؤقتًا. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | يرجع قيمة تشير إلى ما إذا كانت الفئة يمكنها إرجاع معلومات السطر. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات الفهرس المحدد. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيمة [XmlReader::get_Name](../xmlreader/get_name/) المحددة. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | عند تجاوزها في فئة مشتقة، يحصل على قيمة السمة ذات القيم [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | يرجع قيمة تشير إلى ما إذا كان سلسلة الإدخال اسم XML صالح. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | يرجع قيمة تشير إلى ما إذا كانت سلسلة الإدخال رمز اسم XML صالح. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويختبر ما إذا كانت عقدة المحتوى الحالية علامة بدء أو علامة عنصر فارغ. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويختبر ما إذا كانت عقدة المحتوى الحالية علامة بدء أو عنصر فارغ وإذا كانت قيمة [XmlReader::get_Name](../xmlreader/get_name/) للعنصر المطابق للمعطى. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | ينادي [XmlReader::MoveToContent](../xmlreader/movetocontent/) ويختبر ما إذا كانت عقدة المحتوى الحالية علامة بدء أو عنصر فارغ وإذا كانت قيم [XmlReader::get_LocalName](../xmlreader/get_localname/) و[XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) للعنصر المطابق للسلاسل المعطاة. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | يحلّ صفة النطاق في نطاق العنصر الحالي. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | ينتقل إلى السمة ذات الاسم المحدد. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | ينتقل إلى السمة ذات الاسم المحلي والـ URI النطاق المحددين. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | ينتقل إلى السمة ذات الفهرس المحدد. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | يفحص ما إذا كانت العقدة الحالية عقدة محتوى (نص غير مساحة بيضاء، **CDATA**، **Element**، **EndElement**، **EntityReference** أو **EndEntity**). إذا لم تكن عقدة محتوى، يتخطى القارئ إلى عقدة المحتوى التالية أو نهاية الملف. يتجاوز العقد من الأنواع التالية: **ProcessingInstruction**، **DocumentType**، **Comment**، **Whitespace** أو **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | ينتقل إلى العنصر الذي يحتوي على عقدة السمة الحالية. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | ينتقل إلى السمة الأولى. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | ينتقل إلى السمة التالية. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| **bool** [Read](./read/)() override | يقرا العقدة التالية من التدفق. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | يفحص قيمة السمة إلى واحد أو أكثر من عقد **[Text](../../system.text/)**، **EntityReference** أو **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يفك ترميز Base64 ويُرجع البايتات الثنائية المفككة. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يفك ترميز **BinHex** ويُرجع البايتات الثنائية المفككة. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | يقرأ محتويات النص لعنصر إلى مخزن مؤقت من الأحرف. تم تصميم هذه الطريقة لقراءة تدفقات نصية كبيرة مضمّنة عن طريق استدعائها بشكل متتالي. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ المحتوى ككائن من النوع المحدد. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ المحتوى ويعيد بايتات الثنائية المفكوكة من **Base64**. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ المحتوى ويعيد بايتات الثنائية المفكوكة من **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | يقرأ محتوى النص في الموضع الحالي كـ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | يقرأ محتوى النص في الموضع الحالي ككائن [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | يقرأ محتوى النص في الموضع الحالي ككائن [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | يقرأ محتوى النص في الموضع الحالي ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | يقرأ محتوى النص في الموضع الحالي كعدد عشري نقطة عائمة بدقة مزدوجة. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | يقرأ محتوى النص في الموضع الحالي كعدد عشري نقطة عائمة بدقة مفردة. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | يقرأ محتوى النص في الموضع الحالي كعدد صحيح موقع 32-بت. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | يقرأ محتوى النص في الموضع الحالي كعدد صحيح موقع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | يقرأ محتوى النص في الموضع الحالي كـ [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | يقرأ محتوى النص في الموضع الحالي ككائن [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | يقرأ محتوى العنصر كنوع الطلب. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي المحدد ومسار مساحة الاسم يتطابقان مع العنصر الحالي، ثم يقرأ محتوى العنصر كنوع الطلب. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ العنصر ويحل شفرة المحتوى **Base64**. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | يقرأ العنصر ويحل شفرة المحتوى **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | يقرأ العنصر الحالي ويعيد المحتوى كعدد عشري نقطة عائمة بدقة مزدوجة. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كعدد عشري نقطة عائمة بدقة مزدوجة. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | يقرأ العنصر الحالي ويعيد المحتوى كعدد عشري نقطة عائمة بدقة مفردة. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كعدد عشري نقطة عائمة بدقة مفردة. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقع 32-بت. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقع 32-بت. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقع 64-بت. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كعدد صحيح موقع 64-بت. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | يقرأ العنصر الحالي ويعيد المحتوى كـ [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى كـ [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | يقرأ العنصر الحالي ويعيد المحتوى ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن الاسم المحلي ومسار مساحة الاسم المحددين يتطابقان مع العنصر الحالي، ثم يقرأ العنصر الحالي ويعيد المحتوى ككائن [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | يقرأ عنصرًا نصيًا فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | يتحقق من أن قيمة [XmlReader::get_Name](../xmlreader/get_name/) للعنصر المطابق تتطابق مع السلسلة المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن قيمتي [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) للعنصر المطابق تتطابق مع السلاسل المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | يتحقق من أن عقدة المحتوى الحالية هي علامة إغلاق ثم يتقدم بالقارئ إلى العقدة التالية. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | عند تجاوزها في فئة مشتقة، تقرأ جميع المحتويات بما في ذلك العلامات كسلسلة نصية. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | عند تجاوزها في فئة مشتقة، تقرأ المحتوى بما في ذلك العلامات التي تمثل هذه العقدة وجميع فروعها. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | يتحقق من أن العقدة الحالية عنصر ثم يتقدم بالقارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية عنصر بقيمة [XmlReader::get_Name](../xmlreader/get_name/) المعطاة ثم يتقدم بالقارئ إلى العقدة التالية. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من أن عقدة المحتوى الحالية عنصر بالقيم [XmlReader::get_LocalName](../xmlreader/get_localname/) و [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) المعطاة ثم يتقدم بالقارئ إلى العقدة التالية. |
| [String](../../system/string/) [ReadString](./readstring/)() override | يقرأ محتويات عنصر أو عقدة نصية كسلسلة نصية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | يعيد نسخة جديدة من [XmlReader](../xmlreader/) يمكن استخدامها لقراءة العقدة الحالية وجميع فروعها. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | يتقدم بـ [XmlReader](../xmlreader/) إلى العنصر اللاحق المتفرع بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | يتقدم بـ [XmlReader](../xmlreader/) إلى العنصر اللاحق المتفرع بالاسم المحلي ومسار مساحة الاسم المحددين. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | يقرأ حتى يتم العثور على عنصر بالاسم المحلي ومسار مساحة الاسم المحددين. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | يتقدم بـ [XmlReader](../xmlreader/) إلى العنصر اللاحق من نفس المستوى بالاسم المؤهل المحدد. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | يتقدم بـ [XmlReader](../xmlreader/) إلى العنصر اللاحق من نفس المستوى بالاسم المحلي ومسار مساحة الاسم المحددين. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | يقرأ تدفقات نصية كبيرة مضمّنة في مستند XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| void [ResetState](./resetstate/)() | يعيد ضبط حالة القارئ إلى [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | يحَلّ إشارة الكيان لعقد **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | يضبط تعداد DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | يضبط قيمة تحدد كيفية تعامل القارئ مع الكيانات. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب دعم مساحات الأسماء. |
| void [set_Normalization](./set_normalization/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب تطبيع المسافات البيضاء وقيم السمات. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب السماح بمعالجة DTD. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | يضبط قيمة تحدد كيفية معالجة المسافات البيضاء. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | يضبط الـ [XmlResolver](../xmlresolver/) المستخدم لحل مراجع DTD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلًا منه. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلًا منه. |
| void [Skip](./skip/)() override | يتخطى أبناء العقدة الحالية. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء القفل الخاص بعبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلًا منه. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلًا منه. |
| [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ نسخة جديدة من الفئة [XmlTextReader](./) باستخدام الدفق المحدد. |
| [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ينشئ نسخة جديدة من الفئة [XmlTextReader](./) باستخدام عنوان URL والدفق المحدد. |
| [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | ينشئ نسخة جديدة من الفئة [XmlTextReader](./) باستخدام الدفق المحدد و[XmlNameTable](../xmlnametable/). |
| [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | ينشئ نسخة جديدة من الفئة [XmlTextReader](./) باستخدام عنوان URL والدفق و[XmlNameTable](../xmlnametable/) المحددين. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام TextReader المحدد. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام URL و TextReader المحددين. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام TextReader و[XmlNameTable](../xmlnametable/) المحددين. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام URL و TextReader و[XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام stream و XmlNodeType و[XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام string و XmlNodeType و[XmlParserContext](../xmlparsercontext/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام الملف المحدد. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | يُنشئ مثيلاً جديدًا من الفئة [XmlTextReader](./) باستخدام الملف و[XmlNameTable](../xmlnametable/). |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## أنواع التعريف

| نوع التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |
## ملاحظات



يوصى باستخدام الفئة [XmlReader](../xmlreader/) بدلاً من ذلك. 

الكائنات من هذه الفئة يجب تخصيصها فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء مثيلات من هذا النوع على المكدس أو باستخدام المشغّل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو فشل في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. 

## انظر أيضًا

* الفئة [XmlReader](../xmlreader/)
* الفئة [IXmlLineInfo](../ixmllineinfo/)
* الفئة [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)