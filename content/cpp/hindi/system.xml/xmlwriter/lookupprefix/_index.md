---
title: LookupPrefix()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब व्युत्पन्न वर्ग में अधिलेखित किया जाता है, तो वर्तमान नामस्थान स्कोप में परिभाषित सबसे निकटतम उपसर्ग लौटाता है जो नामस्थान URI के लिए है।
type: docs
weight: 352
url: /hi/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) विधि

When overridden in a derived class, returns the closest prefix defined in the current namespace scope for the namespace URI.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ns | [String](../../../system/string/) | वह नामस्थान URI जिसका उपसर्ग आप खोजना चाहते हैं। |

### वापसी मान

मिलता हुआ उपसर्ग या **nullptr** यदि वर्तमान स्कोप में कोई मिलता हुआ नामस्थान URI नहीं मिला।

## संबंधित देखें

* कक्षा [String](../../../system/string/)
* कक्षा [XmlWriter](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)