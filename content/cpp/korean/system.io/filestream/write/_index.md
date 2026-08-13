---
title: Write()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.
type: docs
weight: 248
url: /ko/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 기록할 바이트를 포함하는 배열입니다. |
| offset | **int32_t** | **buffer**에서 하위 범위 쓰기가 시작되는 0부터 시작하는 인덱스입니다. |
| count | **int32_t** | 쓰여질 하위 범위의 요소 개수입니다. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 기록할 바이트를 포함하는 배열 뷰입니다. |
| offset | **int32_t** | **buffer**에서 하위 범위 쓰기가 시작되는 0부터 시작하는 인덱스입니다. |
| count | **int32_t** | 쓰여질 하위 범위의 요소 개수입니다. |

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)