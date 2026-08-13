---
title: Write()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.
type: docs
weight: 53
url: /ko/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기 위한 바이트를 포함하는 배열 |
| offset | **int32_t** | 쓰기 하위 범위가 시작되는 **buffer** 내 요소의 0 기반 인덱스 |
| count | **int32_t** | 쓰기 하위 범위의 요소 수 |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기 위한 바이트를 포함하는 배열 뷰 |
| offset | **int32_t** | 쓰기 하위 범위가 시작되는 **buffer** 내 요소의 0 기반 인덱스 |
| count | **int32_t** | 쓰기 하위 범위의 요소 수 |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) method

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| N | 스택 배열의 크기 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | 쓰기 위한 바이트를 포함하는 스택 배열 |
| offset | **int32_t** | 쓰기 하위 범위가 시작되는 **buffer** 내 요소의 0 기반 인덱스 |
| count | **int32_t** | 쓰기 하위 범위의 요소 수 |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) method

지정된 바이트 스팬에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | 작성된 바이트를 읽을 바이트 스팬 |

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)