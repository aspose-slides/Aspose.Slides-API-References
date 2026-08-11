---
title: XmlDocument
second_title: مرجع API Aspose.Slides لـ C++
description: يمثل مستند XML. يمكنك استخدام هذه الفئة لتحميل، والتحقق من الصحة، وتحرير، وإضافة، وتحديد موقع XML في مستند.
type: docs
weight: 183
url: /ar/system.xml/xmldocument/
---
## XmlDocument فئة

يمثل مستند XML. يمكنك استخدام هذه الفئة لتحميل، والتحقق من صحة، وتحرير، وإضافة، وتحديد موضع XML في مستند.

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يضيف العقدة المحددة إلى نهاية قائمة العقد الفرعية لهذه العقدة. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | يحصل على المتكرر الذي يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المتكرر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) يُرجع نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | يحصل على المتكرر الذي يشير إلى العنصر الأول (إن وجد) في نسخة المجموعة المؤهلة كـ const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | يحصل على المتكرر الذي يشير إلى العنصر الأول المؤهل كـ const (إن وجد) في المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | يحصل على المتكرر الذي يشير إلى ما بعد العنصر الأخير المؤهل كـ const (إن وجد) في المجموعة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | ينشئ نسخة مكررة من هذه العقدة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | ينشئ نسخة مكررة من هذه العقدة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&) | ينشئ [XmlAttribute](../xmlattribute/) بالاسم المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ [XmlAttribute](../xmlattribute/) بالاسم المؤهل المحدد و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ [XmlAttribute](../xmlattribute/) بال[XmlNode::get_Prefix](../xmlnode/get_prefix/)، [XmlDocument::get_LocalName](./get_localname/)، و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlCDataSection](../xmlcdatasection/)\> [CreateCDataSection](./createcdatasection/)(const [String](../../system/string/)\&) | ينشئ [XmlCDataSection](../xmlcdatasection/) يحتوي على البيانات المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlComment](../xmlcomment/)\> [CreateComment](./createcomment/)(const [String](../../system/string/)\&) | ينشئ [XmlComment](../xmlcomment/) يحتوي على البيانات المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentFragment](../xmldocumentfragment/)\> [CreateDocumentFragment](./createdocumentfragment/)() | ينشئ [XmlDocumentFragment](../xmldocumentfragment/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [CreateDocumentType](./createdocumenttype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يرجع كائن [XmlDocumentType](../xmldocumenttype/) جديد. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&) | ينشئ عنصرًا بالاسم المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ [XmlElement](../xmlelement/) بالاسم المؤهل و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ عنصرًا بال[XmlNode::get_Prefix](../xmlnode/get_prefix/)، [XmlDocument::get_LocalName](./get_localname/)، و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlEntityReference](../xmlentityreference/)\> [CreateEntityReference](./createentityreference/)(const [String](../../system/string/)\&) | ينشئ [XmlEntityReference](../xmlentityreference/) بالاسم المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | ينشئ كائن XPathNavigator جديد لتصفح هذا المستند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ [XmlNode](../xmlnode/) بال{{XmlNodeType}}، [XmlNode::get_Prefix](../xmlnode/get_prefix/)، [XmlDocument::get_Name](./get_name/)، و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ [XmlNode](../xmlnode/) بنوع العقدة المحدد، [XmlDocument::get_Name](./get_name/)، و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ [XmlNode](../xmlnode/) بال{{XmlNodeType}}، [XmlDocument::get_Name](./get_name/)، و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlProcessingInstruction](../xmlprocessinginstruction/)\> [CreateProcessingInstruction](./createprocessinginstruction/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ [XmlProcessingInstruction](../xmlprocessinginstruction/) بالاسم والبيانات المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlSignificantWhitespace](../xmlsignificantwhitespace/)\> [CreateSignificantWhitespace](./createsignificantwhitespace/)(const [String](../../system/string/)\&) | ينشئ عقدة [XmlSignificantWhitespace](../xmlsignificantwhitespace/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlText](../xmltext/)\> [CreateTextNode](./createtextnode/)(const [String](../../system/string/)\&) | ينشئ [XmlText](../xmltext/) بالنص المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWhitespace](../xmlwhitespace/)\> [CreateWhitespace](./createwhitespace/)(const [String](../../system/string/)\&) | ينشئ عقدة [XmlWhitespace](../xmlwhitespace/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDeclaration](../xmldeclaration/)\> [CreateXmlDeclaration](./createxmldeclaration/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ عقدة [XmlDeclaration](../xmldeclaration/) بالقيم المحددة. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | يحصل على المتكرر الذي يشير إلى ما بعد العنصر الأخير (إن وجد) في المجموعة. لا يمكن استخدام هذا المتكرر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) يُرجع نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | يحصل على المتكرر الذي يشير إلى ما بعد العنصر الأخير (إن وجد) في نسخة المجموعة المؤهلة كـ const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام إحصائيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN متساوية حتى وإن وفقاً لـ IEC 60559:1989 NaN لا تساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN متساوية حتى وإن وفقاً لـ IEC 60559:1989 NaN لا تساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | يُرجع [XmlAttributeCollection](../xmlattributecollection/) يحتوي على خصائص هذه العقدة. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | يُرجع URI الأساسي للعقدة الحالية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | يُرجع جميع العقد الفرعية للعقدة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [get_DocumentElement](./get_documentelement/)() | يُرجع الجذر [XmlElement](../xmlelement/) للمستند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [get_DocumentType](./get_documenttype/)() | يُرجع العقدة التي تحتوي على إعلان DOCTYPE. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | يُرجع أول عقدة فرعية للعقدة. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | يُرجع قيمة تشير ما إذا كانت هذه العقدة تحتوي على أي عقد فرعية. |
| [SharedPtr](../../system/sharedptr/)\<[XmlImplementation](../xmlimplementation/)\> [get_Implementation](./get_implementation/)() | يُرجع كائن [XmlImplementation](../xmlimplementation/) للمستند الحالي. |
| virtual [String](../../system/string/) [get_InnerText](../xmlnode/get_innertext/)() | يُرجع القيم المتسلسلة للعقدة وجميع العقد الفرعية لها. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | يُرجع الترميز الذي يمثل أطفال العقدة الحالية. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | يُرجع قيمة تشير ما إذا كانت العقدة الحالية للقراءة فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | يُرجع آخر عقدة فرعية للعقدة. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | يُرجع الاسم المحلي للعقدة. |
| [String](../../system/string/) [get_Name](./get_name/)() override | يُرجع الاسم المؤهل للعقدة. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | يُرجع URI مساحة الاسم لهذه العقدة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | يُرجع [XmlNameTable](../xmlnametable/) المرتبط بهذا التنفيذ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | يُرجع العقدة التي تلي هذه العقدة مباشرة. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | يُرجع نوع العقدة الحالية. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | يُرجع الترميز الذي يحتوي على هذه العقدة وجميع عقدها الفرعية. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](./)\> [get_OwnerDocument](./get_ownerdocument/)() override | يُرجع [XmlDocument](./) التي تنتمي إليها العقدة الحالية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | يُرجع أب هذه العقدة (للعقد التي يمكن أن تكون لها أبواب). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | يُرجع بادئة مساحة الاسم لهذه العقدة. |
| **bool** [get_PreserveWhitespace](./get_preservewhitespace/)() | يُرجع قيمة تشير ما إذا كان يجب الحفاظ على المسافات البيضاء في محتوى العنصر. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | يُرجع العقدة التي سابقة مباشرةً هذه العقدة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | يُرجع عقدة النص التي سابقة مباشرةً هذه العقدة. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | يُرجع Post-Schema-Validation-Infoset (PSVI) للعقدة. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | يُرجع كائن XmlSchemaSet المرتبط بهذا [XmlDocument](./). |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | يُرجع قيمة العقدة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعية المرتبطة بالكائن. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [GetElementById](./getelementbyid/)([String](../../system/string/)) | يُرجع [XmlElement](../xmlelement/) بالمعرف المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | يُرجع [XmlNodeList](../xmlnodelist/) يحتوي على قائمة بجميع العناصر الناحية التي تطابق الاسم المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | يُرجع [XmlNodeList](../xmlnodelist/) يحتوي على قائمة بجميع العناصر الناحية التي تطابق [XmlDocument::get_LocalName](./get_localname/) و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) المحددين. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | يُرجع عددًا (enumerator) يتجول عبر العقد الفرعية في العقدة الحالية. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | يبحث عن أقرب إعلان **xmlns** للبادئة المحددة وهو ضمن نطاق العقدة الحالية ويعيد URI مساحة الاسم في الإعلان. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | يبحث عن أقرب إعلان **xmlns** للـ URI مساحة الاسم المحددة وهو ضمن نطاق العقدة الحالية ويعيد البادئة المحددة في ذلك الإعلان. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | يُرجع العنصر الفرعي الأول بال[XmlNode::get_Name](../xmlnode/get_name/) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | يُرجع العنصر الفرعي الأول بال[XmlNode::get_LocalName](../xmlnode/get_localname/) و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ImportNode](./importnode/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, **bool**) | يستورد عقدة من مستند آخر إلى المستند الحالي. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يُدرج العقدة المحددة مباشرةً بعد عقدة الإشارة المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يُدرج العقدة المحددة مباشرةً قبل عقدة الإشارة المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل 'is' في C#. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة مُراكم على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كان جميع عناصر التسلسل تحقق شرطًا. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجود أو يحقق شرطًا. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | يحسب المتوسط لتسلسل القيم العددية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب المتوسط لتسلسل القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | يحول العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | يجمع سلسلتين متتالية. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | يُرجع عدد العناصر في التسلسل (محسوب عن طريق العد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يُرجع عدد العناصر في التسلسل التي تحقق الشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | يُرجع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | يُرجع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | يُرجع العنصر الأول في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يُرجع العنصر الأول في التسلسل الذي يحقق الشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | يُرجع العنصر الأول في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | تعيد العنصر الأول في المتسلسلة الذي يحقق شرطًا أو قيمة افتراضية إذا لم يُعثر على عنصر مطابقة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | تجميع عناصر المتسلسلة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | تجميع عناصر المتسلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | تعيد العنصر الأخير في المتسلسلة. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | تعيد العنصر الأخير في المتسلسلة، أو قيمة افتراضية إذا كانت المتسلسلة فارغة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | تستدعي دالة تحويل على كل عنصر من متسلسلة عامة وتعيد أعلى قيمة ناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | تستدعي دالة تحويل على كل عنصر من متسلسلة عامة وتعيد أدنى قيمة ناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | تصفية عناصر المتسلسلة بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر المتسلسلة تصاعديًا حسب قيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر المتسلسلة تنازليًا حسب قيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في المتسلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحول عناصر المتسلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحول كل عنصر من المتسلسلة إلى شكل جديد بدمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | يُسقِط كل عنصر من المتسلسلة ويجمع المتسلسلات الناتجة في متسلسلة واحدة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتابعة من بداية المتسلسلة ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتتابعة من بداية المتسلسلة. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | ينشئ مصفوفة من المتسلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | ينشئ List<T> من المتسلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | يرشح متسلسلة بناءً على العبارة المحددة. |
| virtual void [Load](./load/)([String](../../system/string/)) | يقوم بتحميل مستند XML من العنوان URL المحدد. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | يقوم بتحميل مستند XML من الدفق المحدد. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | يقوم بتحميل مستند XML من القارئ النصي المحدد. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | يقوم بتحميل مستند XML من الـ [XmlReader](../xmlreader/) المحدد. |
| virtual void [LoadXml](./loadxml/)([String](../../system/string/)) | يقوم بتحميل مستند XML من السلسلة المحددة. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل جملة C# lock() . استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مقابل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| virtual void [Normalize](../xmlnode/normalize/)() | يضع جميع عقد [XmlText](../xmltext/) في العمق الكامل للشجرة الفرعية تحت هذا [XmlNode](../xmlnode/) في شكل "عادي" حيث يفصل فقط العلامات (أي الوسوم، التعليقات، تعليمات المعالجة، أقسام CDATA، وإشارات الكيان) بين عقد [XmlText](../xmltext/)، أي لا توجد عقد [XmlText](../xmltext/) متجاورة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ فرعية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يضيف العقدة المحددة إلى بداية قائمة العقد الفرعية لهذه العقدة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReadNode](./readnode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | ينشئ كائن [XmlNode](../xmlnode/) بناءً على المعلومات في [XmlReader](../xmlreader/). يجب أن يكون القارئ موجهًا إلى عقدة أو سمة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعًا لكائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | يزيل جميع العقد الفرعية و/أو السمات للعقدة الحالية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يزيل العقدة الفرعية المحددة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يستبدل العقدة الفرعية **oldChild** بالعقدة **newChild**. |
| virtual void [Save](./save/)([String](../../system/string/)) | يحفظ مستند XML إلى الملف المحدد. إذا كان الملف المحدد موجودًا، تقوم هذه الطريقة بالكتابة فوقه. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | يحفظ مستند XML إلى الدفق المحدد. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>) | يحفظ مستند XML إلى الـ TextWriter المحدد. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>) | يحفظ مستند XML إلى الـ [XmlWriter](../xmlwriter/) المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | يختار قائمة من العقد التي تطابق تعبير [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | يختار قائمة من العقد التي تطابق تعبير [XPath](../../system.xml.xpath/). يتم حل أي سابقة موجودة في تعبير [XPath](../../system.xml.xpath/) باستخدام [XmlNamespaceManager](../xmlnamespacemanager/) الموفّرة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | يختار أول [XmlNode](../xmlnode/) يطابق تعبير [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | يختار أول [XmlNode](../xmlnode/) يطابق تعبير [XPath](../../system.xml.xpath/). يتم حل أي سابقة موجودة في تعبير [XPath](../../system.xml.xpath/) باستخدام [XmlNamespaceManager](../xmlnamespacemanager/) الموفّرة. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | يرمى استثناء InvalidOperationException في جميع الحالات. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | يضبط العلامات التي تمثل أبناء العقدة الحالية. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | يضبط سابقة مساحة الاسم لهذه العقدة. |
| void [set_PreserveWhitespace](./set_preservewhitespace/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب الحفاظ على مسافات بيضاء في محتوى العنصر. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | يضبط كائن XmlSchemaSet المرتبط بهذا [XmlDocument](./). |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | يضبط قيمة العقدة. |
| virtual void [set_XmlResolver](./set_xmlresolver/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>) | يضبط [XmlResolver](../xmlresolver/) لاستخدامه في حل الموارد الخارجية. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n بمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | يفحص ما إذا كان تنفيذ DOM يدعم ميزة محددة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مقابل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يَنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل جملة C# lock() . استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | يَتحقق من صحة [XmlDocument](./) ضد مخططات لغة تعريف XML [Schema](../../system.xml.schema/) (XSD) الموجودة في قائمة [XmlDocument::get_Schemas](./get_schemas/). |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | يَتحقق من صحة كائن [XmlNode](../xmlnode/) المحدد ضد مخططات لغة تعريف XML [Schema](../../system.xml.schema/) (XSD) في قائمة [XmlDocument::get_Schemas](./get_schemas/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | يحصل على تنفيذ الموقّع begin const للوعاء الحالي. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | يحصل على تنفيذ الموقّع begin للوعاء الحالي. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | يحصل على تنفيذ الموقّع end const للوعاء الحالي. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | يحصل على تنفيذ الموقّع end للوعاء الحالي. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | يحفظ جميع أبناء عقدة [XmlDocument](./) إلى الـ [XmlWriter](../xmlwriter/) المحدد. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | يحفظ عقدة [XmlDocument](./) إلى الـ [XmlWriter](../xmlwriter/) المحدد. |
|  [XmlDocument](./xmldocument/)() | يُهيئ نسخة جديدة من الصنف [XmlDocument](./). |
|  [XmlDocument](./xmldocument/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | يُهيئ نسخة جديدة من الصنف [XmlDocument](./) مع [XmlNameTable](../xmlnametable/) المحدد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار للمؤشر المشترك إلى نسخة من هذا الصنف. |

## ملاحظات

يجب تخصيص كائنات هذا الصنف فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء نسخ من هذا النوع على المكدس أو باستخدام المُشغل new، إذ سيتسبب ذلك في أخطاء وقت التشغيل و/أو أخطاء التحقق. احرص دائمًا على تضمين هذا الصنف داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

## انظر أيضًا

* الصنف [XmlNode](../xmlnode/)
* مساحة الاسم [System::Xml](../)
* المكتبة [Aspose.Slides](../../)