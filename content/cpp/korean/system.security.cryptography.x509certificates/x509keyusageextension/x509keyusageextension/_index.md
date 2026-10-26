---
title: X509KeyUsageExtension()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 생성자.
type: docs
weight: 1
url: /ko/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() 생성자

기본 생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 키 사용에 대한 인코딩된 데이터. |
| critical | **bool** | 중요도 표시. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) 생성자

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | 키 사용. |
| critical | **bool** | 중요도 표시. |

## 참조

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509KeyUsageExtension](../)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)