---
title: GetFrame()
second_title: Aspose.Slides for C++ API 참조
description: 스택 프레임을 가져옵니다.
type: docs
weight: 40
url: /ko/system.diagnostics/stacktrace/getframe/
---
## StackTrace::GetFrame(uint32_t) 메서드


스택 프레임을 가져옵니다.

```cpp
virtual SharedPtr<StackFrame> System::Diagnostics::StackTrace::GetFrame(uint32_t index)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **uint32_t** | 스택 프레임 인덱스, 0과 FrameCount-1 사이여야 합니다. |

### 반환값

사용 가능한 스택 프레임.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StackFrame](../../stackframe/)
* Class [StackTrace](../)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)