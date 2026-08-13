---
title: const_pointer_cast()
second_title: Aspose.Slides for C++ API 레퍼런스
description: const_cast을 사용하여 스마트 포인터를 캐스팅합니다.
type: docs
weight: 2939
url: /ko/system/const_pointer_cast/
---
## System::const_pointer_cast(SmartPtr\<X\> const\&) function

const_cast을 사용하여 스마트 포인터를 캐스팅합니다.

```cpp
template<class Y,class X> SmartPtr<Y> System::const_pointer_cast(SmartPtr<X> const &x)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 소스 포인터 피오니 타입. |
| Y | 타깃 포인터 피오니 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 소스 포인터. |

### 반환 값

캐스트 후 포인터.

## 관련 항목

* 클래스 [SmartPtr](../smartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)