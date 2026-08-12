---
title: get_Current()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह इस XPathNodeIterator के लिए XPathNavigator ऑब्जेक्ट प्राप्त करता है, जो वर्तमान कॉन्टेक्स्ट नोड पर स्थित होता है।
type: docs
weight: 1
url: /hi/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() मेथड

जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह [XPathNodeIterator](../) के लिए [XPathNavigator](../../xpathnavigator/) ऑब्जेक्ट प्राप्त करता है, जो वर्तमान संदर्भ नोड पर स्थित होता है।

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### रिटर्न वैल्यू

एक [XPathNavigator](../../xpathnavigator/) ऑब्जेक्ट जो उस कॉन्टेक्स्ट नोड पर स्थित है जिससे नोड सेट चयनित किया गया था। [XPathNodeIterator::MoveNext](../movenext/) मेथड को कॉल किया जाना चाहिए ताकि [XPathNodeIterator](../) को चयनित सेट के पहले नोड पर ले जाया जा सके।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [XPathNavigator](../../xpathnavigator/)
* क्लास [XPathNodeIterator](../)
* नामस्थान [System::Xml::XPath](../../)
* लाइब्रेरी [Aspose.Slides](../../../)