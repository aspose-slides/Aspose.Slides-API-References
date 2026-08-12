---
title: ResolveVariable()
second_title: Aspose.Slides for C++ API संदर्भ
description: जब डेराइव्ड क्लास में ओवरराइड किया जाता है, तो यह एक वेरिएबल रेफ़रेंस को हल करता है और एक IXsltContextVariable लौटाता है जो वेरिएबल का प्रतिनिधित्व करता है।
type: docs
weight: 14
url: /hi/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) विधि

जब किसी डेराइव्ड क्लास में ओवरराइड किया जाता है, तो यह एक वेरिएबल रेफ़रेंस को हल करता है और एक [IXsltContextVariable](../../ixsltcontextvariable/) लौटाता है जो वेरिएबल का प्रतिनिधित्व करता है।

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | वेरिएबल का प्रीफ़िक्स जैसा कि [XPath](../../../system.xml.xpath/) अभिव्यक्ति में दिखाई देता है। |
| name | [String](../../../system/string/) | वेरिएबल का नाम। |

## वापसी मान

एक [IXsltContextVariable](../../ixsltcontextvariable/) जो रनटाइम पर वेरिएबल का प्रतिनिधित्व करता है।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IXsltContextVariable](../../ixsltcontextvariable/)
* क्लास [String](../../../system/string/)
* क्लास [XsltContext](../)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)