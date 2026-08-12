---
title: get_ArgTypes()
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़ंक्शन की तर्क सूची के लिए प्रदान किए गए XML Path Language (XPath) प्रकार लौटाता है। इस जानकारी का उपयोग फ़ंक्शन की सिग्नेचर खोजने के लिए किया जा सकता है, जिससे ओवरलोडेड फ़ंक्शन के बीच अंतर किया जा सके।
type: docs
weight: 40
url: /hi/system.xml.xsl/ixsltcontextfunction/get_argtypes/
---
## IXsltContextFunction::get_ArgTypes() विधि


Returns the supplied XML Path Language ([XPath](../../../system.xml.xpath/)) types for the function's argument list. This information can be used to discover the signature of the function which allows you to differentiate between overloaded functions.

```cpp
virtual ArrayPtr<System::Xml::XPath::XPathResultType> System::Xml::Xsl::IXsltContextFunction::get_ArgTypes()=0
```


### रिटर्न वैल्यू

An array of XPathResultType representing the types for the function's argument list.

## देखें

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)