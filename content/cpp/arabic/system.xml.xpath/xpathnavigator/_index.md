---
title: XPathNavigator
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: توفر نموذج مؤشر للتنقل وتحرير بيانات XML.
type: docs
weight: 66
url: /ar/system.xml.xpath/xpathnavigator/
---
## XPathNavigator فئة

Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## الأساليب

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | إرجاع كائن [XmlWriter](../../system.xml/xmlwriter/) يُستخدم لإنشاء عقد فرعية جديدة واحدة أو أكثر في نهاية قائمة العقد الفرعية للعقدة الحالية. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | إنشاء عقدة فرعية جديدة في نهاية قائمة العقد الفرعية للعقدة الحالية باستخدام سلسلة بيانات XML المحددة. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | إنشاء عقدة فرعية جديدة في نهاية قائمة العقد الفرعية للعقدة الحالية باستخدام محتويات XML للكائن [XmlReader](../../system.xml/xmlreader/) المحدد. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | إنشاء عقدة فرعية جديدة في نهاية قائمة العقد الفرعية للعقدة الحالية باستخدام العقد الموجودة في [XPathNavigator](./) المحدد. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | إنشاء عقدة عنصر فرعي جديدة في نهاية قائمة العقد الفرعية للعقدة الحالية باستخدام بادئة الفضاء الاسمي والاسم المحلي وURI الفضاء الاسمي المحددين مع القيمة المحددة. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | التحقق من أن بيانات XML في [XPathNavigator](./) تتطابق مع مخطط لغة تعريف XML [Schema](../../system.xml.schema/) (XSD) المقدم. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | عند تجاوزها في فئة مشتقة، تنشئ كائن [XPathNavigator](./) جديد يتموضع عند نفس العقدة كما هو [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | يقارن موضع [XPathNavigator](./) الحالي بموضع [XPathNavigator](./) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | يقوم بتجميع سلسلة تمثل تعبير [XPath](../) ويعيد كائن [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | ينشئ عقدة سمة على عقدة العنصر الحالية باستخدام بادئة الفضاء الاسمي والاسم المحلي وURI الفضاء الاسمي المحددين مع القيمة المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | إرجاع كائن [XmlWriter](../../system.xml/xmlwriter/) يُستخدم لإنشاء سمات جديدة على العنصر الحالي. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | إرجاع نسخة من [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | حذف نطاق من العقد الشقيقة من العقدة الحالية إلى العقدة المحددة. |
| virtual void [DeleteSelf](./deleteself/)() | حذف العقدة الحالية وعقدها الفرعية. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقارنة الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقارنة كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقارنة كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNين متساويتين رغم أن IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما فيها NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | يقيم التعبير [XPath](../) المحدد ويعيد النتيجة ذات النوع. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | يقيم التعبير [XPath](../) المحدد ويعيد النتيجة ذات النوع، باستخدام كائن [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات الفضاء الاسمي في التعبير [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | يقيم [XPathExpression](../xpathexpression/) ويعيد النتيجة ذات النوع. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | يستخدم السياق المقدم لتقييم [XPathExpression](../xpathexpression/)، ويعيد النتيجة ذات النوع. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | عند تجاوزها في فئة مشتقة، يحصل على URI الأساس للعقدة الحالية. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | إرجاع قيمة تشير إلى ما إذا كان بإمكان [XPathNavigator](./) تعديل بيانات XML الأساسية. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | إرجاع قيمة تشير إلى ما إذا كانت العقدة الحالية لديها أي سمات. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | إرجاع قيمة تشير إلى ما إذا كانت العقدة الحالية لديها أي عقد فرعية. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | إرجاع العلامة التي تمثل العقد الفرعية للعقدة الحالية. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كانت العقدة الحالية عنصرًا فارغًا بدون وسم إغلاق. |
| **bool** [get_IsNode](./get_isnode/)() override | إرجاع قيمة تشير إلى ما إذا كانت العقدة الحالية تمثل عقدة [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | عند تجاوزها في فئة مشتقة، يحصل على [XPathNavigator::get_Name](./get_name/) للعقدة الحالية دون أي بادئة مساحة اسم. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | عند تجاوزها في فئة مشتقة، يحصل على الاسم المؤهل للعقدة الحالية. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | عند تجاوزها في فئة مشتقة، يحصل على URI الفضاء الاسمي للعقدة الحالية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | عند تجاوزها في فئة مشتقة، يحصل على [XmlNameTable](../../system.xml/xmlnametable/) لـ [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | إرجاع كائن [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) يستخدم للمقارنة المتساوية لكائنات [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | عند تجاوزها في فئة مشتقة، يحصل على XPathNodeType للعقدة الحالية. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | إرجاع العلامة التي تمثل وسم الفتح والإغلاق للعقدة الحالية وعقدها الفرعية. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | عند تجاوزها في فئة مشتقة، يحصل على بادئة الفضاء الاسمي المرتبطة بالعقدة الحالية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | إرجاع معلومات المخطط التي تم تعيينها للعقدة الحالية نتيجة للتحقق من صحة المخطط. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | إرجاع العقدة الحالية ككائن معبأ من النوع الأنسب. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | يُستخدم من قبل تنفيذات [XPathNavigator](./) التي توفر عرض XML "مُفترض" فوق مخزن، لتوفير الوصول إلى الكائنات الأساسية. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | عند تجاوزها في فئة مشتقة، يحصل على قيمة **string** للعنصر. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | إرجاع قيمة العقدة الحالية كـ [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | إرجاع قيمة العقدة الحالية كـ [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | إرجاع قيمة العقدة الحالية كـ [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | إرجاع قيمة العقدة الحالية كـ [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | إرجاع قيمة العقدة الحالية كـ [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | إرجاع نوع العقدة الحالية. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | إرجاع نطاق **xml:lang** للعقدة الحالية. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | إرجاع معلومات XmlSchemaType للعقدة الحالية. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | إرجاع قيمة السمة بالاسم المحلي وURI الفضاء الاسمي المحددين. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | الحصول على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | إرجاع قيمة عقدة الفضاء الاسمي المقابلة للاسم المحلي المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | إرجاع مساحات الأسماء في نطاق العقدة الحالية. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | الحصول على النوع الفعلي للكائن. نظير نداء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | إرجاع كائن [XmlWriter](../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة شقيقة جديدة بعد العقدة المحددة حاليًا. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | إنشاء عقدة شقيقة جديدة بعد العقدة المحددة حاليًا باستخدام سلسلة XML المحددة. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | إنشاء عقدة شقيقة جديدة بعد العقدة المحددة حاليًا باستخدام محتويات XML للكائن [XmlReader](../../system.xml/xmlreader/) المحدد. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | إنشاء عقدة شقيقة جديدة بعد العقدة المحددة حاليًا باستخدام العقد الموجودة في كائن [XPathNavigator](./) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | إرجاع كائن [XmlWriter](../../system.xml/xmlwriter/) يُستخدم لإنشاء عقدة شقيقة جديدة قبل العقدة المحددة حاليًا. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | إنشاء عقدة شقيقة جديدة قبل العقدة المحددة حاليًا باستخدام سلسلة XML المحددة. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | إنشاء عقدة شقيقة جديدة قبل العقدة المحددة حاليًا باستخدام محتويات XML للكائن [XmlReader](../../system.xml/xmlreader/) المحدد. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | إنشاء عقدة شقيقة جديدة قبل العقدة المحددة حاليًا باستخدام العقد الموجودة في [XPathNavigator](./) المحدد. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | إنشاء عنصر شقيق جديد بعد العقدة الحالية باستخدام بادئة الفضاء الاسمي والاسم المحلي وURI الفضاء الاسمي المحددين، مع القيمة المحددة. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | إنشاء عنصر شقيق جديد قبل العقدة الحالية باستخدام بادئة الفضاء الاسمي والاسم المحلي وURI الفضاء الاسمي المحددين، مع القيمة المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | التحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموضح بواسطة targetType. نظير عامل C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | تحديد ما إذا كان [XPathNavigator](./) المحدد هو سليل [XPathNavigator](./) الحالي. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | عند تجاوزها في فئة مشتقة، تحدد ما إذا كان [XPathNavigator](./) الحالي في نفس موضع [XPathNavigator](./) المحدد. |
| void [Lock](../../system/object/lock/)() | يطبق قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | إرجاع URI الفضاء الاسمي للبادئة المحددة. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | إرجاع البادئة المُعلنة للURI الفضاء الاسمي المحدد. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | تحديد ما إذا كانت العقدة الحالية تتطابق مع [XPathExpression](../xpathexpression/) المحدد. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | تحديد ما إذا كانت العقدة الحالية تتطابق مع تعبير [XPath](../) المحدد. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | عند تجاوزها في فئة مشتقة، ينقل [XPathNavigator](./) إلى نفس موضع [XPathNavigator](./) المحدد. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | نقل [XPathNavigator](./) إلى السمة ذات الاسم المحلي وURI الفضاء الاسمي المطابقين. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | نقل [XPathNavigator](./) إلى العقدة الفرعية ذات الاسم المحلي وURI الفضاء الاسمي المحددين. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | نقل [XPathNavigator](./) إلى العقدة الفرعية من نوع XPathNodeType المحدد. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | نقل [XPathNavigator](./) إلى أول عقدة شقيقة للعقدة الحالية. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | عند تجاوزها في فئة مشتقة، ينقل [XPathNavigator](./) إلى أول سمة للعقدة الحالية. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | عند تجاوزها في فئة مشتقة، ينقل [XPathNavigator](./) إلى أول عقدة فرعية للعقدة الحالية. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | عند تجاوزها في فئة مشتقة، ينقل [XPathNavigator](./) إلى أول عقدة فضائية اسم تتطابق مع XPathNamespaceScope المحدد. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | يحرك [XPathNavigator](./) إلى أول عقدة مساحة أسماء لل عقدة الحالية. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | يحرك [XPathNavigator](./) إلى العنصر الذي له الاسم المحلي ومسار مساحة الاسم المحددين بترتيب المستند. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | يحرك [XPathNavigator](./) إلى العنصر الذي له الاسم المحلي ومسار مساحة الاسم المحددين، إلى الحد المحدد، بترتيب المستند. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | يحرك [XPathNavigator](./) إلى العنصر التالي من نوع XPathNodeType المحدد بترتيب المستند. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | يحرك [XPathNavigator](./) إلى العنصر التالي من نوع XPathNodeType المحدد، إلى الحد المحدد، بترتيب المستند. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | عند إعادة تعريفه في فئة مشتقة، يتحرك إلى العقدة التي لها سمة من النوع **ID** قيمتها تطابق [String](../../system/string/) المحدد. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | يحرك [XPathNavigator](./) إلى عقدة مساحة الاسم ذات البادئة المحددة. |
| virtual **bool** [MoveToNext](./movetonext/)() | عند إعادة تعريفه في فئة مشتقة، يحرك [XPathNavigator](./) إلى العقدة الشقيقة التالية لل عقدة الحالية. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | يحرك [XPathNavigator](./) إلى العقدة الشقيقة التالية التي لها الاسم المحلي ومسار مساحة الاسم المحددين. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | يحرك [XPathNavigator](./) إلى العقدة الشقيقة التالية لل عقدة الحالية التي تطابق XPathNodeType المحدد. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | عند إعادة تعريفه في فئة مشتقة، يحرك [XPathNavigator](./) إلى السمة التالية. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | عند إعادة تعريفه في فئة مشتقة، يحرك [XPathNavigator](./) إلى عقدة مساحة الاسم التالية التي تطابق XPathNamespaceScope المحدد. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | يحرك [XPathNavigator](./) إلى عقدة مساحة الاسم التالية. |
| virtual **bool** [MoveToParent](./movetoparent/)() | عند إعادة تعريفه في فئة مشتقة، يحرك [XPathNavigator](./) إلى العقدة الأصلية لل عقدة الحالية. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | عند إعادة تعريفه في فئة مشتقة، يحرك [XPathNavigator](./) إلى العقدة الشقيقة السابقة لل عقدة الحالية. |
| virtual void [MoveToRoot](./movetoroot/)() | يحرك [XPathNavigator](./) إلى عقدة الجذر التي تنتمي إليها العقدة الحالية. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | منشئ نسخة. لا ينسخ شيئًا في الواقع، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عامل الإسناد. لا ينسخ شيئًا في الواقع، فقط يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | يرجع كائنًا من نوع [XmlWriter](../../system.xml/xmlwriter/) يستخدم لإنشاء عقدة فرعية جديدة في بداية قائمة العقد الفرعية لل عقدة الحالية. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | ينشئ عقدة فرعية جديدة في بداية قائمة العقد الفرعية لل عقدة الحالية باستخدام سلسلة XML المحددة. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | ينشئ عقدة فرعية جديدة في بداية قائمة العقد الفرعية لل عقدة الحالية باستخدام محتويات XML لكائن [XmlReader](../../system.xml/xmlreader/) المحدد. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | ينشئ عقدة فرعية جديدة في بداية قائمة العقد الفرعية لل عقدة الحالية باستخدام العقد الموجودة في كائن [XPathNavigator](./) المحدد. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | ينشئ عنصرًا فرعيًا جديدًا في بداية قائمة العقد الفرعية لل عقدة الحالية باستخدام بادئة مساحة الاسم والاسم المحلي ومسار مساحة الاسم المحددين مع القيمة المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | يرجع كائنًا من نوع [XmlReader](../../system.xml/xmlreader/) يحتوي على العقدة الحالية وعقدها الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | يستبدل نطاقًا من العقد الشقيقة من العقدة الحالية إلى العقدة المحددة. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | يستبدل العقدة الحالية بمحتوى السلسلة المحددة. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | يستبدل العقدة الحالية بمحتويات كائن [XmlReader](../../system.xml/xmlreader/) المحدد. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | يستبدل العقدة الحالية بمحتويات كائن [XPathNavigator](./) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | يختار مجموعة عقد، باستخدام التعبير [XPath](../) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | يختار مجموعة عقد باستخدام التعبير [XPath](../) المحدد مع كائن [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات مساحة الاسم. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | يختار مجموعة عقد باستخدام [XPathExpression](../xpathexpression/) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | يختار جميع العقد الأصلية لل عقدة الحالية التي لها XPathNodeType مطابقة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | يختار جميع العقد الأصلية لل عقدة الحالية التي لها الاسم المحلي ومسار مساحة الاسم المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | يختار جميع العقد الفرعية لل عقدة الحالية التي لها XPathNodeType مطابقة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | يختار جميع العقد الفرعية لل عقدة الحالية التي لها الاسم المحلي ومسار مساحة الاسم المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | يختار جميع العقد التابعة لل عقدة الحالية التي لها XPathNodeType مطابقة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | يختار جميع العقد التابعة لل عقدة الحالية التي لها الاسم المحلي ومسار مساحة الاسم المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | يختار عقدة واحدة في [XPathNavigator](./) باستخدام الاستعلام [XPath](../) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | يختار عقدة واحدة في كائن [XPathNavigator](./) باستخدام الاستعلام [XPath](../) المحدد مع كائن [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات مساحة الاسم. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | يختار عقدة واحدة في [XPathNavigator](./) باستخدام الكائن [XPathExpression](../xpathexpression/) المحدد. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | يضبط العلامات التي تمثل العقد الفرعية لل عقدة الحالية. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | يضبط العلامات التي تمثل وسوم الفتح والإغلاق لل عقدة الحالية وعقدها الفرعية. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n من النوع **uint32_t** كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يضبط القيمة ذات النوع المحدد لل عقدة الحالية. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | يضبط قيمة العقدة الحالية. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | يرجع القيمة النصية لل عقدة الحالية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | يرجع قيمة العقدة الحالية كالنمط المحدد، باستخدام كائن [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات مساحة الاسم. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | يرجع قيمة العنصر بالنوع المحدد. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | يبث العقدة الحالية وعقدها الفرعية إلى كائن [XmlWriter](../../system.xml/xmlwriter/) المحدد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## تعريفات الأنواع

| تعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |
## أنظر أيضًا

* الفئة [XPathItem](../xpathitem/)
* الفئة [IXPathNavigable](../ixpathnavigable/)
* الفئة [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* مساحة الاسم [System::Xml::XPath](../)
* مكتبة [Aspose.Slides](../../)