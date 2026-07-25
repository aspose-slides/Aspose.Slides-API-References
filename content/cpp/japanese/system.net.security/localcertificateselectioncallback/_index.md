---
title: LocalCertificateSelectionCallback
second_title: Aspose.Slides for C++ API リファレンス
description: ローカル SSL 証明書を選択するために使用されるユーザーデリゲートです。
type: docs
weight: 79
url: /ja/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef

ローカル SSL 証明書を選択するために使用されるユーザーデリゲートです。

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## 参照

* 名前空間 [System::Net::Security](../)
* ライブラリ [Aspose.Slides](../../)