---
title: HashData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산합니다.
type: docs
weight: 105
url: /ko/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) 메서드


지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/)를 해시합니다. |
| offset | **int32_t** | **data**의 오프셋. |
| count | **int32_t** | 해시할 바이트 수. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 해시 알고리즘. |

### 반환 값

해시된 데이터.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) 메서드


지정된 해시 알고리즘을 사용하여 지정된 바이너리 스트림의 해시 값을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | 해시할 바이너리 스트림. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 해시 알고리즘. |

### 반환 값

해시된 데이터.

## 또 보기

* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 타입 정의 [StreamPtr](../../../system/streamptr/)
* 클래스 [ECDsaBotan](../)
* 구조체 [HashAlgorithmName](../../hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)