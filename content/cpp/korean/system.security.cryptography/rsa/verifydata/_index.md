---
title: VerifyData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 데이터의 서명이 유효한지 확인합니다.
type: docs
weight: 157
url: /ko/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 메서드

지정된 데이터의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 패딩 모드. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 메서드

지정된 데이터의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| offset | **int32_t** | **data**의 오프셋. |
| count | **int32_t** | 해시할 바이트 수. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 패딩 모드. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 메서드

지정된 바이너리 스트림의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 패딩 모드. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## 참고

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)