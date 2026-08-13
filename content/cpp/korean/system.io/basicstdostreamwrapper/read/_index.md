---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 래핑 모드가 바이너리인 경우 스트림에서 지정된 바이트 수를 읽고, 그렇지 않으면 지정된 문자 수를 읽어 uint8_t 유형으로 변환합니다. 읽은 결과를 지정된 바이트 배열에 씁니다. 지원되지 않음!
type: docs
weight: 66
url: /ko/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드


If wrapping mode is binary, reads the specified number of bytes from the stream, otherwise read the specified number of characters and converts them to **uint8_t** type. Writes result of the reading to the specified byte array. Not supported!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 쓸 바이트 배열 |
| offset | **int32_t** | 쓰기 시작 위치인 **buffer**의 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환값

Number of bytes or characters read

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드


스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열에 씁니다.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 쓸 바이트 배열 보기 |
| offset | **int32_t** | 쓰기 시작 위치인 **buffer**의 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환값

The number of bytes read

## 관련

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)