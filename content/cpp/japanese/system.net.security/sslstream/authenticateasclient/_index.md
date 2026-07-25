---
title: AuthenticateAsClient()
second_title: Aspose.Slides の C++ API リファレンス
description: 接続のクライアント側を認証します。
type: docs
weight: 339
url: /ja/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) メソッド

クライアント側の接続を認証します。

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 現在のインスタンスを共有するサーバーの名前。 |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) メソッド

クライアント側の接続を認証します。

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 現在のインスタンスを共有するサーバーの名前。 |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | クライアント証明書。 |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | 認証に使用される SSL プロトコル。 |
| checkCertificateRevocation | **bool** | 認証中に証明書失効リストをチェックすべきかを示す値。 |

## 参照

* 列挙型 [SslProtocols](../../../system.security.authentication/sslprotocols/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [SslStream](../)
* クラス [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* 名前空間 [System::Net::Security](../../)
* ライブラリ [Aspose.Slides](../../../)