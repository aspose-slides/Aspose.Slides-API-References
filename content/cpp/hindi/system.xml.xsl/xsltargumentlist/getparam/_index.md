---
title: GetParam()
second_title: Aspose.Slides for C++ API संदर्भ
description: नेमस्पेस क्वालिफ़ाइड नाम से संबंधित पैरामीटर लौटाता है।
type: docs
weight: 14
url: /hi/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String&, const String&) विधि

Returns the parameter associated with the namespace qualified name.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### आर्ग्यूमेंट

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | पैरामीटर का नाम। [XsltArgumentList](../) प्रमाणित नहीं करता कि पास किया गया नाम वैध स्थानीय नाम है; हालांकि, नाम **nullptr** नहीं हो सकता। |
| namespaceUri | const [String](../../../system/string/)\& | पैरामीटर से संबंधित नेमस्पेस URI। |

### रिटर्न मान

पैरामीटर ऑब्जेक्ट या **nullptr** यदि नहीं मिला।

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [String](../../../system/string/)
* क्लास [XsltArgumentList](../)
* नेमस्पेस [System::Xml::Xsl](../../)
* लाइब्रेरी [Aspose.Slides](../../../)