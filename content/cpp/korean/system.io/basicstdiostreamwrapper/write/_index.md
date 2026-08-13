---
title: Write()
second_title: Aspose.Slides for C++ API 참조
description: 래핑 모드가 바이너리인 경우, 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다. 그렇지 않은 경우, 지정된 바이트 배열에서 지정된 바이트 하위 범위를 char_type 형식으로 변환한 다음 결과를 스트림에 씁니다.
type: docs
weight: 79
url: /ko/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드


If wrapping mode is binary, writes to the stream the specified subrange of bytes from the specified byte array, otherwise convert the specified subrange of bytes from the specified byte array to char_type type ant then writes result to the stream.

래핑 모드가 바이너리인 경우, 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다. 그렇지 않은 경우, 지정된 바이트 배열에서 지정된 바이트 하위 범위를 char_type 형식으로 변환한 다음 결과를 스트림에 씁니다.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기에 사용할 바이트를 포함하는 배열 |
| offset | **int32_t** | 쓰기를 시작하는 **buffer** 안의 요소에 대한 0 기반 인덱스 |
| count | **int32_t** | 쓰여질 하위 범위의 요소 개수 |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드


Writes the specified subrange of bytes from the specified byte array to the stream.

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기에 사용할 바이트를 포함하는 배열 뷰 |
| offset | **int32_t** | 쓰기를 시작하는 **buffer** 안의 요소에 대한 0 기반 인덱스 |
| count | **int32_t** | 쓰여질 하위 범위의 요소 개수 |

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [BasicSTDIOStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)