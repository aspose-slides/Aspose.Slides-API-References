---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 기록합니다.
type: docs
weight: 27
url: /ko/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 기록합니다.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 |
| offset | **int32_t** | 쓰기 시작 위치인 **buffer**의 0 기반 위치 |
| count | **int32_t** | 읽어야 할 바이트 수 |

### 반환값

읽은 바이트 수

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 기록합니다.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 뷰 |
| offset | **int32_t** | 쓰기 시작 위치인 **buffer**의 0 기반 위치 |
| count | **int32_t** | 읽어야 할 바이트 수 |

### 반환값

읽은 바이트 수

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| N | 스택 배열의 크기 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | 읽은 바이트를 기록할 바이트 스택 배열 |
| offset | **int32_t** | 쓰기 시작 위치인 **buffer**의 0 기반 위치 |
| count | **int32_t** | 읽어야 할 바이트 수 |

### 반환값

읽은 바이트 수

## Stream::Read(const System::Span\<uint8_t\>\&) 메서드

스트림에서 지정된 바이트 수를 읽고 지정된 바이트 스팬에 기록합니다.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 스팬 |

### 반환값

읽은 바이트 수

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Stream](../)
* 클래스 [Span](../../../system/span/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)