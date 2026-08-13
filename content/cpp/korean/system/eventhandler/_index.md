---
title: EventHandler
second_title: Aspose.Slides C++ API 참조
description: "이벤트에 반응하고 처리하는 메서드를 나타냅니다. 이 타입은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하려면 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 3706
url: /ko/system/eventhandler/
---
## EventHandler 타입 정의

이벤트에 반응하고 처리하는 메서드를 나타냅니다. 이 유형은 스택에 할당되고 함수에 값 또는 참조로 전달되어야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)