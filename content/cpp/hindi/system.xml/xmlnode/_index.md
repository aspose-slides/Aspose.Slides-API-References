---
title: XmlNode
second_title: Aspose.Slides for C++ API संदर्भ
description: XML दस्तावेज़ में एकल नोड का प्रतिनिधित्व करता है।
type: docs
weight: 326
url: /hi/system.xml/xmlnode/
---
## XmlNode क्लास

XML दस्तावेज़ में एकल नोड का प्रतिनिधित्व करता है।

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | निर्दिष्ट नोड को इस नोड के चाइल्ड नोड्स की सूची के अंत में जोड़ता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | संग्रह के पहले तत्व (यदि कोई हो) की ओर संकेत करने वाला iterator प्राप्त करता है। यह iterator किसी संदर्भित ऑब्जेक्ट को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T की एक कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | संग्रह के const-योग्य इंस्टेंस के पहले तत्व (यदि कोई हो) की ओर संकेत करने वाला iterator प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | संग्रह के पहले const-योग्य तत्व (यदि कोई हो) की ओर संकेत करने वाला iterator प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | संग्रह के अंतिम const-योग्य तत्व (यदि कोई हो) के ठीक बाद की ओर संकेत करने वाला iterator प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [Clone](./clone/)() | इस नोड की एक प्रतिलिपि बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [CloneNode](./clonenode/)(**bool**) | जब व्युत्पन्न क्लास में ओवरराइड किया जाए, तो नोड की एक प्रतिलिपि बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | इस ऑब्जेक्ट को नेविगेट करने के लिए एक XPathNavigator बनाता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | संग्रह के अंतिम तत्व (यदि कोई हो) के ठीक बाद की ओर संकेत करने वाला iterator प्राप्त करता है। यह iterator किसी संदर्भित ऑब्जेक्ट को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T की एक कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | संग्रह के const-योग्य इंस्टेंस के अंतिम तत्व (यदि कोई हो) के ठीक बाद की ओर संकेत करने वाला iterator प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](./get_attributes/)() | इस नोड के गुणों को शामिल करने वाला [XmlAttributeCollection](../xmlattributecollection/) लौटाता है। |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | वर्तमान नोड का बेस URI लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](./get_childnodes/)() | नोड के सभी चाइल्ड नोड्स लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_FirstChild](./get_firstchild/)() | नोड का पहला चाइल्ड लौटाता है। |
| virtual **bool** [get_HasChildNodes](./get_haschildnodes/)() | यह दर्शाने वाला मान लौटाता है कि इस नोड के कोई चाइल्ड नोड्स हैं या नहीं। |
| virtual [String](../../system/string/) [get_InnerText](./get_innertext/)() | नोड और उसके सभी चाइल्ड नोड्स के संयोजित मान लौटाता है। |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | इस नोड के केवल चाइल्ड नोड्स को प्रदर्शित करने वाला मार्कअप लौटाता है। |
| virtual **bool** [get_IsReadOnly](./get_isreadonly/)() | यह दर्शाने वाला मान लौटाता है कि नोड केवल-पढ़ने योग्य है या नहीं। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_LastChild](./get_lastchild/)() | नोड का अंतिम चाइल्ड लौटाता है। |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | व्युत्पन्न क्लास में ओवरराइड होने पर नोड का स्थानीय नाम लौटाता है। |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | व्युत्पन्न क्लास में ओवरराइड होने पर नोड का क्वालिफाइड नाम लौटाता है। |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | इस नोड का नेमस्पेस URI लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_NextSibling](./get_nextsibling/)() | इस नोड के तुरंत बाद आने वाला नोड लौटाता है। |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | व्युत्पन्न क्लास में ओवरराइड होने पर वर्तमान नोड का प्रकार लौटाता है। |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | इस नोड और उसके सभी चाइल्ड नोड्स को शामिल करने वाला मार्कअप लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() | इस नोड जिस [XmlDocument](../xmldocument/) का हिस्सा है, उसे लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_ParentNode](./get_parentnode/)() | इस नोड का पैरेंट लौटाता है (उन नोड्स के लिए जो पैरेंट रख सकते हैं)। |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | इस नोड का नेमस्पेस प्रीफ़िक्स लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousSibling](./get_previoussibling/)() | इस नोड से ठीक पहले वाला नोड लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousText](./get_previoustext/)() | इस नोड से ठीक पहले आने वाला टेक्स्ट नोड लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | स्कीमा वैलिडेशन के परिणामस्वरूप इस नोड को सौंपे गए पोस्ट-स्कीमा वैलिडेशन इन्फोसैट को लौटाता है। |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | नोड का मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>\>\> [GetEnumerator](./getenumerator/)() override | वर्तमान नोड के चाइल्ड नोड्स के माध्यम से इटरेट करने वाला एन्न्यूमरेटर लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](./getnamespaceofprefix/)([String](../../system/string/)) | वर्तमान नोड के लिए स्कोप में मौजूद दिए गए प्रीफ़िक्स की सबसे निकटतम **xmlns** घोषणा खोजता है और घोषणा में नेमस्पेस URI लौटाता है। |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](./getprefixofnamespace/)([String](../../system/string/)) | वर्तमान नोड के लिए स्कोप में मौजूद दिए गए नेमस्पेस URI की सबसे निकटतम **xmlns** घोषणा खोजता है और उस घोषणा में परिभाषित प्रीफ़िक्स लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/)) | निर्दिष्ट [XmlNode::get_Name](./get_name/) वाले पहले चाइल्ड एलिमेंट को लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट [XmlNode::get_LocalName](./get_localname/) और [XmlNode::get_NamespaceURI](./get_namespaceuri/) मानों वाले पहले चाइल्ड एलिमेंट को लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | निर्दिष्ट नोड को निर्दिष्ट रेफ़रेंस नोड के तुरंत बाद डालता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | निर्दिष्ट नोड को निर्दिष्ट रेफ़रेंस नोड के तुरंत पहले डालता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | एक क्रम पर एग्रीगेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्रम के सभी तत्व किसी शर्त को संतुष्ट करते हैं या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | निर्धारित करता है कि क्रम में कोई तत्व हैं या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्रम में कोई तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मूल्यों के क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करके प्राप्त मानों के क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | तत्वों को निर्दिष्ट टाइप में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो क्रमों को क्रमबद्ध करता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | निर्धारित करता है कि क्रम में निर्दिष्ट मान मौजूद है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | क्रम में तत्वों की संख्या लौटाता है (सीधे गिनती द्वारा गणना किया गया)। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को संतुष्ट करने वाले क्रम के तत्वों की संख्या लौटाता है। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | क्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | क्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | क्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | निर्दिष्ट शर्त को संतुष्ट करने वाले क्रम का पहला तत्व लौटाता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | क्रम का पहला तत्व लौटाता है, या यदि क्रम खाली है तो एक डिफ़ॉल्ट मान। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाला क्रम का पहला तत्व लौटाता है, या यदि ऐसा तत्व नहीं मिला तो डिफ़ॉल्ट मान। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | क्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | क्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | क्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | क्रम का अंतिम तत्व लौटाता है, या यदि क्रम खाली है तो एक डिफ़ॉल्ट मान। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम परिणामस्वरूप मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | सामान्य क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम परिणामस्वरूप मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्दिष्ट टाइप के आधार पर क्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार क्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चयनित कुंजी मानों के अनुसार क्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | क्रम के तत्वों का क्रम उलट देता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के तत्वों को परिवर्तित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | क्रम के प्रत्येक तत्व को उसके इंडेक्स को सम्मिलित करके नई रूप में परिवर्तित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | क्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और उत्पन्न क्रमों को एक क्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में क्रमबद्ध तत्वों को छोड़ देता है और शेष लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | क्रम की शुरुआत से निर्दिष्ट संख्या में क्रमबद्ध तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | क्रम से एक ऐरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | क्रम से एक List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर क्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| virtual void [Normalize](./normalize/)() | इस [XmlNode](./) के अंतर्गत सब-ट्री की पूरी गहराई में सभी [XmlText](../xmltext/) नोड्स को "सामान्य" रूप में रखता है जहाँ केवल मार्कअप (टैग, कमेंट, प्रोसेसिंग इंस्ट्रक्शन, CDATA सेक्शन, और एंटिटी रेफ़रेंसेस) [XmlText](../xmltext/) नोड्स को अलग करता है, यानी कोई निकटवर्ती [XmlText](../xmltext/) नोड नहीं होते। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कॉन्स्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कॉन्स्ट्रक्शन सक्षम करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | निर्दिष्ट नोड को इस नोड के चाइल्ड नोड्स की सूची की शुरुआत में जोड़ता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| virtual void [RemoveAll](./removeall/)() | वर्तमान नोड के सभी चाइल्ड नोड्स और/या एट्रिब्यूट्स को हटा देता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [RemoveChild](./removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | निर्दिष्ट चाइल्ड नोड को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [ReplaceChild](./replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | चाइल्ड नोड **oldChild** को **newChild** नोड से बदलता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) अभिव्यक्ति से मेल खाने वाले नोड्स की सूची का चयन करता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) अभिव्यक्ति से मेल खाने वाले नोड्स की सूची का चयन करता है। [XPath](../../system.xml.xpath/) अभिव्यक्ति में मिले किसी भी प्रीफ़िक्स को प्रदान किए गए [XmlNamespaceManager](../xmlnamespacemanager/) के द्वारा हल किया जाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) अभिव्यक्ति से मेल खाने वाला पहला [XmlNode](./) चुनता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) अभिव्यक्ति से मेल खाने वाला पहला [XmlNode](./) चुनता है। [XPath](../../system.xml.xpath/) अभिव्यक्ति में मिले किसी भी प्रीफ़िक्स को प्रदान किए गए [XmlNamespaceManager](../xmlnamespacemanager/) के द्वारा हल किया जाता है। |
| virtual void [set_InnerText](./set_innertext/)([String](../../system/string/)) | नोड और उसके सभी चाइल्ड नोड्स के संयोजित मान सेट करता है। |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | इस नोड के केवल चाइल्ड नोड्स को दर्शाने वाला मार्कअप सेट करता है। |
| virtual void [set_Prefix](./set_prefix/)([String](../../system/string/)) | इस नोड का नेमस्पेस प्रीफ़िक्स सेट करता है। |
| virtual void [set_Value](./set_value/)([String](../../system/string/)) | नोड का मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेंप्लेट के n'th आर्ग्युमेंट को weak पॉइंटर (साझा के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual **bool** [Supports](./supports/)([String](../../system/string/), [String](../../system/string/)) | जाँच करता है कि DOM कार्यान्वयन कोई विशिष्ट सुविधा लागू करता है या नहीं। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के begin const iterator का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के begin iterator का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के end const iterator का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के end iterator का इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | व्युत्पन्न क्लास में ओवरराइड होने पर नोड के सभी चाइल्ड नोड्स को निर्दिष्ट [XmlWriter](../xmlwriter/) में सहेजता है। |
| virtual void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | व्युत्पन्न क्लास में ओवरराइड होने पर वर्तमान नोड को निर्दिष्ट [XmlWriter](../xmlwriter/) में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक इंस्टेंस के लिए shared pointer का उपनाम। |

## देखें भी

* क्लास [IEnumerable](../../system.collections.generic/ienumerable/)
* क्लास [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)