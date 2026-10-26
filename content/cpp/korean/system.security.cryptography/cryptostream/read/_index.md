---
title: Read()
second_title: Aspose.Slides for C++ API 참조
description: 스트림에서 데이터를 읽습니다.
type: docs
weight: 14
url: /ko/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 데이터를 읽습니다.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 대상 데이터 버퍼. |
| offset | **int32_t** | 대상 버퍼의 오프셋. |
| count | **int32_t** | 읽을 바이트 수. |

### 반환 값

실제로 읽힌 바이트 수.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 데이터를 읽습니다.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 대상 데이터 버퍼. |
| offset | **int32_t** | 대상 버퍼의 오프셋. |
| count | **int32_t** | 읽을 바이트 수. |

### 반환 값

실제로 읽힌 바이트 수.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)