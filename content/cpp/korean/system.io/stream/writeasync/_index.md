---
title: WriteAsync()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바이트 시퀀스를 현재 스트림에 비동기적으로 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 이동시키며, 취소 요청을 모니터링합니다.
type: docs
weight: 66
url: /ko/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) 메서드

바이트 시퀀스를 현재 스트림에 비동기적으로 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 이동시키며, 취소 요청을 모니터링합니다.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓸 바이트를 포함하는 배열. |
| offset | **int32_t** | **buffer** 내에서 쓰기 하위 범위가 시작되는 0 기반 인덱스. |
| count | **int32_t** | 쓰기 하위 범위에 포함된 요소 수. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링할 토큰. |

### 반환값

비동기 쓰기 작업을 나타내는 작업.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

바이트 시퀀스를 현재 스트림에 비동기적으로 쓰고, 쓰여진 바이트 수만큼 스트림 내 현재 위치를 이동시키며, 취소 요청을 모니터링합니다.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓸 바이트를 포함하는 배열. |
| offset | **int32_t** | **buffer** 내에서 쓰기 하위 범위가 시작되는 0 기반 인덱스. |
| count | **int32_t** | 쓰기 하위 범위에 포함된 요소 수. |

### 반환값

비동기 쓰기 작업을 나타내는 작업.

## 참조

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [CancellationToken](../../../system.threading/cancellationtoken/)
* 클래스 [Stream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)