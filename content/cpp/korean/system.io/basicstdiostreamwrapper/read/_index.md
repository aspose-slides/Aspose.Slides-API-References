---
title: Read()
second_title: Aspose.Slides for C++ API 참조
description: 래핑 모드가 바이너리인 경우 스트림에서 지정된 바이트 수를 읽고, 그렇지 않으면 지정된 문자 수를 읽어 uint8_t 타입으로 변환합니다. 읽은 결과를 지정된 바이트 배열에 기록합니다.
type: docs
weight: 66
url: /ko/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

래핑 모드가 바이너리인 경우 스트림에서 지정된 바이트 수를 읽고, 그렇지 않으면 지정된 문자 수를 읽어 **uint8_t** 형식으로 변환합니다. 읽은 결과를 지정된 바이트 배열에 기록합니다.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### 반환값

읽은 바이트 또는 문자 수

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열에 기록합니다.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array view to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### 반환값

읽은 바이트 수

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [BasicSTDIOStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)