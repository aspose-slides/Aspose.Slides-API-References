---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक संग्रह लौटाता है जिसमें वर्तमान में स्कोप में सभी नेमस्पेस शामिल होते हैं।
type: docs
weight: 716
url: /hi/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) विधि

एक संग्रह लौटाता है जिसमें वर्तमान में स्कोप में सभी नेमस्पेस शामिल हैं।

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | एक XmlNamespaceScope मान जो लौटाने के लिए नेमस्पेस नोड्स के प्रकार को निर्दिष्ट करता है। |

### वापसी मान

एक IDictionary ऑब्जेक्ट जो सभी वर्तमान इन-स्कोप नेमस्पेस को सम्मिलित करता है। यदि रीडर किसी तत्व पर स्थित नहीं है, तो एक खाली शब्दकोश (कोई नेमस्पेस नहीं) लौटाया जाता है।

## देखें

* एन्यूम [XmlNamespaceScope](../../xmlnamespacescope/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDictionary](../../../system.collections.generic/idictionary/)
* क्लास [String](../../../system/string/)
* क्लास [XmlTextReader](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)