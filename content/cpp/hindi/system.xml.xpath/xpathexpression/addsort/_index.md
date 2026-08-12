---
title: AddSort()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट IComparer ऑब्जेक्ट के अनुसार XPath अभिव्यक्ति द्वारा चयनित नोड्स को क्रमबद्ध करता है।
type: docs
weight: 27
url: /hi/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) मेथड


जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो निर्दिष्ट IComparer ऑब्जेक्ट के अनुसार [XPath](../../) अभिव्यक्ति द्वारा चयनित नोड्स को क्रमबद्ध करता है।

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | क्रम कुंजी का प्रतिनिधित्व करने वाला एक ऑब्जेक्ट। यह नोड के **string** मान या एक [XPathExpression](../) ऑब्जेक्ट हो सकता है जिसमें संकलित [XPath](../../) अभिव्यक्ति हो। |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | एक IComparer ऑब्जेक्ट जो दो ऑब्जेक्ट्स की समानता के लिए विशिष्ट डेटा प्रकार तुलना प्रदान करता है। |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) मेथड


जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो प्रदान किए गए पैरामीटर के अनुसार [XPath](../../) अभिव्यक्ति द्वारा चयनित नोड्स को क्रमबद्ध करता है।

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | क्रम कुंजी का प्रतिनिधित्व करने वाला एक ऑब्जेक्ट। यह नोड के **string** मान या एक [XPathExpression](../) ऑब्जेक्ट हो सकता है जिसमें संकलित [XPath](../../) अभिव्यक्ति हो। |
| order | [XmlSortOrder](../../xmlsortorder/) | क्रम क्रम का संकेत देने वाला XmlSortOrder मान। |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | बड़े और छोटे अक्षरों के क्रम को निर्धारित करने वाला XmlCaseOrder मान। |
| lang | [String](../../../system/string/) | तुलना के लिए उपयोग की जाने वाली भाषा। यह [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) वर्ग का उपयोग करता है जिसे [String::Compare](../../../system/string/compare/) मेथड को भाषा प्रकारों के लिए पास किया जा सकता है, उदाहरण के लिए, "us-en" U.S. English के लिए। यदि एक खाली स्ट्रिंग निर्दिष्ट की गई है, तो सिस्टम पर्यावरण का उपयोग [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) निर्धारित करने के लिए किया जाता है। |
| dataType | [XmlDataType](../../xmldatatype/) | डेटा प्रकार के क्रम को दर्शाने वाला XmlDataType मान। |

## देखें

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)