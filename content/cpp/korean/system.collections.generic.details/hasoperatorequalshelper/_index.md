---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 클래스에 연산자 == 가 있는지 확인하는 도우미 함수.
type: docs
weight: 235
url: /ko/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) 함수

특정 클래스에 연산자 == 가 있는지 확인하는 도우미 함수.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인할 형식. |
| Dummy | SFINAE 매직을 위한 더미 인수. |

### 반환 값

operator == 가 존재하면 std::true_type 값을 반환하고, 그렇지 않으면 false 값을 반환합니다.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) 함수

특정 클래스에 연산자 == 가 있는지 확인하는 도우미 함수.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### 반환 값

operator == 가 존재하면 std::true_type 값을 반환하고, 그렇지 않으면 false 값을 반환합니다.

## 참고

* 네임스페이스 [System::Collections::Generic::Details](../)
* 라이브러리 [Aspose.Slides](../../)