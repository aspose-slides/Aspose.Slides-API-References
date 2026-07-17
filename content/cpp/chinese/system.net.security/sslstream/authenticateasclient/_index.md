---
title: AuthenticateAsClient()
second_title: Aspose.Slides C++ API 参考
description: 对连接的客户端进行身份验证。
type: docs
weight: 339
url: /zh/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) 方法

对连接的客户端进行身份验证。

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 与当前实例共享的服务器名称。 |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) 方法

对连接的客户端进行身份验证。

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 与当前实例共享的服务器名称。 |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | 客户端证书。 |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | 用于身份验证的 SSL 协议。 |
| checkCertificateRevocation | **bool** | 指示在身份验证期间是否必须检查证书吊销列表的值。 |

## 另请参见

* 枚举 [SslProtocols](../../../system.security.authentication/sslprotocols/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [SslStream](../)
* 类 [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* 命名空间 [System::Net::Security](../../)
* 库 [Aspose.Slides](../../../)