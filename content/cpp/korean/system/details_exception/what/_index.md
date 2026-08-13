---
title: what()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "ExceptionWrapper 클래스에 의해 호출되는 what() 메서드를 구현합니다. 이 클래스가 std::exception으로부터 상속되지 않았음에도 불구하고 파생 클래스는 protected/private 멤버를 사용하여 로직을 구현할 수 있습니다. 이 메서드 구현을 ExceptionWrapper로 이동하면 해당 로직이 깨질 수 있습니다."
type: docs
weight: 105
url: /ko/system/details_exception/what/
---
## Details_Exception::what() const 메서드

Implements [what()](./) 메서드이며 [ExceptionWrapper](../../exceptionwrapper/) 클래스에 의해 호출됩니다. 이 클래스가 std::exception으로부터 상속되지 않았음에도 불구하고 파생 클래스는 protected/private 멤버를 사용하여 로직을 구현할 수 있습니다. 이 메서드 구현을 [ExceptionWrapper](../../exceptionwrapper/) 로 이동하면 해당 로직이 깨질 수 있습니다.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### 반환 값

예외에 대한 설명.

## 관련 항목

* 클래스 [Details_Exception](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)