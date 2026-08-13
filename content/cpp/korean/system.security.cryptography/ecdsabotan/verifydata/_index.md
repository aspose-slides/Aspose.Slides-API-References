---
title: VerifyData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 데이터의 서명이 유효한지 확인합니다.
type: docs
weight: 170
url: /ko/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method

지정된 데이터의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) method

지정된 데이터의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| offset | **int32_t** | **data** 내 오프셋. |
| count | **int32_t** | 해시할 바이트 수. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) method

지정된 바이너리 스트림의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

지정된 데이터의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

지정된 데이터의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명된 데이터. |
| offset | **int32_t** | **data** 내 오프셋. |
| count | **int32_t** | 해시할 바이트 수. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

지정된 바이너리 스트림의 서명이 유효한지 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 서명된 데이터. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 클래스 [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)