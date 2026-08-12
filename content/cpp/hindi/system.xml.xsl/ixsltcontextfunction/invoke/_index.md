---
title: Invoke()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्धारित संदर्भ में दिए गए तर्कों के साथ फ़ंक्शन को कॉल करने के लिए विधि प्रदान करता है।
type: docs
weight: 53
url: /hi/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method


फ़ंक्शन को दिए गए तर्कों के साथ निर्दिष्ट संदर्भ में बुलाने के लिए यह विधि प्रदान की गई है।

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | फ़ंक्शन कॉल के लिए XSLT संदर्भ। |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | फ़ंक्शन कॉल के तर्क। प्रत्येक तर्क सरणी में एक तत्व है। |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | फ़ंक्शन कॉल के लिए संदर्भ नोड। |

### रिटर्न मान

[Object](../../../system/object/) जो फ़ंक्शन के रिटर्न मान को दर्शाता है।

## संबंधित

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [Object](../../../system/object/)
* क्लास [XsltContext](../../xsltcontext/)
* क्लास [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* क्लास [IXsltContextFunction](../)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)