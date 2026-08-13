---
title: CheckedCast()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 값이 타입 TTo의 값 범위에 속하는지 확인하고, 속한다면 해당 값을 타입 TTo로 변환합니다.
type: docs
weight: 2796
url: /ko/system/checkedcast/
---
## System::CheckedCast(TFrom) 함수

지정된 값이 **TTo** 유형의 값 범위에 포함되는지 확인하고, 포함될 경우 **TTo** 유형으로 변환합니다.

```cpp
template<typename TTo,typename TFrom> TTo System::CheckedCast(TFrom value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 지정된 값을 변환할 타입 |
| TFrom | 지정된 값의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | TFrom | 캐스트할 값 |

### 반환 값

**value**와 동등한 **TTo** 유형의 값

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)