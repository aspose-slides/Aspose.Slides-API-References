---
title: setter_wrap()
second_title: Aspose.Slides for C++ API 참조
description: 형 변환을 사용한 정적 setter 함수에 대한 오버로드.
type: docs
weight: 2822
url: /ko/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) 함수

형 변환을 사용한 정적 setter 함수에 대한 오버로드.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 유형. |
| T2 | setter 함수가 기대하는 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pSetter | void(*)(T2) | 정적 setter 함수 참조. |
| value | T | 설정할 값. |

### 반환 값

값을 설정합니다.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) 함수

형 변환을 사용한 인스턴스 setter 함수에 대한 오버로드.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 유형. |
| T2 | setter 함수가 기대하는 형식. |
| Host | 인스턴스 유형. |
| HostSet | - 속성의 setter가 정의된 Host 자체 또는 그 기반 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | Host *const | [Object](../object/)에 대한 setter 함수를 호출하기 위해. |
| pSetter | void(HostSet::*)(T2) | setter 함수 참조. |
| value | T | 설정할 값. |

### 반환 값

값을 설정합니다.

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)