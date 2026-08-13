---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 포인터가 가리키는 객체가 특정 타입 또는 그 하위 타입인지 확인합니다. C# 'is' 연산자와 동일한 동작을 따릅니다.
type: docs
weight: 300
url: /ko/system/smartptr/is/
---
## SmartPtr::Is(const System::TypeInfo\&) const 메서드


Checks if pointed object is of specific type or its child type. Follows C# 'is' semantics.

```cpp
bool System::SmartPtr<T>::Is(const System::TypeInfo &target) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | 대상 유형을 지정합니다. |

### 반환 값

True if C# 'is'-style check is positive and false otherwise.

## 비고

Implementation.

## 참고

* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)