---
title: ToString()
second_title: Aspose.Slides for C++ API संदर्भ
description: XmlQualifiedName का स्ट्रिंग मान लौटाता है।
type: docs
weight: 79
url: /hi/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const मेथड

[XmlQualifiedName](../) का स्ट्रिंग मान लौटाता है।

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### रिटर्न वैल्यू

[XmlQualifiedName](../) का स्ट्रिंग मान **namespace:localname** फॉर्मेट में है। यदि ऑब्जेक्ट का नेमस्पेस परिभाषित नहीं है, तो यह मेथड केवल स्थानीय नाम लौटाता है।

## XmlQualifiedName::ToString(const String\&, const String\&) मेथड

[XmlQualifiedName](../) का स्ट्रिंग मान लौटाता है।

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ऑब्जेक्ट का नाम। |
| ns | const [String](../../../system/string/)\& | ऑब्जेक्ट का नेमस्पेस। |

### रिटर्न वैल्यू

[XmlQualifiedName](../) का स्ट्रिंग मान **namespace:localname** फॉर्मेट में है। यदि ऑब्जेक्ट का नेमस्पेस परिभाषित नहीं है, तो यह मेथड केवल स्थानीय नाम लौटाता है।

## देखिए

* क्लास [String](../../../system/string/)
* क्लास [XmlQualifiedName](../)
* नेमस्पेस [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)