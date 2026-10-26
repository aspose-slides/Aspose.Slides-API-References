---
title: GetDescription()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 가진 열거형 상수의 이름을 반환합니다.
type: docs
weight: 53
url: /ko/system/enum/getdescription/
---
## Enum::GetDescription(T) 메서드


지정된 값을 가진 열거형 상수의 이름을 반환합니다.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 이름이 반환될 enum 상수의 값 |

### 반환값

지정된 enum 상수의 이름

## 참조

* 타입정의 [UnderlyingType](../underlyingtype/)
* 클래스 [String](../../string/)
* 구조체 [Enum](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)