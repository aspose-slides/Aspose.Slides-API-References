---
title: Equals< float, float >()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "단정도 부동소수점 값에 대한 특수화. 두 부동소수점 NaN은 IEC 60559:1989에 의해 항상 같지 않다고 정의되지만, System.Object.Equals에 대한 계약은 오버라이드가 동등 연산자에 대한 요구 사항을 만족해야 함을 요구합니다. 따라서 System.Double.Equals와 System.Single.Equals는 두 NaN을 비교할 때 True를 반환하고, 그 경우 동등 연산자는 표준이 요구하는 대로 False를 반환합니다."
type: docs
weight: 2705
url: /ko/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) 함수

특수화 for 단정도 부동소수점 값. Although two floating point NaNs are defined by IEC 60559:1989 to always compare as unequal, the contract for [System.Object.Equals](../object/equals/), requires that overrides must satisfy the requirements for an equivalence operator. Therefore, System.Double.Equals and System.Single.Equals return True when comparing two NaNs, while the equality operator returns False in that case, as required by the standard.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const **float**\& | 첫 번째 비교 대상 |
| b | const **float**\& | 두 번째 비교 대상 |

### 반환 값

True if both values are NaN or are equal, otherwise false

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)