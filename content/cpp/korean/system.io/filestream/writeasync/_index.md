---
title: WriteAsync()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비동기적으로 바이트 시퀀스를 현재 스트림에 쓰고, 쓰여진 바이트 수만큼 현재 스트림 내 위치를 이동하며, 취소 요청을 모니터링합니다.
type: docs
weight: 261
url: /ko/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) 메서드

비동기적으로 바이트 시퀀스를 현재 스트림에 쓰고, 쓰여진 바이트 수만큼 현재 스트림 내 위치를 이동하며, 취소 요청을 모니터링합니다.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 쓰여질 바이트를 포함하는 배열입니다. |
| offset | **int32_t** | 쓰기 하위 범위가 시작되는 **buffer** 내 요소의 0 기반 인덱스입니다. |
| count | **int32_t** | 쓰기 하위 범위에 포함된 요소 수입니다. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링할 토큰입니다. |

### 반환 값

비동기 쓰기 작업을 나타내는 작업(Task)입니다.

## 참고

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [CancellationToken](../../../system.threading/cancellationtoken/)
* 클래스 [FileStream](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)