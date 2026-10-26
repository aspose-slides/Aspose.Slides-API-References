---
title: VerifyData()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 데이터의 서명이 유효한지 확인합니다.
type: docs
weight: 105
url: /ko/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 메서드

지정된 데이터의 서명이 유효함을 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) 메서드

지정된 데이터의 서명이 유효함을 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| offset | **int32_t** | **data**의 오프셋. |
| count | **int32_t** | 해시할 바이트 수. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 메서드

지정된 이진 스트림의 서명이 유효함을 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## 또 보기

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 클래스 [ECDsa](../)
* 구조체 [HashAlgorithmName](../../hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)