---
title: UnboxToNullable()
second_title: Aspose.Slides for C++ API 참조
description: 객체를 nullable 타입으로 언박스합니다.
type: docs
weight: 79
url: /ko/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) 메서드


객체를 nullable 타입으로 언박스합니다.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 목적지 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/)을 언박스합니다. |
| safe | **bool** | true인 경우 실패 시 nullptr를 반환하고, 그렇지 않으면 InvalidCastException을 발생시킵니다. |

### 반환값

언박스된 nullable 값 (null일 수 있음).

## 참조

* 클래스 [Nullable](../../nullable/)
* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [Object](../../object/)
* 클래스 [ObjectExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)