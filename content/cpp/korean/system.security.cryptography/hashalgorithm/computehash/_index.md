---
title: ComputeHash()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 버퍼를 해시합니다.
type: docs
weight: 14
url: /ko/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) 메서드

버퍼를 해시합니다.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 소스 버퍼. |

### 반환값

계산된 해시 값.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) 메서드

버퍼 슬라이스를 해시합니다.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 소스 버퍼. |
| offset | int | 소스 버퍼의 오프셋. |
| count | int | 소스 버퍼에서 사용할 바이트 수. |

### 반환값

계산된 해시 값.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) 메서드

스트림을 끝까지 읽고 읽은 데이터의 해시를 계산합니다.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | 데이터를 읽을 스트림. |

### 반환값

전체 스트림 데이터에 대한 계산된 해시 값.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)