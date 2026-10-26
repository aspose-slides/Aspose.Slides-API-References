---
title: AuthenticateAsClient()
second_title: Aspose.Slides for C++ API 참조
description: 연결의 클라이언트 측을 인증합니다.
type: docs
weight: 339
url: /ko/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) 메서드


연결의 클라이언트 측을 인증합니다.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 현재 인스턴스를 공유하는 서버의 이름입니다. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) 메서드


연결의 클라이언트 측을 인증합니다.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | 현재 인스턴스를 공유하는 서버의 이름입니다. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | 클라이언트 인증서입니다. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | 인증에 사용되는 SSL 프로토콜입니다. |
| checkCertificateRevocation | **bool** | 인증 중에 인증서 폐기 목록을 확인해야 하는지를 나타내는 값입니다. |

## 참고

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [SslStream](../)
* 클래스 [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* 네임스페이스 [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)