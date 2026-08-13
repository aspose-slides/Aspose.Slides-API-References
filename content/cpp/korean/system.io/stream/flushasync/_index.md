---
title: FlushAsync()
second_title: Aspose.Slides for C++ API 참조
description: 스트림의 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하며, 취소 요청을 모니터링합니다.
type: docs
weight: 118
url: /ko/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) 메서드

스트림의 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하며, 취소 요청을 모니터링합니다.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링할 토큰입니다. |

### 반환값

비동기 플러시 작업을 나타내는 작업입니다.

## Stream::FlushAsync() 메서드

스트림의 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하며, 취소 요청을 모니터링합니다.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### 반환값

비동기 플러시 작업을 나타내는 작업입니다.

## 관련 항목

* Typedef [TaskPtr](../../../system/taskptr/)
* 클래스 [CancellationToken](../../../system.threading/cancellationtoken/)
* 클래스 [Stream](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)