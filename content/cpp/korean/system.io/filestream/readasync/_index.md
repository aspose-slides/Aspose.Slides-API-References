---
title: ReadAsync()
second_title: Aspose.Slides for C++ API 참조
description: 현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동하며, 취소 요청을 모니터링합니다.
type: docs
weight: 196
url: /ko/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) 메서드

현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동하며, 취소 요청을 모니터링합니다.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열입니다. |
| offset | **int32_t** | **buffer**에서 기록을 시작하는 0 기반 위치입니다. |
| count | **int32_t** | 읽을 바이트 수입니다. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링할 토큰입니다. |

### 반환값

비동기 읽기 작업을 나타내는 작업(Task)입니다. TResult 매개변수의 값은 버퍼에 읽힌 전체 바이트 수를 포함합니다. 현재 사용 가능한 바이트 수가 요청된 수보다 적은 경우 결과 값은 요청된 바이트 수보다 작을 수 있으며, 스트림의 끝에 도달한 경우 0(영)이 될 수 있습니다.

## 참조

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)