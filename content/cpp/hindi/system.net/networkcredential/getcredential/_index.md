---
title: GetCredential()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट URI और प्रमाणन प्रकार के लिए प्रमाणपत्र लौटाता है।
type: docs
weight: 92
url: /hi/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) विधि


निर्दिष्ट URI और प्रमाणन प्रकार के लिए प्रमाणपत्र लौटाता है।

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI। |
| authenticationType | [String](../../../system/string/) | प्रमाणन प्रकार। |

## NetworkCredential::GetCredential(String, int32_t, String) विधि


निर्दिष्ट होस्ट नाम, पोर्ट और प्रमाणन प्रकार के लिए प्रमाणपत्र लौटाता है।

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| host | [String](../../../system/string/) | होस्ट नाम। |
| port | **int32_t** | पोर्ट संख्या। |
| authenticationType | [String](../../../system/string/) | प्रमाणन प्रकार। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [NetworkCredential](../)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Net](../../)
* लाइब्रेरी [Aspose.Slides](../../../)