---
title: Write()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 래핑 모드가 바이너리인 경우, 지정된 바이트 배열의 지정된 서브렌지를 스트림에 기록하고, 그렇지 않은 경우 지정된 바이트 배열의 지정된 서브렌지를 char_type 타입으로 변환한 뒤 결과를 스트림에 기록합니다. 지원되지 않음!
type: docs
weight: 79
url: /ko/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

바이너리 래핑 모드인 경우 지정된 바이트 배열의 지정된 서브렌지를 스트림에 기록하고, 그렇지 않은 경우 지정된 바이트 배열의 지정된 서브렌지를 `char_type` 형식으로 변환한 뒤 결과를 스트림에 기록합니다. 지원되지 않음!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기 위한 바이트를 포함하는 배열. |
| offset | **int32_t** | 쓰기 서브렌지가 시작되는 **buffer** 내의 0 기반 인덱스. |
| count | **int32_t** | 쓰기 서브렌지에 포함된 요소의 수. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

지정된 바이트 배열의 지정된 서브렌지를 스트림에 기록합니다.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기 위한 바이트를 포함하는 배열 뷰 |
| offset | **int32_t** | 쓰기 서브렌지가 시작되는 **buffer** 내의 0 기반 인덱스 |
| count | **int32_t** | 쓰기 서브렌지에 포함된 요소의 수 |

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)