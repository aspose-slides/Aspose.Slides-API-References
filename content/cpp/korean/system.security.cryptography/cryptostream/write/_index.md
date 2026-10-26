---
title: Write()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에 데이터를 씁니다.
type: docs
weight: 27
url: /ko/system.security.cryptography/cryptostream/write/
---
## CryptoStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에 데이터를 씁니다.

```cpp
void System::Security::Cryptography::CryptoStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 소스 데이터 버퍼. |
| offset | **int32_t** | 소스 버퍼의 오프셋. |
| count | **int32_t** | 쓰기 위한 바이트 수. |

## CryptoStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에 데이터를 씁니다.

```cpp
void System::Security::Cryptography::CryptoStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 소스 데이터 버퍼. |
| offset | **int32_t** | 소스 버퍼의 오프셋. |
| count | **int32_t** | 쓰기 위한 바이트 수. |

## 참고

* typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [CryptoStream](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)