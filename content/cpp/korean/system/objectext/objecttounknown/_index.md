---
title: ObjectToUnknown()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Object를 알 수 없는 유형으로 변환하며, 스마트 포인터 유형과 bpxed 값 상황을 모두 처리합니다.
type: docs
weight: 131
url: /ko/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) 메서드

[Object](../../object/)를 알 수 없는 유형으로 변환하며, 스마트 포인터 유형과 bpxed 값 상황을 모두 처리합니다.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 변환할 [Object](../../object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | 변환할 [Object](../../object/). |

### 반환 값

언박싱된 값이든 변환된 포인터이든 반환합니다.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) 메서드

[Object](../../object/)를 알 수 없는 유형으로 변환하며, 스마트 포인터 유형과 boxed 값 상황을 모두 처리합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 변환할 [Object](../../object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | 변환할 [Object](../../object/). |

### 반환 값

언박싱된 값이든 변환된 포인터이든 반환합니다.

## 관련 항목

* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [Object](../../object/)
* 클래스 [ObjectExt](../)
* 구조체 [IsSmartPtr](../../issmartptr/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)