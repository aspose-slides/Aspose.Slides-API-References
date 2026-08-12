---
title: GetCredential()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट URI और प्रमाणिकरण प्रकार के लिए क्रेडेंशियल्स लौटाता है।
type: docs
weight: 1
url: /hi/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) विधि

निर्दिष्ट URI और प्रमाणिकरण प्रकार के लिए क्रेडेंशियल्स लौटाता है।

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | जिस URI के लिए क्लाइंट द्वारा प्रमाणिकरण प्रकार प्रदान किया जाता है। |
| authType | [String](../../../system/string/) | प्रमाणिकरण प्रकार। |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [NetworkCredential](../../networkcredential/)
* क्लास [Uri](../../../system/uri/)
* क्लास [String](../../../system/string/)
* क्लास [ICredentials](../)
* नामस्थान [System::Net](../../)
* Library [Aspose.Slides](../../../)