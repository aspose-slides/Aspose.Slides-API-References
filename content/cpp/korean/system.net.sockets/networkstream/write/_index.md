---
title: Write()
second_title: C++용 Aspose.Slides API 참조
description: 지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.
type: docs
weight: 209
url: /ko/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰기에 사용할 바이트를 포함하는 배열입니다. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋입니다. |
| size | **int32_t** | 쓰게 될 하위 범위에 포함된 요소의 수입니다. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드

지정된 바이트 배열에서 지정된 바이트 하위 범위를 스트림에 씁니다.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 쓰기에 사용할 바이트를 포함하는 배열 뷰입니다. |
| offset | **int32_t** | 쓰게 될 하위 범위가 시작되는 **buffer** 내 요소의 0부터 시작하는 인덱스입니다. |
| size | **int32_t** | 쓰게 될 하위 범위에 포함된 요소의 수입니다. |

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [NetworkStream](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)