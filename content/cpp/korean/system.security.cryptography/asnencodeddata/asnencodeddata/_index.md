---
title: AsnEncodedData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 복사 생성자.
type: docs
weight: 1
url: /ko/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) 생성자

복사 생성자.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) 복사할 데이터. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) 생성자

생성자.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 원시 바이트 형식의 인코딩된 데이터. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) 생성자

생성자.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) 인코딩된 데이터 식별자. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 원시 바이트 형식의 인코딩된 데이터. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) 생성자

생성자.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) 인코딩된 데이터 식별자. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 원시 바이트 형식의 인코딩된 데이터. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [AsnEncodedData](../)
* 클래스 [Oid](../../oid/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)