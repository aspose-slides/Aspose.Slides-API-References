---
title: Box()
second_title: Aspose.Slides for C++ API 참조
description: 값 유형을 Object 로 변환하기 위해 박싱합니다. 열거형에 대한 구현입니다.
type: docs
weight: 40
url: /ko/system/objectext/box/
---
## ObjectExt::Box(const T\&) 메서드

값 유형을 [Object](../../object/) 로 변환하기 위해 박싱합니다. 열거형에 대한 구현입니다.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Enum](../../enum/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) 값을 박싱합니다. |

### 반환값

박싱된 값을 보관하는 객체에 대한 스마트 포인터.

## ObjectExt::Box(const T\&) 메서드

값 유형을 [Object](../../object/) 로 변환하기 위해 박싱합니다. 비열거형에 대한 구현입니다.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | 값을 박싱합니다. |

### 반환값

박싱된 값을 보관하는 객체에 대한 스마트 포인터.

## ObjectExt::Box(const T\&) 메서드

[Nullable](../../nullable/) 유형을 [Object](../../object/) 로 변환하기 위해 박싱합니다.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | 값을 박싱합니다. |

### 반환값

박싱된 값을 보관하는 객체에 대한 스마트 포인터.

## ObjectExt::Box(const String\&) 메서드

문자열 값을 박싱합니다.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 값을 박싱합니다. |

### 반환값

소스 문자열이 null인 경우 박싱된 값 또는 null을 반환합니다.

## 참조

* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [Object](../../object/)
* 클래스 [ObjectExt](../)
* 클래스 [String](../../string/)
* Struct [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)