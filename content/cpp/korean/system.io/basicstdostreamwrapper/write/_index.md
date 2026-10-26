---
title: Write()
second_title: Aspose.Slides for C++ API 참조
description: 래핑 모드가 바이너리인 경우, 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 기록합니다. 그렇지 않은 경우 지정된 바이트 배열에서 지정된 바이트 하위 범위를 char_type 형식으로 변환한 다음 결과를 스트림에 기록합니다.
type: docs
weight: 79
url: /ko/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


래핑 모드가 바이너리인 경우, 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 기록합니다. 그렇지 않으면 지정된 바이트 배열에서 지정된 바이트 하위 범위를 char_type 형식으로 변환한 후 결과를 스트림에 기록합니다.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기 위해 바이트를 포함하는 배열 |
| offset | **int32_t** | 쓰기 하위 범위가 시작되는 **buffer** 내 요소의 0부터 시작하는 인덱스 |
| count | **int32_t** | 쓰기 하위 범위에 있는 요소 수 |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 기록합니다.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기 위해 바이트를 포함하는 배열 뷰 |
| offset | **int32_t** | 쓰기 하위 범위가 시작되는 **buffer** 내 요소의 0부터 시작하는 인덱스 |
| count | **int32_t** | 쓰기 하위 범위에 있는 요소 수 |

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [BasicSTDOStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)