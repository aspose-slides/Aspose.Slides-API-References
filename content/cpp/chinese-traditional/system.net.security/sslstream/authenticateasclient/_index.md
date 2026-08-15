---
title: AuthenticateAsClient()
second_title: Aspose.Slides C++ API 參考
description: 驗證連線的客戶端。
type: docs
weight: 339
url: /zh-hant/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) 方法


驗證連線的客戶端。

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 共享目前實例的伺服器名稱。 |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) 方法


驗證連線的客戶端。

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 共享目前實例的伺服器名稱。 |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | 客戶端憑證。 |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | 用於驗證的 SSL 協議。 |
| checkCertificateRevocation | **bool** | 指示在驗證期間是否必須檢查憑證撤銷清單的值。 |

## 另請參閱

* 列舉 [SslProtocols](../../../system.security.authentication/sslprotocols/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [SslStream](../)
* 類別 [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* 命名空間 [System::Net::Security](../../)
* 函式庫 [Aspose.Slides](../../../)