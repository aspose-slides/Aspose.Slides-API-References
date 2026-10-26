---
title: WriteNode()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह रीडर से राइटर तक सब कुछ कॉपी करता है और रीडर को अगले सिब्लिंग की शुरुआत में ले जाता है।
type: docs
weight: 430
url: /hi/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) विधि


जब एक व्युत्पन्न वर्ग में ओवरराइड किया जाता है, तो यह रीडर से राइटर तक सब कुछ कॉपी करता है और रीडर को अगले सिब्लिंग की शुरुआत में ले जाता है।

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | पढ़ने के लिए [XmlReader](../../xmlreader/)। |
| defattr | **bool** | **true** डिफ़ॉल्ट एट्रीब्यूट्स को [XmlReader](../../xmlreader/) से कॉपी करने के लिये; अन्यथा, **false**। |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) विधि


XPathNavigator ऑब्जेक्ट से राइटर तक सब कुछ कॉपी करता है। XPathNavigator की स्थिति अपरिवर्तित रहती है।

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | कॉपी करने के लिये XPathNavigator। |
| defattr | **bool** | **true** डिफ़ॉल्ट एट्रीब्यूट्स को कॉपी करने के लिये; अन्यथा, **false**। |

## संदर्भ देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XmlReader](../../xmlreader/)
* क्लास [XmlWriter](../)
* क्लास [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)