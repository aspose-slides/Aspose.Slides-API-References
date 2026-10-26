---
title: Cast()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 포인터를 해당 유형 자체로 변환합니다.
type: docs
weight: 287
url: /ko/system/smartptr/cast/
---
## SmartPtr::Cast() const 메서드

포인터를 해당 유형 자체로 변환합니다.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | 포인터가 가리키는 객체의 대상 유형. |
| Check | 변환이 불가능한 경우 예외를 발생시키는 플래그. |

### 반환 값

항상 공유 모드인 변경된 유형의 포인터.

## SmartPtr::Cast() const 메서드

static_cast를 사용하여 포인터를 기본 유형으로 변환합니다.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | 포인터가 가리키는 객체의 대상 유형. |
| Check | 변환이 불가능한 경우 예외를 발생시키는 플래그. |

### 반환 값

항상 공유 모드인 변경된 유형의 포인터.

## SmartPtr::Cast() const 메서드

dynamic_cast를 사용하여 포인터를 파생 유형으로 변환합니다.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | 포인터가 가리키는 객체의 대상 유형. |
| Check | 변환이 불가능한 경우 예외를 발생시키는 플래그. |

### 반환 값

항상 공유 모드인 변경된 유형의 포인터. 변환이 불가능한 경우 InvalidCastException을 발생시킵니다.

## SmartPtr::Cast() const 메서드

dynamic_cast를 사용하여 포인터를 파생 유형으로 변환합니다.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Y | 포인터가 가리키는 객체의 대상 유형. |
| Check | 변환이 불가능한 경우 예외를 발생시키는 플래그. |

### 반환 값

항상 공유 모드인 변경된 유형의 포인터. 변환이 불가능한 경우 nullptr를 반환합니다.

## 참조

* 클래스 [SmartPtr](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)