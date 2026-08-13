---
title: BoxEnum()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 열거형 타입을 Object로 전파하기 위해 박싱합니다.
type: docs
weight: 196
url: /ko/system/objectext/boxenum/
---
## ObjectExt::BoxEnum(T) 메서드

Boxes enum types for being propagated as [Object](../../object/).

```cpp
template<typename T> static SmartPtr<System::BoxedValueBase> System::ObjectExt::BoxEnum(T enumValue)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Enum](../../enum/) 타입을 박싱합니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| enumValue | T | [Enum](../../enum/) 값을 박싱합니다. |

### 반환 값

박싱된 열거형 값.

## 참조

* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [BoxedValueBase](../../boxedvaluebase/)
* 클래스 [ObjectExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)