---
title: Read()
second_title: Aspose.Slides for C++ API 참조
description: 스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 씁니다.
type: docs
weight: 144
url: /ko/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 씁니다.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 쓸 바이트 배열 |
| offset | **int32_t** | **buffer**에서 쓰기를 시작할 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환값

읽은 바이트 수

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽어 지정된 바이트 배열에 씁니다.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 쓸 바이트 배열 뷰 |
| offset | **int32_t** | **buffer**에서 쓰기를 시작할 0 기반 위치 |
| count | **int32_t** | 읽을 바이트 수 |

### 반환값

읽은 바이트 수

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [UnmanagedMemoryStream](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)