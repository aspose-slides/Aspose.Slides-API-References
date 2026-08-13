---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 씁니다.
type: docs
weight: 79
url: /ko/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 해당 바이트를 지정된 바이트 배열에 씁니다.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 |
| offset | **int32_t** | **buffer**에 기록을 시작할 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환 값

읽은 바이트 수

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 해당 바이트를 지정된 바이트 배열에 씁니다.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 뷰 |
| offset | **int32_t** | **buffer**에 기록을 시작할 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환 값

읽은 바이트 수

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)