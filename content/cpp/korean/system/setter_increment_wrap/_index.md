---
title: setter_increment_wrap()
second_title: Aspose.Slides C++ API 레퍼런스
description: 번역기는 setter와 getter가 정의된 클래스의 속성을 대상으로 하는 C#의 증감 표현식을 이 함수 호출로 변환합니다.
type: docs
weight: 2835
url: /ko/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) 함수

Translator translates C#'s increment expressions targeting 클래스' 속성 that has setter and getter defined, into invocation of this 함수.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 속성의 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| pGetter | T(*)() | 속성의 getter 자유 함수를 가리키는 함수 포인터 |
| pSetter | void(*)(T) | 속성의 setter 자유 함수를 가리키는 함수 포인터 |

### 반환 값

속성의 증가된 값

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 함수

Translator translates C#'s increment expressions targeting 클래스' 속성 that has setter and getter defined, into invocation of this 함수.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 속성의 타입 |
| Host | - 수정될 인스턴스의 클래스 |
| HostGet | - Host 자체 또는 속성의 getter가 정의된 기본 타입 |
| HostSet | - Host 자체 또는 속성의 setter가 정의된 기본 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| host | Host *const | 속성을 증가시킬 객체를 가리키는 포인터 |
| pGetter | T(HostGet::*)() | 속성의 getter 메서드를 가리키는 함수 포인터 |
| pSetter | void(HostSet::*)(T) | 속성의 setter 메서드를 가리키는 함수 포인터 |

### 반환 값

속성의 증가된 값

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)