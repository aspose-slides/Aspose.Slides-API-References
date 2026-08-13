---
title: FromCanceled()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 토큰으로 인해 취소되어 완료된 작업을 생성합니다.
type: docs
weight: 118
url: /ko/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) 함수

지정된 토큰으로 인해 취소되어 완료된 작업을 생성합니다.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 작업이 취소되도록 만든 취소 토큰입니다. |

### 반환값

취소된 작업입니다.

## 참고

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)