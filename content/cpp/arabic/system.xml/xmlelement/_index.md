---
title: XmlElement
second_title: مرجع API Aspose.Slides للغة C++
description: يمثل عنصرًا.
type: docs
weight: 222
url: /ar/system.xml/xmlelement/
---
## فئة XmlElement

يمثل عنصرًا.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يضيف العقدة المحددة إلى نهاية قائمة العقد الفرعية لهذا العقدة. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | يحصل على مُؤشّر يشير إلى العنصر الأول (إن وجد) من المجموعة. لا يمكن استخدام هذا المُؤشّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) يُعيد كائن نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | يحصل على مُؤشّر يشير إلى العنصر الأول (إن وجد) من النسخة المؤهلة للثوابت من المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | يحصل على مُؤشّر يشير إلى العنصر الأول المؤهَّل للثوابت (إن وجد) في المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | يحصل على مُؤشّر يشير مباشرة بعد العنصر الأخير المؤهَّل للثوابت (إن وجد) في المجموعة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | ينشئ نسخة مكررة من هذه العقدة. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | ينشئ نسخة مكررة من هذه العقدة. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | ينشئ XPathNavigator للتنقُّل عبر هذا الكائن. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | يحصل على مُؤشّر يشير مباشرة بعد العنصر الأخير (إن وجد) في المجموعة. لا يمكن استخدام هذا المُؤشّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) يُعيد كائن نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | يحصل على مُؤشّر يشير مباشرة بعد العنصر الأخير (إن وجد) في النسخة المؤهَّلة للثوابت من المجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لمعيار IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أنه وفقًا لمعيار IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | يرجع [XmlAttributeCollection](../xmlattributecollection/) يحتوي على سمات هذه العقدة. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | يرجع عنوان URI الأساسي للعقدة الحالية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | يرجع جميع العقد الفرعية للعقدة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | يرجع أول عقدة فرعية للعقدة. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | يرجع قيمة **bool** تشير إلى ما إذا كانت العقدة الحالية تحتوي على أي سمات. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | يرجع قيمة تشير إلى ما إذا كانت هذه العقدة تحتوي على أي عقد فرعية. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | يرجع القيم المتسلسلة للعقدة وجميع عقدها الفرعية. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | يرجع العلامة التي تمثل فقط عقد هذا العقدة. |
| **bool** [get_IsEmpty](./get_isempty/)() | يرجع تنسيق العلامة للعنصر. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | يرجع قيمة تشير إلى ما إذا كانت العقدة للقراءة فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | يرجع آخر عقدة فرعية للعقدة. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | يرجع الاسم المحلي للعقدة الحالية. |
| [String](../../system/string/) [get_Name](./get_name/)() override | يرجع الاسم المؤهل للعقدة. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | يرجع عنوان URI للمساحة الاسمية لهذه العقدة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | يرجع العقدة التي تلي هذه العقدة مباشرة. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | يرجع نوع العقدة الحالية. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | يرجع العلامة التي تحتوي على هذه العقدة وجميع عقدها الفرعية. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() override | يرجع [XmlDocument](../xmldocument/) التي تنتمي إليها هذه العقدة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | يرجع الوالد لهذه العقدة (للعقد التي يمكن أن يكون لها والد). |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | يرجع بادئة مساحة الاسم لهذه العقدة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | يرجع العقدة التي تسبق هذه العقدة مباشرة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | يرجع عقدة النص التي تسبق هذه العقدة مباشرة. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | يرجع مجموعة معلومات ما بعد التحقق من المخطط التي تم تعيينها لهذه العقدة نتيجة للتحقق من المخطط. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | يرجع قيمة العقدة. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | يرجع القيمة للخاصية بالاسم المحدد. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | يرجع القيمة للخاصية بالاسم المحلي وعنوان URI للمساحة الاسمية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/)) | يرجع [XmlAttribute](../xmlattribute/) بالاسم المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/), [String](../../system/string/)) | يرجع [XmlAttribute](../xmlattribute/) بالاسم المحلي وعنوان URI للمساحة الاسمية المحددين. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | يرجع [XmlNodeList](../xmlnodelist/) يحتوي على قائمة بجميع العناصر النابية التي تطابق [XmlElement::get_Name](./get_name/) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | يرجع [XmlNodeList](../xmlnodelist/) يحتوي على قائمة بجميع العناصر النابية التي تطابق القيم المحددة لـ [XmlElement::get_LocalName](./get_localname/) و[XmlElement::get_NamespaceURI](./get_namespaceuri/). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | يرجع عدادًا يتنقل عبر العقد الفرعية في العقدة الحالية. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | يبحث عن أقرب تعريف **xmlns** للبادئة المعطاة الموجود في نطاق العقدة الحالية ويعيد عنوان URI للمساحة الاسمية في التعريف. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | يبحث عن أقرب تعريف **xmlns** لعنوان URI للمساحة الاسمية المعطى الموجود في نطاق العقدة الحالية ويعيد البادئة المحددة في ذلك التعريف. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مكافئ لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/)) | يحدد ما إذا كانت العقدة الحالية لديها خاصية بالاسم المحدد. |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/), [String](../../system/string/)) | يحدد ما إذا كانت العقدة الحالية لديها خاصية بالاسم المحلي وعنوان URI للمساحة الاسمية المحددين. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | يرجع أول عنصر فرعي بال[XmlNode::get_Name](../xmlnode/get_name/) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | يرجع أول عنصر فرعي بالقيم المحددة لـ [XmlNode::get_LocalName](../xmlnode/get_localname/) و[XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يدخل العقدة المحددة مباشرة بعد عقدة المرجع المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يدخل العقدة المحددة مباشرة قبل عقدة المرجع المحددة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مكافئ لمشغل C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة التجميع على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تحقق شرطًا. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجودًا أو يحقق شرطًا. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | يحسب المتوسط لتسلسل من القيم الرقمية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب المتوسط لتسلسل من القيم التي يتم الحصول عليها عن طريق استدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | يحول العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | يدمج تسلسلين. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | يرجع عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع عدد العناصر في التسلسل التي تحقق الشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | يرجع العنصر عند الفهرس المحدد في تسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | يرجع العنصر عند الفهرس المحدد في تسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | يرجع أول عنصر من تسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع أول عنصر من تسلسل يحقق الشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | يرجع أول عنصر من تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يرجع أول عنصر من التسلسل يحقق شرطًا أو قيمة افتراضية إذا لم يُعثر على عنصر كهذا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر التسلسل في مجموعات. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر التسلسل في مجموعات. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | يرجع آخر عنصر من تسلسل. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | يرجع آخر عنصر من تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويُرجع القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويُرجع القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | ينقّح عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل تصاعديًا وفقًا للقيم المفتاحية المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل تنازليًا وفقًا للقيم المفتاحية المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوّل عناصر تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوّل كل عنصر من تسلسل إلى شكل جديد من خلال دمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | يطبق كل عنصر في تسلسل ويربط التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية التسلسل ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتتالية من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | يفلتر تسلسلًا بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| virtual void [Normalize](../xmlnode/normalize/)() | يضع جميع عقد [XmlText](../xmltext/) في العمق الكامل للشجرة الفرعية تحت [XmlNode](../xmlnode/) في شكل \"عادي\" حيث يفصل فقط الترميز (أي العلامات، التعليقات، تعليمات المعالجة، أقسام CDATA، وإشارات الكيانات) بين عقد [XmlText](../xmltext/)، أي لا توجد عقد [XmlText](../xmltext/) متجاورة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يضيف العقدة المحددة إلى بداية قائمة العقد الفرعية لهذا العقد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائنًا من نوع قيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [RemoveAll](./removeall/)() override | يزيل جميع السمات المحددة والأطفال للعقدة الحالية. لا تُزال السمات الافتراضية. |
| virtual void [RemoveAllAttributes](./removeallattributes/)() | يزيل جميع السمات المحددة من العنصر. لا تُزال السمات الافتراضية. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/)) | يزيل سمة بالاسم. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/), [String](../../system/string/)) | يزيل سمة بالاسم المحلي والمسار الاسمي المحدد. (إذا كانت السمة المزالة لها قيمة افتراضية، يتم استبدالها فورًا). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveAttributeAt](./removeattributeat/)(**int32_t**) | يزيل عقدة الصفة ذات الفهرس المحدد من العنصر. (إذا كانت الصفة المزالة لها قيمة افتراضية، يتم استبدالها فورًا). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | يزيل الـ [XmlAttribute](../xmlattribute/) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([String](../../system/string/), [String](../../system/string/)) | يزيل الـ [XmlAttribute](../xmlattribute/) المحدد بالاسم المحلي والمسار الاسمي. (إذا كانت الصفة المزالة لها قيمة افتراضية، يتم استبدالها فورًا). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يزيل العقدة الفرعية المحددة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | يستبدل العقدة الفرعية **oldChild** بعقدة **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | يختار قائمة من العقد التي تطابق تعبير [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | يختار قائمة من العقد التي تطابق تعبير [XPath](../../system.xml.xpath/). يتم حل أي بادئات موجودة في تعبير [XPath](../../system.xml.xpath/) باستخدام [XmlNamespaceManager](../xmlnamespacemanager/) المقدم. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | يختار أول [XmlNode](../xmlnode/) يطابق تعبير [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | يختار أول [XmlNode](../xmlnode/) يطابق تعبير [XPath](../../system.xml.xpath/). يتم حل أي بادئات في تعبير [XPath](../../system.xml.xpath/) باستخدام [XmlNamespaceManager](../xmlnamespacemanager/) المقدم. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | يضبط القيم المدمجة للعقدة وجميع أطفالها. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | يضبط الترميز الذي يمثل فقط أطفال هذه العقدة. |
| void [set_IsEmpty](./set_isempty/)(**bool**) | يضبط تنسيق الوسم للعنصر. |
| void [set_Prefix](./set_prefix/)([String](../../system/string/)) override | يضبط بادئة مساحة الاسم لهذه العقدة. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | يضبط قيمة العقدة. |
| virtual void [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/)) | يضبط قيمة الصفة بالاسم المحدد. |
| virtual [String](../../system/string/) [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | يضبط قيمة الصفة بالاسم المحلي والمسار الاسمي المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | يضيف الـ [XmlAttribute](../xmlattribute/) المحدد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([String](../../system/string/), [String](../../system/string/)) | يضيف الـ [XmlAttribute](../xmlattribute/) المحدد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | يفحص ما إذا كان تطبيق DOM يدعم خاصية معينة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | يحصل على تنفيذ iterator const للبدء للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | يحصل على تنفيذ iterator للبدء للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | يحصل على تنفيذ iterator const للانتهاء للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | يحصل على تنفيذ iterator للانتهاء للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | يحفظ جميع أطفال العقدة إلى [XmlWriter](../xmlwriter/) المحدد. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | يحفظ العقدة الحالية إلى [XmlWriter](../xmlwriter/) المحدد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## التعريفات

| اسم تعريف | الوصف |
| --- | --- |
| [Ptr](./ptr/) | اسم مستعار لمؤشر مشترك إلى نسخة من هذه الفئة. |
## ملاحظات

يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تنشئ أبدًا مثيلات من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أعطال التحقق. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. 

## انظر أيضًا

* الفئة [XmlLinkedNode](../xmllinkednode/)
* مساحة الاسم [System::Xml](../)
* مكتبة [Aspose.Slides](../../)