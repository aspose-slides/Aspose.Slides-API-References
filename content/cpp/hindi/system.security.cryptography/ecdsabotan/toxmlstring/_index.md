---
title: ToXmlString()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: सभी पैरामीटर को XML फ़ॉर्मेट में निर्यात करता है। लागू नहीं किया गया है।
type: docs
weight: 157
url: /hi/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) विधि

सभी पैरामीटर को XML फ़ॉर्मेट में निर्यात करता है। लागू नहीं किया गया है।

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| include_private_parameters | **bool** | यदि true है तो निजी और सार्वजनिक दोनों पैरामीटर निर्यात करता है, यदि false है तो केवल सार्वजनिक पैरामीटर निर्यात करता है। |

### रिटर्न वैल्यू

XML-एन्कोडेड पैरामीटर।

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) विधि

सभी पैरामीटर को XML फ़ॉर्मेट में निर्यात करता है।

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | परिणामी XML स्ट्रिंग का फ़ॉर्मेट। |

### रिटर्न वैल्यू

XML-एन्कोडेड पैरामीटर।

## संबंधित देखें

* एन्यूम [ECKeyXmlFormat](../../eckeyxmlformat/)
* क्लास [String](../../../system/string/)
* क्लास [ECDsaBotan](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)