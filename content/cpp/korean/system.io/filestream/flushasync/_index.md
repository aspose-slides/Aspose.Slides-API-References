---
title: FlushAsync()
second_title: Aspose.Slides for C++ API 참조
description: 이 스트림에 대한 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하며, 취소 요청을 모니터링합니다.
type: docs
weight: 157
url: /ko/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) 메서드

이 스트림에 대한 모든 버퍼를 비동기적으로 비우고, 버퍼링된 데이터를 기본 장치에 기록하도록 하며, 취소 요청을 모니터링합니다.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링하기 위한 토큰입니다. |

### 반환값

비동기 플러시 작업을 나타내는 작업.

## 참조

* Typedef [TaskPtr](../../../system/taskptr/)
* 클래스 [CancellationToken](../../../system.threading/cancellationtoken/)
* 클래스 [FileStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)