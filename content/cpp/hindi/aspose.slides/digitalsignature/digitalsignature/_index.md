---
title: DigitalSignature()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट प्रमाणपत्र के साथ एक नया DigitalSignature ऑब्जेक्ट बनाता है।
type: docs
weight: 66
url: /hi/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) कन्स्ट्रक्टर

निर्दिष्ट प्रमाणपत्र के साथ एक नया [DigitalSignature](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | प्रेजेंटेशन पर हस्ताक्षर करने के लिए उपयोग किया जाने वाला प्रमाणपत्र। |

## DigitalSignature::DigitalSignature(System::String, System::String) कन्स्ट्रक्टर

निर्दिष्ट प्रमाणपत्र फ़ाइल पथ और पासवर्ड के साथ एक नया [DigitalSignature](../) ऑब्जेक्ट बनाता है।

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | प्रमाणपत्र वाली फ़ाइल का पथ। |
| password | [System::String](../../../system/string/) | प्रमाणपत्र तक पहुँचने के लिए आवश्यक पासवर्ड। |

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* क्लास [DigitalSignature](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)