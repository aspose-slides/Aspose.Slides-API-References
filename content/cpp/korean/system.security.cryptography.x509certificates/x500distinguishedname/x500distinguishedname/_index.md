---
title: X500DistinguishedName()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자.
type: docs
weight: 1
url: /ko/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 구별 이름을 나타내는 [Object](../../../system/object/). |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 인코딩된 구별 이름. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 구별 이름. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor

복사 생성자.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | 데이터를 복사할 구별 이름. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor

생성자.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 구별 이름. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | 이름 구성 속성을 지정하는 비트 단위 결합 플래그. |

## 참고

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)