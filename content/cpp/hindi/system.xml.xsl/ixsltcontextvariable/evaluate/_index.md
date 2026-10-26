---
title: Evaluate()
second_title: Aspose.Slides for C++ API संदर्भ
description: रनटाइम पर वैरिएबल का मूल्यांकन करता है और एक ऑब्जेक्ट लौटाता है जो वैरिएबल के मान का प्रतिनिधित्व करता है।
type: docs
weight: 40
url: /hi/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) method


रनटाइम पर वैरिएबल का मूल्यांकन करता है और एक ऑब्जेक्ट लौटाता है जो वैरिएबल के मान का प्रतिनिधित्व करता है।

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | एक [XsltContext](../../xsltcontext/) जो वैरिएबल के निष्पादन संदर्भ का प्रतिनिधित्व करता है। |

### रिटर्न वैल्यू

एक [Object](../../../system/object/) जो वैरिएबल के मान का प्रतिनिधित्व करता है। संभावित रिटर्न प्रकारों में number, string, [Boolean](../../../system/boolean/), document fragment, या node set शामिल हैं।

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Class [IXsltContextVariable](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)