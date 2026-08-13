---
title: CastEnumerableTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 enumerable 객체의 요소들을 다른 타입으로 명시적으로 캐스팅합니다.
type: docs
weight: 2965
url: /ko/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) 함수

지정된 enumerable 객체의 요소들을 다른 유형으로 명시적 캐스팅합니다.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| To | enumerable 객체의 요소들을 정적으로 캐스팅할 유형 |
| From | enumerable 객체의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| enumerable | const From\& | 캐스팅할 요소들을 포함하는 enumerable 객체 |

### 반환 값

새 컬렉션에 대한 포인터이며, **enumerable**의 요소와 동등한 **To** 유형의 요소를 포함합니다.

## System::CastEnumerableTo(const From\&) 함수

지정된 enumerable 객체의 요소들을 다른 유형으로 명시적 캐스팅합니다.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| To | enumerable 객체의 요소들을 정적으로 캐스팅할 유형 |
| From | enumerable 객체의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| enumerable | const From\& | 정의된 get_Count 메서드를 가진 Enumerable 객체의 상속자이며 캐스팅할 요소들을 포함합니다 |

### 반환 값

새 컬렉션에 대한 포인터이며, **enumerable**의 요소와 동등한 **To** 유형의 요소를 포함합니다.

## 참조

* 클래스 [ListPtr](../../system.collections.generic/listptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)