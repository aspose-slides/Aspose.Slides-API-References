---
title: UnknownIsNull()
second_title: Aspose.Slides for C++ API 참조
description: 알 수 없는 타입 객체가 nullptr인지 확인합니다. 비스칼라 타입에 대한 오버로드입니다.
type: docs
weight: 144
url: /ko/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) 메서드


Checks whether unknown type object is nullptr. Overload for non-scalar types.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../object/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T | [Object](../../object/) 확인 대상. |

### 반환값

True if 'obj == nullptr'가 true이면 True, 그렇지 않으면 false.

## ObjectExt::UnknownIsNull(T) 메서드


Checks whether unknown type object is nullptr. Overload for scalar types.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../object/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T | [Object](../../object/) 확인 대상. |

### 반환값

항상 false를 반환합니다.

## 참고

* 클래스 [ObjectExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)