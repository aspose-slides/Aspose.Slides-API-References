---
title: X509Extension()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자.
type: docs
weight: 1
url: /ko/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 인증서와 연관된 인코딩된 데이터. |
| critical | **bool** | 중요도 표시. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) 확장과 연관된 식별자. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인증서와 연관된 원시 데이터. |
| critical | **bool** | 중요도 표시. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) 확장과 연관된 식별자. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인증서와 연관된 원시 데이터. |
| critical | **bool** | 중요도 표시. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 클래스 [X509Extension](../)
* 클래스 [Oid](../../../system.security.cryptography/oid/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../../)
* 라이브러리 [Aspose.Slides](../../../)