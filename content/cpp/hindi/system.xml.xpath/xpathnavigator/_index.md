---
title: XPathNavigator
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: XML डेटा को नेविगेट करने और संपादित करने के लिए एक कर्सर मॉडल प्रदान करता है।
type: docs
weight: 66
url: /hi/system.xml.xpath/xpathnavigator/
---
## XPathNavigator क्लास

Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | वर्तमान नोड की बाल नोड्स की सूची के अंत में एक या अधिक नई बाल नोड्स बनाने के लिए उपयोग किए जाने वाले [XmlWriter](../../system.xml/xmlwriter/) ऑब्जेक्ट को लौटाता है। |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | निर्दिष्ट XML डेटा स्ट्रिंग का उपयोग करके वर्तमान नोड की बाल नोड्स की सूची के अंत में एक नया बाल नोड बनाता है। |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | निर्दिष्ट [XmlReader](../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग करके वर्तमान नोड की बाल नोड्स की सूची के अंत में एक नया बाल नोड बनाता है। |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | निर्दिष्ट [XPathNavigator](./) में नोड्स का उपयोग करके वर्तमान नोड की बाल नोड्स की सूची के अंत में एक नया बाल नोड बनाता है। |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट मान के साथ दिए गए नेमस्पेस प्रीफ़िक्स, लोकल नेम और नेमस्पेस URI का उपयोग करके वर्तमान नोड की बाल नोड्स की सूची के अंत में एक नया बाल एलेमेंट नोड बनाता है। |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | [XPathNavigator](./) में XML डेटा यह सत्यापित करता है कि वह प्रदान किए गए XML [Schema](../../system.xml.schema/) डिफ़िनिशन भाषा (XSD) स्कीमा के अनुरूप है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, इस [XPathNavigator](./) के समान नोड पर स्थित एक नया [XPathNavigator](./) बनाता है। |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | वर्तमान [XPathNavigator](./) की स्थिति की तुलना निर्दिष्ट [XPathNavigator](./) की स्थिति से करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | [XPath](../) अभिव्यक्ति का प्रतिनिधित्व करने वाली स्ट्रिंग को संकलित करता है और एक [XPathExpression](../xpathexpression/) ऑब्जेक्ट लौटाता है। |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट मान के साथ दिए गए नेमस्पेस प्रीफ़िक्स, लोकल नेम और नेमस्पेस URI का उपयोग करके वर्तमान एलेमेंट नोड पर एक एट्रीब्यूट नोड बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | वर्तमान एलेमेंट पर नए एट्रीब्यूट्स बनाने के लिए उपयोग किए जाने वाले [XmlWriter](../../system.xml/xmlwriter/) ऑब्जेक्ट को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | [XPathNavigator](./) की प्रतिलिपि लौटाता है। |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | वर्तमान नोड से लेकर निर्दिष्ट नोड तक के सिब्लिंग नोड्स की रेंज को हटाता है। |
| virtual void [DeleteSelf](./deleteself/)() | वर्तमान नोड और उसके बाल नोड्स को हटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकूलन करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकूलन करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | निर्दिष्ट [XPath](../) अभिव्यक्ति का मूल्यांकन करता है और टाइप्ड परिणाम लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | निर्दिष्ट [XPath](../) अभिव्यक्ति का मूल्यांकन करता है और टाइप्ड परिणाम लौटाता है, [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके [XPath](../) अभिव्यक्ति में नेमस्पेस प्रीफ़िक्स को हल करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | [XPathExpression](../xpathexpression/) का मूल्यांकन करता है और टाइप्ड परिणाम लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | प्रदान किए गए कॉन्टेक्स्ट का उपयोग करके [XPathExpression](../xpathexpression/) का मूल्यांकन करता है, और टाइप्ड परिणाम लौटाता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उद्देश्यों के लिए। |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, वर्तमान नोड के लिए बेस URI प्राप्त करता है। |
| virtual **bool** [get_CanEdit](./get_canedit/)() | एक मान लौटाता है जो दर्शाता है कि क्या [XPathNavigator](./) अंतर्निहित XML डेटा को संपादित कर सकता है। |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | एक मान लौटाता है जो दर्शाता है कि वर्तमान नोड के कोई एट्रीब्यूट्स हैं या नहीं। |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | एक मान लौटाता है जो दर्शाता है कि वर्तमान नोड के कोई चाइल्ड नोड्स हैं या नहीं। |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | वर्तमान नोड के चाइल्ड नोड्स को दर्शाने वाला मार्कअप लौटाता है। |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, यह मान प्राप्त करता है जो दर्शाता है कि वर्तमान नोड कोई एंड एलेमेंट टैग के बिना एक खाली एलेमेंट है या नहीं। |
| **bool** [get_IsNode](./get_isnode/)() override | एक मान लौटाता है जो दर्शाता है कि क्या वर्तमान नोड एक [XPath](../) नोड का प्रतिनिधित्व करता है। |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, नेमस्पेस प्रीफ़िक्स के बिना वर्तमान नोड का [XPathNavigator::get_Name](./get_name/) प्राप्त करता है। |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, वर्तमान नोड का क्वालिफाइड नेम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, वर्तमान नोड का नेमस्पेस URI प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, [XPathNavigator](./) का [XmlNameTable](../../system.xml/xmlnametable/) प्राप्त करता है। |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | [XPathNavigator](./) ऑब्जेक्ट्स की समानता तुलना के लिए उपयोग किया जाने वाला [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) लौटाता है। |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, वर्तमान नोड का XPathNodeType प्राप्त करता है। |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | वर्तमान नोड और उसके चाइल्ड नोड्स के ओपनिंग और क्लोजिंग टैग्स को दर्शाने वाला मार्कअप लौटाता है। |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, वर्तमान नोड से जुड़ा नेमस्पेस प्रीफ़िक्स प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | स्कीमा वैधता के परिणामस्वरूप वर्तमान नोड को सौंपा गया स्कीमा जानकारी लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | वर्तमान नोड को सबसे उपयुक्त प्रकार के बॉक्स्ड ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | [XPathNavigator](./) कार्यान्वयन द्वारा उपयोग किया जाता है जो स्टोर पर एक "वर्चुअलाइज़्ड" XML व्यू प्रदान करते हैं, अंतर्निहित ऑब्जेक्ट्स तक पहुंच प्रदान करने के लिए। |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, आइटम का **string** मान प्राप्त करता है। |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | वर्तमान नोड के मान को [Boolean](../../system/boolean/) के रूप में लौटाता है। |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | वर्तमान नोड के मान को [DateTime](../../system/datetime/) के रूप में लौटाता है। |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | वर्तमान नोड के मान को [Double](../../system/double/) के रूप में लौटाता है। |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | वर्तमान नोड के मान को [Int32](../../system/int32/) के रूप में लौटाता है। |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | वर्तमान नोड के मान को [Int64](../../system/int64/) के रूप में लौटाता है। |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | वर्तमान नोड का टाइप लौटाता है। |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | वर्तमान नोड के लिए **xml:lang** स्कोप लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | वर्तमान नोड के लिए XmlSchemaType जानकारी लौटाता है। |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट लोकल नेम और नेमस्पेस URI वाले एट्रीब्यूट का मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर है। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | निर्दिष्ट लोकल नेम से संबंधित नेमस्पेस नोड का मान लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | वर्तमान नोड के इन-स्कोप नेमस्पेसेस लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | वर्तमान चयनित नोड के बाद एक नया सिब्लिंग नोड बनाने के लिए उपयोग किए जाने वाले [XmlWriter](../../system.xml/xmlwriter/) ऑब्जेक्ट को लौटाता है। |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | निर्दिष्ट XML स्ट्रिंग का उपयोग करके वर्तमान चयनित नोड के बाद एक नया सिब्लिंग नोड बनाता है। |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | निर्दिष्ट [XmlReader](../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग करके वर्तमान चयनित नोड के बाद एक नया सिब्लिंग नोड बनाता है। |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | निर्दिष्ट [XPathNavigator](./) ऑब्जेक्ट में नोड्स का उपयोग करके वर्तमान चयनित नोड के बाद एक नया सिब्लिंग नोड बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | वर्तमान चयनित नोड से पहले एक नया सिब्लिंग नोड बनाने के लिए उपयोग किए जाने वाले [XmlWriter](../../system.xml/xmlwriter/) ऑब्जेक्ट को लौटाता है। |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | निर्दिष्ट XML स्ट्रिंग का उपयोग करके वर्तमान चयनित नोड से पहले एक नया सिब्लिंग नोड बनाता है। |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | निर्दिष्ट [XmlReader](../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग करके वर्तमान चयनित नोड से पहले एक नया सिब्लिंग नोड बनाता है। |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | निर्दिष्ट [XPathNavigator](./) में नोड्स का उपयोग करके वर्तमान चयनित नोड से पहले एक नया सिब्लिंग नोड बनाता है। |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट नेमस्पेस प्रीफ़िक्स, लोकल नेम और नेमस्पेस URI, तथा निर्दिष्ट मान का उपयोग करके वर्तमान नोड के बाद एक नया सिब्लिंग एलेमेंट बनाता है। |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट नेमस्पेस प्रीफ़िक्स, लोकल नेम, नेमस्पेस URI, और निर्दिष्ट मान का उपयोग करके वर्तमान नोड से पहले एक नया सिब्लिंग एलेमेंट बनाता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है। C# 'is' ऑपरेटर के समान। |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | निर्दिष्ट [XPathNavigator](./) वर्तमान [XPathNavigator](./) का वंशज है या नहीं निर्धारित करता है। |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | डिराइव्ड क्लास में ओवरराइड किए जाने पर, यह निर्धारित करता है कि वर्तमान [XPathNavigator](./) निर्दिष्ट [XPathNavigator](./) के समान स्थिति में है या नहीं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | निर्दिष्ट प्रीफ़िक्स के लिए नेमस्पेस URI लौटाता है। |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | निर्दिष्ट नेमस्पेस URI के लिए घोषित प्रीफ़िक्स लौटाता है। |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | जाँचता है कि क्या वर्तमान नोड निर्दिष्ट [XPathExpression](../xpathexpression/) के साथ मेल खाता है। |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | जाँचता है कि क्या वर्तमान नोड निर्दिष्ट [XPath](../) अभिव्यक्ति के साथ मेल खाता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर है। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | डिराइव्ड क्लास में ओवरराइड किए जाने पर, [XPathNavigator](./) को निर्दिष्ट [XPathNavigator](./) के समान स्थिति में ले जाता है। |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) को मिलते-जुलते लोकल नेम और नेमस्पेस URI वाले एट्रीब्यूट में ले जाता है। |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) को निर्दिष्ट लोकल नेम और नेमस्पेस URI वाले चाइल्ड नोड में ले जाता है। |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./) को निर्दिष्ट XPathNodeType के चाइल्ड नोड में ले जाता है। |
| virtual **bool** [MoveToFirst](./movetofirst/)() | [XPathNavigator](./) को वर्तमान नोड के पहले सिब्लिंग नोड में ले जाता है। |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, [XPathNavigator](./) को वर्तमान नोड के पहले एट्रीब्यूट में ले जाता है। |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | डिराइव्ड क्लास में ओवरराइड किए जाने पर, [XPathNavigator](./) को वर्तमान नोड के पहले चाइल्ड नोड में ले जाता है। |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | डिराइव्ड क्लास में ओवरराइड किए जाने पर, [XPathNavigator](./) को निर्दिष्ट XPathNamespaceScope से मेल खाने वाले पहले नेमस्पेस नोड में ले जाता है। |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | [XPathNavigator](./) को वर्तमान नोड के पहले नेमस्पेस नोड पर ले जाता है। |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) को दस्तावेज़ क्रम में निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले तत्व पर ले जाता है। |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./) को दस्तावेज़ क्रम में निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले तत्व तक, निर्दिष्ट सीमा तक ले जाता है। |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./) को दस्तावेज़ क्रम में निर्दिष्ट XPathNodeType के अगले तत्व तक ले जाता है। |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./) को दस्तावेज़ क्रम में निर्दिष्ट XPathNodeType के अगले तत्व तक, निर्दिष्ट सीमा तक ले जाता है। |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | जब विरासत वर्ग में ओवरराइड किया जाता है, तो ऐसे नोड पर ले जाता है जिसमें **ID** प्रकार का गुण हो जिसका मान निर्दिष्ट [String](../../system/string/) से मेल खाता है। |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | [XPathNavigator](./) को निर्दिष्ट नेमस्पेस उपसर्ग वाले नेमस्पेस नोड पर ले जाता है। |
| virtual **bool** [MoveToNext](./movetonext/)() | जब विरासत वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](./) को वर्तमान नोड के अगले सहोदर नोड पर ले जाता है। |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) को निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले सहोदर नोड पर ले जाता है। |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./) को वर्तमान नोड के अगले सहोदर नोड पर ले जाता है जो निर्दिष्ट XPathNodeType से मेल खाता है। |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | जब विरासत वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](./) को अगले गुण पर ले जाता है। |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | जब विरासत वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](./) को निर्दिष्ट XPathNamespaceScope से मेल खाने वाले अगले नेमस्पेस नोड पर ले जाता है। |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | [XPathNavigator](./) को अगले नेमस्पेस नोड पर ले जाता है। |
| virtual **bool** [MoveToParent](./movetoparent/)() | जब विरासत वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](./) को वर्तमान नोड के पैरेंट नोड पर ले जाता है। |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | जब विरासत वर्ग में ओवरराइड किया जाता है, तो [XPathNavigator](./) को वर्तमान नोड के पिछले सहोदर नोड पर ले जाता है। |
| virtual void [MoveToRoot](./movetoroot/)() | [XPathNavigator](./) को उस मूल नोड पर ले जाता है जिससे वर्तमान नोड संबंधित है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों के कॉपी निर्माण को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों के कॉपी निर्माण को सक्षम बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | एक [XmlWriter](../../system.xml/xmlwriter/) ऑब्जेक्ट लौटाता है जिसका उपयोग वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड नोड बनाने के लिए किया जाता है। |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | निर्दिष्ट XML स्ट्रिंग का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड नोड बनाता है। |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | निर्दिष्ट [XmlReader](../../system.xml/xmlreader/) ऑब्जेक्ट की XML सामग्री का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड नोड बनाता है। |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | निर्दिष्ट [XPathNavigator](./) ऑब्जेक्ट के नोड्स का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड नोड बनाता है। |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | निर्धारित मान के साथ नेमस्पेस उपसर्ग, स्थानीय नाम और नेमस्पेस URI का उपयोग करके वर्तमान नोड के चाइल्ड नोड्स की सूची की शुरुआत में नया चाइल्ड एलिमेंट बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | एक [XmlReader](../../system.xml/xmlreader/) ऑब्जेक्ट लौटाता है जिसमें वर्तमान नोड और उसके चाइल्ड नोड्स शामिल होते हैं। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की संदर्भ द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार के ऑब्जेक्ट की nullptr के साथ संदर्भ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | वर्तमान नोड से निर्दिष्ट नोड तक के सहोदर नोड्स की रेंज को बदलता है। |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | वर्तमान नोड को निर्दिष्ट स्ट्रिंग की सामग्री से बदलता है। |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | वर्तमान नोड को निर्दित [XmlReader](../../system.xml/xmlreader/) ऑब्जेक्ट की सामग्री से बदलता है। |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | वर्तमान नोड को निर्दित [XPathNavigator](./) ऑब्जेक्ट की सामग्री से बदलता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | निर्दिष्ट [XPath](../) अभिव्यक्ति का उपयोग करके एक नोड सेट चुनता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | निर्दिष्ट [XPath](../) अभिव्यक्ति और नेमस्पेस उपसर्ग हल करने के लिए निर्दिष्ट [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके एक नोड सेट चुनता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | निर्दिष्ट [XPathExpression](../xpathexpression/) का उपयोग करके एक नोड सेट चुनता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | वर्तमान नोड के सभी पूर्वज नोड्स को चुनता है जिनका XPathNodeType मेल खाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | वर्तमान नोड के सभी पूर्वज नोड्स को चुनता है जिनका स्थानीय नाम और नेमस्पेस URI निर्दिष्ट है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | वर्तमान नोड के सभी चाइल्ड नोड्स को चुनता है जिनका XPathNodeType मेल खाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | वर्तमान नोड के सभी चाइल्ड नोड्स को चुनता है जिनका स्थानीय नाम और नेमस्पेस URI निर्दिष्ट है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | वर्तमान नोड के सभी डाउनस्ट्रीम (वंशज) नोड्स को चुनता है जिनका XPathNodeType मेल खाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | वर्तमान नोड के सभी वंशज नोड्स को चुनता है जिनका स्थानीय नाम और नेमस्पेस URI निर्दिष्ट है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | निर्दिष्ट [XPath](../) क्वेरी का उपयोग करके [XPathNavigator](./) में एकल नोड चुनता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | निर्दिष्ट [XPath](../) क्वेरी और नेमस्पेस उपसर्ग हल करने के लिए निर्दिष्ट [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके [XPathNavigator](./) ऑब्जेक्ट में एकल नोड चुनता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | निर्दिष्ट [XPathExpression](../xpathexpression/) ऑब्जेक्ट का उपयोग करके [XPathNavigator](./) में एकल नोड चुनता है। |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | वर्तमान नोड के चाइल्ड नोड्स का प्रतिनिधित्व करने वाले मार्कअप को सेट करता है। |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | वर्तमान नोड और उसके चाइल्ड नोड्स के खुले और बंद टैग का प्रतिनिधित्व करने वाला मार्कअप सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्युमेंट को शैयर के बजाय वीक्स पॉइंटर सेट करता है। कंटेनर में पॉइंटर को वीक्स मोड में बदलने की अनुमति देता है। |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | वर्तमान नोड का टाइप्ड मान सेट करता है। |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | वर्तमान नोड का मान सेट करता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | वर्तमान नोड का टेक्स्ट मान लौटाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | निर्दिष्ट [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ऑब्जेक्ट का उपयोग करके नेमस्पेस उपसर्ग हल करने के साथ, वर्तमान नोड का मान निर्दिष्ट प्रकार के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | आइटम का मान निर्दिष्ट प्रकार के रूप में लौटाता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक्स रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक्स रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | वर्तमान नोड और उसके चाइल्ड नोड्स को निर्दिष्ट [XmlWriter](../../system.xml/xmlwriter/) ऑब्जेक्ट में स्ट्रीम करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस वर्ग की एक इंस्टेंस के साझा पॉइंटर का उपनाम। |

## संबंधित देखें

* कक्षा [XPathItem](../xpathitem/)
* कक्षा [IXPathNavigable](../ixpathnavigable/)
* कक्षा [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* नेमस्पेस [System::Xml::XPath](../)
* लाइब्रेरी [Aspose.Slides](../../)