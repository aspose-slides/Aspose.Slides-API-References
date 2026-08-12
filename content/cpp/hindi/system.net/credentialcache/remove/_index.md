---
title: Remove()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट URI उपसर्ग और प्रमाणीकरण प्रकार के लिए नेटवर्क प्रमाण-पत्रों को हटाता है।
type: docs
weight: 53
url: /hi/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) विधि

निर्दिष्ट URI उपसर्ग और प्रमाणीकरण प्रकार के लिए नेटवर्क प्रमाण-पत्रों को हटाता है।

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI उपसर्ग। |
| authenticationType | [String](../../../system/string/) | प्रमाणीकरण प्रकार। |

## CredentialCache::Remove(String, int32_t, String) विधि

निर्दिष्ट होस्ट नाम, पोर्ट और प्रमाणीकरण प्रकार के लिए नेटवर्क प्रमाण-पत्रों को हटाता है।

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | [String](../../../system/string/) | क्रेडेंशियल्स से जुड़ा होस्ट नाम। |
| port | **int32_t** | पोर्ट संख्या। |
| authenticationType | [String](../../../system/string/) | एक प्रमाणीकरण प्रकार। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [CredentialCache](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)