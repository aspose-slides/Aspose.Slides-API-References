---
title: PublicKey()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자.
type: docs
weight: 1
url: /ko/system.security.cryptography.x509certificates/publickey/publickey/
---
## PublicKey::PublicKey(const SharedPtr\<Oid\>\&, const SharedPtr\<AsnEncodedData\>\&, const SharedPtr\<AsnEncodedData\>) 생성자


생성자.

```cpp
System::Security::Cryptography::X509Certificates::PublicKey::PublicKey(const SharedPtr<Oid> &oid, const SharedPtr<AsnEncodedData> &parameters, const SharedPtr<AsnEncodedData> key_value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | 공개 키를 나타내는 식별자 객체. |
| parameters | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | ASN.1 인코딩된 공개 키 매개변수. |
| key_value | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\> | ASN.1 인코딩된 공개 키 값. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Oid](../../../system.security.cryptography/oid/)
* 클래스 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 클래스 [PublicKey](../)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../../)
* 라이브러리 [Aspose.Slides](../../../)