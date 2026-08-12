---
title: XmlElement
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक तत्व का प्रतिनिधित्व करता है।
type: docs
weight: 222
url: /hi/system.xml/xmlelement/
---
## XmlElement क्लास

Represents an element.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | निर्दिष्ट नोड को इस नोड के चाइल्ड नोड्स की सूची के अंत में जोड़ता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | कलेक्शन के पहले तत्व (यदि कोई हो) की ओर संकेत करने वाला इटरेटर प्राप्त करता है। यह इटरेटर रेफ़रेंस किए गए ऑब्जेक्ट को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T का एक कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | कलेक्शन की कॉन्स्ट-योग्य इंस्टेंस के पहले तत्व (यदि कोई हो) की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | कलेक्शन के पहले कॉन्स्ट-योग्य तत्व (यदि कोई हो) की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | कलेक्शन के आखिरी कॉन्स्ट-योग्य तत्व (यदि कोई हो) के तुरंत बाद की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | इस नोड की एक प्रतिलिपि बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | इस नोड की एक प्रतिलिपि बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | इस ऑब्जेक्ट को नेविगेट करने के लिए एक XPathNavigator बनाता है। |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | कलेक्शन के आखिरी तत्व (यदि कोई हो) के तुरंत बाद की ओर संकेत करने वाला इटरेटर प्राप्त करता है। यह इटरेटर रेफ़रेंस किए गए ऑब्जेक्ट को बदलने के लिए उपयोग नहीं किया जा सकता क्योंकि [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T का एक कॉपी-ऑब्जेक्ट लौटाता है। |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | कलेक्शन की कॉन्स्ट-योग्य इंस्टेंस के आखिरी तत्व (यदि कोई हो) के तुरंत बाद की ओर संकेत करने वाला इटरेटर प्राप्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | इस नोड के एट्रीब्यूट्स को समाहित करने वाला [XmlAttributeCollection](../xmlattributecollection/) लौटाता है। |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | वर्तमान नोड का बेस URI लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | नोड के सभी चाइल्ड नोड्स लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | नोड का पहला चाइल्ड लौटाता है। |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | एक **bool** मान लौटाता है जो दर्शाता है कि वर्तमान नोड के कोई एट्रीब्यूट्स हैं या नहीं। |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | एक मान लौटाता है जो दर्शाता है कि इस नोड के कोई चाइल्ड नोड्स हैं या नहीं। |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | नोड और उसके सभी चाइल्ड्स के संयोजित मानों को लौटाता है। |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | केवल इस नोड के चाइल्ड्स को दर्शाने वाला मार्कअप लौटाता है। |
| **bool** [get_IsEmpty](./get_isempty/)() | एलीमेंट का टैग फॉर्मेट लौटाता है। |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | एक मान लौटाता है जो दर्शाता है कि नोड केवल-रीड है या नहीं। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | नोड का अंतिम चाइल्ड लौटाता है। |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | वर्तमान नोड का लोकल नाम लौटाता है। |
| [String](../../system/string/) [get_Name](./get_name/)() override | नोड का क्वालिफाइड नाम लौटाता है। |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | इस नोड का नेमस्पेस URI लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | इस नोड के तुरंत बाद आने वाला नोड लौटाता है। |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | वर्तमान नोड का टाइप लौटाता है। |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | इस नोड और उसके सभी चाइल्ड नोड्स को समाहित करने वाला मार्कअप लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() override | इस नोड जिस [XmlDocument](../xmldocument/) से संबंधित है, उसे लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | इस नोड के पैरेंट को लौटाता है (उन नोड्स के लिए जिनके पैरेंट हो सकते हैं)। |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | इस नोड का नेमस्पेस प्रीफ़िक्स लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | इस नोड से तुरंत पहले आने वाला नोड लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | इस नोड से तुरंत पहले स्थित टेक्स्ट नोड लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | स्कीमा वैलिडेशन के परिणामस्वरूप इस नोड को सौंपा गया पोस्ट स्कीमा वैलिडेशन इंफ़ोसैट लौटाता है। |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | नोड का मान लौटाता है। |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | निर्दिष्ट नाम वाले एट्रीब्यूट का मान लौटाता है। |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रीब्यूट का मान लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/)) | निर्दिष्ट नाम वाले [XmlAttribute](../xmlattribute/) को लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले [XmlAttribute](../xmlattribute/) को लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | निर्दिष्ट [XmlElement::get_Name](./get_name/) से मेल खाने वाले सभी डीसेंडेंट एलिमेंट्स की सूची समाहित करने वाला [XmlNodeList](../xmlnodelist/) लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट [XmlElement::get_LocalName](./get_localname/) और [XmlElement::get_NamespaceURI](./get_namespaceuri/) मानों से मेल खाने वाले सभी डीसेंडेंट एलिमेंट्स की सूची समाहित करने वाला [XmlNodeList](../xmlnodelist/) लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | वर्तमान नोड के चाइल्ड नोड्स के माध्यम से इटररेट करने वाला एक एनेमरेटर लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | वर्तमान नोड के स्कोप में दिए गए प्रीफ़िक्स के लिए सबसे निकटतम **xmlns** डिक्लेरेशन खोजता है और डिक्लेरेशन में नेमस्पेस URI लौटाता है। |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | वर्तमान नोड के स्कोप में दिए गए नेमस्पेस URI के लिए सबसे निकटतम **xmlns** डिक्लेरेशन खोजता है और उस डिक्लेरेशन में परिभाषित प्रीफ़िक्स लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/)) | निर्दिष्ट नाम वाले एट्रीब्यूट की मौजूदगी निर्धारित करता है कि वर्तमान नोड में है या नहीं। |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रीब्यूट की मौजूदगी निर्धारित करता है कि वर्तमान नोड में है या नहीं। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | निर्दिष्ट [XmlNode::get_Name](../xmlnode/get_name/) वाला पहला चाइल्ड एलिमेंट लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट [XmlNode::get_LocalName](../xmlnode/get_localname/) और [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) मानों वाला पहला चाइल्ड एलिमेंट लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | निर्दिष्ट नोड को निर्दिष्ट रेफ़रेंस नोड के तुरंत बाद डालता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | निर्दिष्ट नोड को निर्दिष्ट रेफ़रेंस नोड से ठीक पहले डालता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | एक क्रम पर एक्क्यूमुलेटर फ़ंक्शन लागू करता है। |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्या क्रम के सभी तत्व किसी शर्त को संतुष्ट करते हैं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | निर्धारित करता है कि क्रम में कोई भी तत्व हैं या नहीं। |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | निर्धारित करता है कि क्रम का कोई भी तत्व मौजूद है या शर्त को संतुष्ट करता है। |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | संख्यात्मक मानों के क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | इनपुट क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन को लागू करके प्राप्त मानों के क्रम का औसत गणना करता है। |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | एलिमेंट्स को निर्दिष्ट टाइप में कास्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | दो क्रमों को संयोजित करता है। |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | निर्धारित करता है कि क्रम में निर्दिष्ट मूल्य मौजूद है या नहीं। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | क्रम में तत्वों की संख्या लौटाता है (प्रत्यक्ष गणना द्वारा)। |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | क्रम में उन तत्वों की संख्या लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करते हैं। |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | क्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | क्रम में निर्दिष्ट इंडेक्स पर तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | क्रम का पहला तत्व लौटाता है। |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | क्रम में वह पहला तत्व लौटाता है जो निर्दिष्ट शर्त को संतुष्ट करता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | क्रम का पहला तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान देता है। |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | शर्त को संतुष्ट करने वाला क्रम का पहला तत्व लौटाता है, या यदि कोई ऐसा तत्व न मिले तो डिफ़ॉल्ट मान देता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | क्रम के तत्वों को समूहित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | क्रम के तत्वों को समूहित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | क्रम का अंतिम तत्व लौटाता है। |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | क्रम का अंतिम तत्व लौटाता है, या यदि क्रम खाली है तो डिफ़ॉल्ट मान देता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | एक सामान्य क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और अधिकतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | एक सामान्य क्रम के प्रत्येक तत्व पर ट्रांसफ़ॉर्म फ़ंक्शन लागू करता है और न्यूनतम प्राप्त मान लौटाता है। |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | निर्दिष्ट टाइप के आधार पर क्रम के तत्वों को फ़िल्टर करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मानों के आधार पर क्रम के तत्वों को आरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector द्वारा चुनी गई कुंजी मानों के आधार पर क्रम के तत्वों को अवरोही क्रम में सॉर्ट करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | क्रम के तत्वों का क्रम उलटता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | क्रम के तत्वों को ट्रांसफ़ॉर्म करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | तत्वों के इंडेक्स को शामिल करके क्रम के प्रत्येक तत्व को नए रूप में ट्रांसफ़ॉर्म करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | एक अनुक्रम के प्रत्येक तत्व को प्रोजेक्ट करता है और परिणामी अनुक्रमों को एक अनुक्रम में संयोजित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में लगातार तत्वों को छोड़ता है और शेष को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | एक अनुक्रम की शुरुआत से निर्दिष्ट संख्या में लगातार तत्वों को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | एक अनुक्रम से एक ऐरे बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | एक अनुक्रम से List<T> बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | निर्दिष्ट प्रेडिकेट के आधार पर एक अनुक्रम को फ़िल्टर करता है। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| virtual void [Normalize](../xmlnode/normalize/)() | सभी [XmlText](../xmltext/) नोड्स को इस [XmlNode](../xmlnode/) के नीचे सब-ट्री की पूरी गहराई में एक \"सामान्य\" रूप में रखता है जहाँ केवल मार्कअप (जैसे टैग, टिप्पणियाँ, प्रोसेसिंग इंस्ट्रक्शन, CDATA सेक्शन, और एंटिटी रेफ़रेंसेज़) [XmlText](../xmltext/) नोड्स को अलग करती है, अर्थात् कोई सटे हुए [XmlText](../xmltext/) नोड्स नहीं होते। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | निर्दिष्ट नोड को इस नोड के चाइल्ड नोड्स की सूची की शुरुआत में जोड़ता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| void [RemoveAll](./removeall/)() override | वर्तमान नोड के सभी निर्दिष्ट एट्रिब्यूट्स और चाइल्ड को हटाता है। डिफ़ॉल्ट एट्रिब्यूट्स नहीं हटाए जाते। |
| virtual void [RemoveAllAttributes](./removeallattributes/)() | तत्व से सभी निर्दिष्ट एट्रिब्यूट्स को हटाता है। डिफ़ॉल्ट एट्रिब्यूट्स नहीं हटाए जाते। |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/)) | नाम के द्वारा एट्रिब्यूट को हटाता है। |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI के साथ एट्रिब्यूट को हटाता है। (यदि हटाया गया एट्रिब्यूट का डिफ़ॉल्ट मान है, तो वह तुरंत प्रतिस्थापित हो जाता है)। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveAttributeAt](./removeattributeat/)(**int32_t**) | तत्व से निर्दिष्ट इंडेक्स वाले एट्रिब्यूट नोड को हटाता है। (यदि हटाया गया एट्रिब्यूट का डिफ़ॉल्ट मान है, तो वह तुरंत प्रतिस्थापित हो जाता है)। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | निर्दिष्ट [XmlAttribute](../xmlattribute/) को हटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([String](../../system/string/), [String](../../system/string/)) | स्थानीय नाम और नेमस्पेस URI द्वारा निर्दिष्ट [XmlAttribute](../xmlattribute/) को हटाता है। (यदि हटाया गया एट्रिब्यूट का डिफ़ॉल्ट मान है, तो वह तुरंत प्रतिस्थापित हो जाता है)। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | निर्दिष्ट चाइल्ड नोड को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से शेयर किए गए रेफ़रेंस काउंट को घटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | चाइल्ड नोड **oldChild** को **newChild** नोड से प्रतिस्थापित करता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) एक्सप्रेशन से मेल खाने वाले नोड्स की सूची चुनता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) एक्सप्रेशन से मेल खाने वाले नोड्स की सूची चुनता है। [XPath](../../system.xml.xpath/) एक्सप्रेशन में पाए गए किसी भी प्रिफ़िक्स को प्रदान किए गए [XmlNamespaceManager](../xmlnamespacemanager/) का उपयोग करके हल किया जाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) एक्सप्रेशन से मेल खाने वाले पहले [XmlNode](../xmlnode/) को चुनता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) एक्सप्रेशन से मेल खाने वाले पहले [XmlNode](../xmlnode/) को चुनता है। [XPath](../../system.xml.xpath/) एक्सप्रेशन में पाए गए किसी भी प्रिफ़िक्स को प्रदान किए गए [XmlNamespaceManager](../xmlnamespacemanager/) का उपयोग करके हल किया जाता है। |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | नोड और उसके सभी चाइल्ड्स के संयोजित मान सेट करता है। |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | इस नोड के केवल चाइल्ड्स को दर्शाने वाला मार्कअप सेट करता है। |
| void [set_IsEmpty](./set_isempty/)(**bool**) | तत्व का टैग फ़ॉर्मेट सेट करता है। |
| void [set_Prefix](./set_prefix/)([String](../../system/string/)) override | इस नोड का नेमस्पेस प्रीफ़िक्स सेट करता है। |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | नोड का मान सेट करता है। |
| virtual void [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट नाम वाले एट्रिब्यूट का मान सेट करता है। |
| virtual [String](../../system/string/) [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रिब्यूट का मान सेट करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | निर्दिष्ट [XmlAttribute](../xmlattribute/) जोड़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट [XmlAttribute](../xmlattribute/) जोड़ता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए गए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर किए गए रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर किए गए रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | परीक्षण करता है कि DOM इम्प्लीमेंटेशन एक विशिष्ट फीचर को लागू करता है या नहीं। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | वर्तमान कंटेनर के लिए begin const इटरेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | वर्तमान कंटेनर के लिए begin इटरेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | वर्तमान कंटेनर के लिए end const इटरेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | वर्तमान कंटेनर के लिए end इटरेटर का इम्प्लीमेंटेशन प्राप्त करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | नोड के सभी चाइल्ड को निर्दिष्ट [XmlWriter](../xmlwriter/) में सहेजता है। |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | वर्तमान नोड को निर्दिष्ट [XmlWriter](../xmlwriter/) में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक इंस्टेंस के लिए shared pointer का एक उपनाम। |

## टिप्पणी

इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही अल्लोकेट किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम एरर और/या एसेर्शन फ़ॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्युमेंट के रूप में पास करने के लिए करें।

## संबंधित

* क्लास [XmlLinkedNode](../xmllinkednode/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)