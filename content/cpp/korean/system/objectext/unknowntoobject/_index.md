---
title: UnknownToObject()
second_title: Aspose.Slides C++ API 참조
description: 알 수 없는 유형을 Object(으)로 변환하며, 스마트 포인터 유형과 값 유형 상황을 모두 처리합니다.
type: docs
weight: 118
url: /ko/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) 메서드

알 수 없는 유형을 [Object](../../object/)(으)로 변환하며, 스마트 포인터 유형과 값 유형 상황 모두를 처리합니다.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../object/)(으)로 변환할 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | T | 변환할 [Object](../../object/). |

### 반환 값

[Object](../../object/)에 대한 스마트 포인터이며, 변환된 포인터 또는 박싱된 값 중 하나입니다.

## ObjectExt::UnknownToObject(const T\&) 메서드

알 수 없는 유형을 [Object](../../object/)(으)로 변환하며, 스마트 포인터 유형과 값 유형 상황 모두를 처리합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../object/)(으)로 변환할 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | const T\& | 변환할 [Object](../../object/). |

### 반환 값

[Object](../../object/)에 대한 스마트 포인터이며, 변환된 포인터 또는 박싱된 값 중 하나입니다.

## 참고

* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [Object](../../object/)
* 클래스 [ObjectExt](../)
* 구조체 [IsSmartPtr](../../issmartptr/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)