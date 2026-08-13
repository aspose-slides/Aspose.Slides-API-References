---
title: Read()
second_title: Aspose.Slides for C++ API 참조
description: 하위 스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열에 기록합니다.
type: docs
weight: 53
url: /ko/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

하위 스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열에 기록합니다.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 |
| offset | **int32_t** | **buffer**에 쓰기 시작할 0부터 시작하는 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환 값

읽은 바이트 수

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

하위 스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열에 기록합니다.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 |
| offset | **int32_t** | **buffer**에 쓰기 시작할 0부터 시작하는 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환 값

읽은 바이트 수

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [BufferedStream](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)