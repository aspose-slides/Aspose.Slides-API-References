---
title: Read()
second_title: Aspose.Slides C++ API 레퍼런스
description: 래핑 모드가 바이너리인 경우 스트림에서 지정된 바이트 수를 읽고, 그렇지 않으면 지정된 문자 수를 읽어 uint8_t 형식으로 변환합니다. 읽은 결과를 지정된 바이트 배열에 씁니다.
type: docs
weight: 66
url: /ko/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

If wrapping mode is binary, reads the specified number of bytes from the stream, otherwise read the specified number of characters and converts them to **uint8_t** type. Writes result of the reading to the specified byte array.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 쓸 바이트 배열 |
| offset | **int32_t** | **buffer**에서 쓰기를 시작할 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환값

읽은 바이트 또는 문자 수

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 쓸 바이트 배열 뷰 |
| offset | **int32_t** | **buffer**에서 쓰기를 시작할 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환값

읽은 바이트 수

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)