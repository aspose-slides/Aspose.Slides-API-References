---
title: GetCertHashString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체에 대한 SHA1 해시를 16진수 문자열로 가져옵니다.
type: docs
weight: 92
url: /ko/system.security.cryptography.x509certificates/x509certificate/getcerthashstring/
---
## X509Certificate::GetCertHashString() const 메서드

Gets [SHA1](../../../system.security.cryptography/sha1/) 해시를 16진수 문자열로 가져옵니다.

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString() const
```

### 반환값

16진수 문자열.

## X509Certificate::GetCertHashString(const HashAlgorithmName\&) const 메서드

Gets [SHA1](../../../system.security.cryptography/sha1/) 해시를 16진수 문자열로 가져옵니다.

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString(const HashAlgorithmName &hash_algorithm) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | 해시 알고리즘 이름. |

### 반환값

16진수 문자열.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [X509Certificate](../)
* 구조체 [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../../)
* 라이브러리 [Aspose.Slides](../../../)