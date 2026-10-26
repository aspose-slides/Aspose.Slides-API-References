---
title: dynamic_pointer_cast()
second_title: Aspose.Slides for C++ API 참조
description: dynamic_cast를 사용하여 스마트 포인터를 캐스팅합니다.
type: docs
weight: 2926
url: /ko/system/dynamic_pointer_cast/
---
## System::dynamic_pointer_cast(SmartPtr\<X\> const\&) 함수

dynamic_cast를 사용하여 스마트 포인터를 캐스팅합니다.

```cpp
template<class Y,class X> SmartPtr<Y> System::dynamic_pointer_cast(SmartPtr<X> const &x)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 소스 포인터가 가리키는 타입. |
| Y | 타겟 포인터가 가리키는 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 소스 포인터. |

### 반환값

캐스팅 후 포인터.

## 참조

* 클래스 [SmartPtr](../smartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)