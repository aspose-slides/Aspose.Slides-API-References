---
title: setter_decrement_wrap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 번역기는 setter와 getter가 정의된 클래스의 속성을 대상으로 하는 C# 사전 감소 표현식을 이 함수 호출로 변환합니다.
type: docs
weight: 2861
url: /ko/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) 함수

Translator translates C#'s pre-decrement expressions targeting class' property that has setter and getter defined, into invocation of this function.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 속성의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pGetter | T(*)() | 속성의 getter 자유 함수를 가리키는 함수 포인터 |
| pSetter | void(*)(T) | 속성의 setter 자유 함수를 가리키는 함수 포인터 |

### 반환 값

증가시키기 전 속성의 값

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 함수

Translator translates C#'s pre-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for non-const getter).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 속성의 형식. |
| Host | - 수정될 인스턴스의 클래스 |
| HostGet | - 속성의 getter가 정의된 Host 자체 또는 그 기반 타입 |
| HostSet | - 속성의 setter가 정의된 Host 자체 또는 그 기반 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | Host *const | getter와 setter를 호출할 인스턴스. |
| pGetter | T(HostGet::*)() | 속성의 getter 함수를 가리키는 함수 포인터 |
| pSetter | void(HostSet::*)(T) | 속성의 setter 함수를 가리키는 함수 포인터 |

### 반환 값

증가시키기 전 속성의 값

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) 함수

Translator translates C#'s pre-decrement expressions targeting instance's property that has setter and getter defined, into invocation of this function (overload for const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 속성의 형식. |
| Host | - 수정될 인스턴스의 클래스 |
| HostConstGet | - 속성의 getter가 정의된 Host 자체 또는 그 기반 타입 |
| HostSet | - 속성의 setter가 정의된 Host 자체 또는 그 기반 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | Host *const | getter와 setter를 호출할 인스턴스. |
| pGetter | T(HostConstGet::*)() const | 속성의 getter 함수를 가리키는 함수 포인터 |
| pSetter | void(HostSet::*)(T) | 속성의 setter 함수를 가리키는 함수 포인터 |

### 반환 값

증가시키기 전 속성의 값

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)