---
title: Write()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 바이트 배열에서 지정된 바이트 하위 범위를 기본 스트림에 씁니다.
type: docs
weight: 66
url: /ko/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드


지정된 바이트 배열에서 지정된 바이트 하위 범위를 기본 스트림에 씁니다.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기 작업을 수행할 바이트를 포함하는 배열 |
| offset | **int32_t** | **buffer**에서 쓰기 하위 범위가 시작되는 0 기반 인덱스 |
| count | **int32_t** | 쓰기 하위 범위에 있는 요소의 개수 |


## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드


지정된 바이트 배열에서 지정된 바이트 하위 범위를 기본 스트림에 씁니다.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기 작업을 수행할 바이트를 포함하는 배열 |
| offset | **int32_t** | **buffer**에서 쓰기 하위 범위가 시작되는 0 기반 인덱스 |
| count | **int32_t** | 쓰기 하위 범위에 있는 요소의 개수 |


## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [BufferedStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)