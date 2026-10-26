---
title: get_pointer()
second_title: Aspose.Slides for C++ API 참조
description: 스마트 포인터가 참조하는 객체를 가져옵니다.
type: docs
weight: 2952
url: /ko/system/get_pointer/
---
## System::get_pointer(System::SmartPtr\<T\> const\&) 함수

스마트 포인터가 참조하는 객체를 가져옵니다.

```cpp
template<class T> T * System::get_pointer(System::SmartPtr<T> const &x)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 가리키는 객체 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | [System::SmartPtr](../smartptr/)\<T\> const\& | 소스 스마트 포인터. |

### 반환 값

전달된 스마트 포인터가 참조하는 객체에 대한 원시 포인터.

## 참고

* 클래스 [SmartPtr](../smartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)