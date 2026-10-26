---
title: Write()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 바이트 배열을 스트림에 씁니다.
type: docs
weight: 404
url: /ko/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) 메서드

지정된 바이트 배열을 스트림에 씁니다.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기 위한 바이트 배열입니다. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기 위한 바이트를 포함하는 배열 |
| offset | **int32_t** | **buffer**에서 쓰기 하위 범위가 시작되는 요소의 0부터 시작하는 인덱스 |
| count | **int32_t** | 쓰기 하위 범위의 요소 수 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) 메서드

지정된 바이트 배열을 스트림에 씁니다.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기 위한 바이트 배열입니다. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기 위한 바이트를 포함하는 배열 |
| offset | **int32_t** | **buffer**에서 쓰기 하위 범위가 시작되는 요소의 0부터 시작하는 인덱스 |
| count | **int32_t** | 쓰기 하위 범위의 요소 수 |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)