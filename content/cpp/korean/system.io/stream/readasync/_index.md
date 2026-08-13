---
title: ReadAsync()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 앞당기며, 취소 요청을 모니터링합니다.
type: docs
weight: 40
url: /ko/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method


현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 앞당기며, 취소 요청을 모니터링합니다.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열입니다. |
| offset | **int32_t** | **buffer**에서 기록을 시작할 0 기반 위치입니다. |
| count | **int32_t** | 읽을 바이트 수입니다. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링할 토큰입니다. |

### 반환 값

비동기 읽기 작업을 나타내는 작업입니다. TResult 매개변수의 값에는 버퍼에 읽힌 총 바이트 수가 들어 있습니다. 현재 사용 가능한 바이트 수가 요청된 수보다 적은 경우 결과 값은 요청된 바이트 수보다 작을 수 있으며, 스트림 끝에 도달한 경우 0(영)이 될 수 있습니다.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


현재 스트림에서 바이트 시퀀스를 비동기적으로 읽고, 읽은 바이트 수만큼 스트림 내 위치를 앞당기며, 취소 요청을 모니터링합니다.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열입니다. |
| offset | **int32_t** | **buffer**에서 기록을 시작할 0 기반 위치입니다. |
| count | **int32_t** | 읽을 바이트 수입니다. |

### 반환 값

비동기 읽기 작업을 나타내는 작업입니다. TResult 매개변수의 값에는 버퍼에 읽힌 총 바이트 수가 들어 있습니다. 현재 사용 가능한 바이트 수가 요청된 수보다 적은 경우 결과 값은 요청된 바이트 수보다 작을 수 있으며, 스트림 끝에 도달한 경우 0(영)이 될 수 있습니다.

## 또 보기

* 타입정의 [RTaskPtr](../../../system/rtaskptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [CancellationToken](../../../system.threading/cancellationtoken/)
* 클래스 [Stream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)