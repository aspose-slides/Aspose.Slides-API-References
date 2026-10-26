---
title: GetCredential()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट होस्ट और प्रमाणिकरण प्रकार के लिए क्रेडेंशियल लौटाता है।
type: docs
weight: 1
url: /hi/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) विधि

निर्दिष्ट होस्ट और प्रमाणिकरण प्रकार के लिए क्रेडेंशियल लौटाता है।

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | [String](../../../system/string/) | क्लाइंट को प्रमाणीकरण करने वाला होस्ट। |
| port | **int32_t** | होस्ट पोर्ट नंबर। |
| authenticationType | [String](../../../system/string/) | प्रमाणिकरण प्रकार। |

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [NetworkCredential](../../networkcredential/)
* क्लास [String](../../../system/string/)
* क्लास [ICredentialsByHost](../)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)