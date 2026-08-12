---
title: GetCredential()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: निर्दिष्ट URI उपसर्ग और प्रमाणीकरण प्रकार के लिए क्रेडेंशियल्स लौटाता है।
type: docs
weight: 66
url: /hi/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) मेथड

निर्दिष्ट URI उपसर्ग और प्रमाणीकरण प्रकार के लिए क्रेडेंशियल्स लौटाता है।

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI उपसर्ग। |
| authenticationType | [String](../../../system/string/) | एक प्रमाणीकरण प्रकार। |

## CredentialCache::GetCredential(String, int32_t, String) मेथड

निर्दिष्ट होस्ट नाम, पोर्ट और प्रमाणीकरण प्रकार के लिए क्रेडेंशियल्स लौटाता है।

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | [String](../../../system/string/) | क्रेडेंशियल्स से जुड़ा होस्ट नाम। |
| port | **int32_t** | पोर्ट संख्या। |
| authenticationType | [String](../../../system/string/) | प्रमाणीकरण प्रकार। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [NetworkCredential](../../networkcredential/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [CredentialCache](../)
* नामस्थान [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)