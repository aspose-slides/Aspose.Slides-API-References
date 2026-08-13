---
title: WaitForExit()
second_title: Aspose.Slides for C++ API 참조
description: 프로세스가 종료될 때까지 대기합니다. 구현되지 않았습니다.
type: docs
weight: 27
url: /ko/system.diagnostics/process/waitforexit/
---
## Process::WaitForExit(int) 메서드

프로세스가 종료될 때까지 대기합니다. 구현되지 않았습니다.

```cpp
bool System::Diagnostics::Process::WaitForExit(int milliseconds)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| milliseconds | int | 최대 대기 지연시간. |

### 반환값

프로세스가 완료되면 true, 제한 시간이 초과하면 false를 반환합니다.

## Process::WaitForExit() 메서드

프로세스가 종료될 때까지 대기하며, 종료될 때까지 반환되지 않습니다.

```cpp
void System::Diagnostics::Process::WaitForExit()
```

## 참고

* 클래스 [Process](../)
* 네임스페이스 [System::Diagnostics](../../)
* 라이브러리 [Aspose.Slides](../../../)