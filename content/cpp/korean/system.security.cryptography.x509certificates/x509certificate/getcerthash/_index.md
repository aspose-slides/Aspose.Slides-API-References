---
title: GetCertHash()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체의 해시를 바이트 배열로 가져옵니다.
type: docs
weight: 79
url: /ko/system.security.cryptography.x509certificates/x509certificate/getcerthash/
---
## X509Certificate::GetCertHash() const 메서드

현재 객체의 해시를 바이트 배열로 가져옵니다.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash() const
```

### 반환값

해시 값.

## X509Certificate::GetCertHash(const HashAlgorithmName\&) const 메서드

현재 객체의 해시를 바이트 배열로 가져옵니다.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash(const HashAlgorithmName &hash_algorithm) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | 해시 알고리즘 이름. |

### 반환값

해시 값.

## 관련 항목

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate](../)
* Struct [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)