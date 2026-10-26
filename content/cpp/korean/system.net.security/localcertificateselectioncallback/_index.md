---
title: LocalCertificateSelectionCallback
second_title: Aspose.Slides for C++ API 레퍼런스
description: 로컬 SSL 인증서를 선택하는 데 사용되는 사용자 대리자입니다.
type: docs
weight: 79
url: /ko/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef


로컬 SSL 인증서를 선택하는 데 사용되는 사용자 대리자입니다.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## 참조

* 네임스페이스 [System::Net::Security](../)
* 라이브러리 [Aspose.Slides](../../)