---
title: GetName()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 값을 갖는 열거형 상수의 이름을 반환합니다.
type: docs
weight: 40
url: /ko/system/enum/getname/
---
## Enum::GetName(T) 메서드


Returns the name of the enumeration constant that has the specified value.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 이 이름을 반환할 열거형 상수의 값 |

### 반환값

지정된 열거형 상수의 이름

## 참조

* Typedef [UnderlyingType](../underlyingtype/)
* 클래스 [String](../../string/)
* 구조체 [Enum](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)