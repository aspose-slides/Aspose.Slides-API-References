---
title: SecurityPermissionFlag
second_title: Aspose.Slides for C++ API संदर्भ
description: सुरक्षा अनुमति के फ़्लैग।
type: docs
weight: 27
url: /hi/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

सुरक्षा अनुमति के फ़्लैग।

```cpp
enum class SecurityPermissionFlag
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| NoFlags | 0 | कोई पहुंच नहीं। |
| Assertion | 1 | सत्यापित करें कि अनुमति दी गई है। |
| UnmanagedCode | 2 | अनप्रबंधित कोड को कॉल करें। |
| SkipVerification | 4 | कोड सत्यापन को छोड़ें। |
| Execution | 8 | कोड को निष्पादित करें। |
| ControlThread | 16 | थ्रेड्स पर संचालन करें। |
| ControlEvidence | 32 | CLR साक्ष्य को नियंत्रित या बदलें। |
| ControlPolicy | 64 | नीति देखें और बदलें। |
| SerializationFormatter | 128 | क्रमबद्ध करें। |
| ControlDomainPolicy | 256 | डोमेन नीति सेट करें। |
| ControlPrincipal | 512 | प्रमुख ऑब्जेक्ट को नियंत्रित करें। |
| ControlAppDomain | 1024 | एप्लिकेशन डोमेन को नियंत्रित करें। |
| RemotingConfiguration | 2048 | रीमोटिंग को कॉन्फ़िगर करें। |
| Infrastructure | 4096 | CLR इन्फ्रास्ट्रक्चर में प्लग इन करें। |
| BindingRedirects | 8192 | स्पष्ट बाइंडिंग पुनःनिर्देशन करें। |
| AllFlags | 16383 | असीमित। |

## संबंधित देखें

* नामस्थान [System::Security::Permissions](../)
* लाइब्रेरी [Aspose.Slides](../../)