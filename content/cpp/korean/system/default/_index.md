---
title: Default()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 예외 유형의 단일 기본 생성 인스턴스에 대한 참조를 반환합니다.
type: docs
weight: 2224
url: /ko/system/default/
---
## System::Default() 함수

예외 유형의 단일 기본 생성 인스턴스에 대한 참조를 반환합니다.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 인스턴스를 반환하는 유형 |

## System::Default() 함수

비예외 유형의 단일 기본 생성 인스턴스에 대한 참조를 반환합니다.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 인스턴스를 반환하는 유형 |

## 참고

* 구조체 [IsExceptionWrapper](../isexceptionwrapper/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)