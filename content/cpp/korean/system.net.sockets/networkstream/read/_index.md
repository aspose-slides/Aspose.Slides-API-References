---
title: Read()
second_title: Aspose.Slides for C++ API 참조
description: 스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 씁니다.
type: docs
weight: 196
url: /ko/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 씁니다.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트가 기록될 바이트 배열입니다. |
| offset | **int32_t** | 지정된 배열의 바이트 단위 오프셋입니다. |
| size | **int32_t** | 읽을 바이트 수입니다. |

### 반환 값

읽은 바이트 수입니다.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

스트림에서 지정된 바이트 수를 읽고 지정된 바이트 배열에 씁니다.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 뷰입니다. |
| offset | **int32_t** | **buffer**에 쓰기를 시작할 0 기반 위치입니다. |
| size | **int32_t** | 읽을 바이트 수입니다. |

### 반환 값

읽은 바이트 수입니다.

## 관련 항목

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [NetworkStream](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)