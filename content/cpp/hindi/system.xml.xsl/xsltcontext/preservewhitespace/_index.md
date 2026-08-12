---
title: PreserveWhitespace()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब डेराइव्ड क्लास में ओवरराइड किया जाता है, तो यह निर्धारित करता है कि दिए गए कॉन्टेक्स्ट के लिए खाली स्थान नोड्स को संरक्षित किया जाए या हटाया जाए।
type: docs
weight: 40
url: /hi/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) मेथड


जब डेराइव्ड क्लास में ओवरराइड किया जाता है, तो यह निर्धारित करता है कि दिए गए कॉन्टेक्स्ट के लिए खाली स्थान नोड्स को संरक्षित किया जाए या उन्हें हटाया जाए।

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | वर्तमान कॉन्टेक्स्ट में जिसे संरक्षित या हटाया जाना है वह खाली स्थान नोड। |

### वापसी मान

**true** यदि खाली स्थान को संरक्षित किया जाना है; **false** यदि खाली स्थान को हटाया जाना है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* क्लास [XsltContext](../)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)