---
title: SignData()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산하고, 결과에 서명합니다.
type: docs
weight: 79
url: /ko/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) 메서드

지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산하고, 결과에 서명합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 입력 데이터 배열. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 입력 데이터에 대한 [DSA](../) 서명을 반환합니다. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) 메서드

지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산하고, 결과에 서명합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 입력 데이터 배열. |
| offset | **int32_t** | **data** 의 오프셋. |
| count | **int32_t** | 입력 데이터로 사용할 바이트 수. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 입력 데이터에 대한 [DSA](../) 서명을 반환합니다. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) 메서드

지정된 해시 알고리즘을 사용하여 지정된 바이너리 스트림의 해시 값을 계산하고, 결과에 서명합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 바이너리 스트림. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. 입력 데이터에 대한 [DSA](../) 서명을 반환합니다. |

## 참조

* 타입정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 타입정의 [StreamPtr](../../../system/streamptr/)
* 클래스 [DSA](../)
* 구조체 [HashAlgorithmName](../../hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)