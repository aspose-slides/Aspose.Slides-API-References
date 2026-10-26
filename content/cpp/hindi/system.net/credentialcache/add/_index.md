---
title: Add()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट नेटवर्क क्रेडेंशियल्स को कैश में जोड़ता है।
type: docs
weight: 40
url: /hi/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) विधि

निर्दिष्ट नेटवर्क क्रेडेंशियल्स को कैश में जोड़ता है।

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | उस संसाधन का URI प्रीफ़िक्स जिसके साथ क्रेडेंशियल्स संबद्ध हैं। |
| authenticationType | [String](../../../system/string/) | प्रमाणीकरण योजना। |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | जोड़ने के लिए क्रेडेंशियल्स। |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) विधि

निर्दिष्ट नेटवर्क क्रेडेंशियल्स को कैश में जोड़ता है।

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | होस्ट नाम जिसके साथ क्रेडेंशियल्स संबद्ध हैं। |
| port | **int32_t** | पोर्ट नंबर। |
| authenticationType | [String](../../../system/string/) | प्रमाणीकरण योजना। |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | जोड़ने के लिए क्रेडेंशियल्स। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [NetworkCredential](../../networkcredential/)
* क्लास [CredentialCache](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)