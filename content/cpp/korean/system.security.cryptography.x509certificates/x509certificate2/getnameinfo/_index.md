---
title: GetNameInfo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 인증서에서 주체 또는 발급자 이름을 가져옵니다.
type: docs
weight: 248
url: /ko/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const 메서드

인증서에서 주체 또는 발급자 이름을 가져옵니다.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | 이름 형식 옵션. |
| for_issuer | **bool** | true인 경우 발급자 이름을 반환하고, 그렇지 않으면 주체 이름을 반환합니다. |

### 반환값

형식이 지정된 발급자 또는 주체 이름.

## 참조

* Enum [X509NameType](../../x509nametype/)
* 클래스 [String](../../../system/string/)
* 클래스 [X509Certificate2](../)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)