---
title: EnumParseHelper
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열 표현을 enum 상수로 변환하는 기능을 제공하는 도우미 클래스입니다.
type: docs
weight: 1613
url: /ko/system/enumparsehelper/
---
## EnumParseHelper 구조체

문자열 표현을 enum 상수로 변환하는 기능을 제공하는 도우미 클래스입니다.

```cpp
template<class E,class G,class Guard>class EnumParseHelper
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| E | 클래스 메서드가 작동하는 enum 유형 |
| G | 사용할 [System::Enum](../enum/)의 두 번째 형식 인수 |
| Guard | 사용 가능한 구문 분석 알고리즘을 선택하는 형식 템플릿 인수 |

## 메서드

| Method | Description |
| --- | --- |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | 지정된 문자열을 동일한 enum 상수 값으로 변환합니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)