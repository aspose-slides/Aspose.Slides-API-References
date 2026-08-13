---
title: Compare()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 실제 데이터 비교.
type: docs
weight: 1
url: /ko/system.collections.generic/defaultcomparer/compare/
---
## DefaultComparer::Compare(typename ThisType::args_type, typename ThisType::args_type) const 메서드

실제 데이터 비교.

```cpp
virtual int System::Collections::Generic::DefaultComparer<T, typename>::Compare(typename ThisType::args_type x, typename ThisType::args_type y) const override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | typename [ThisType::args_type](../../icomparer/args_type/) | 좌항 피연산자. |
| y | typename [ThisType::args_type](../../icomparer/args_type/) | 우항 피연산자. |

### 반환값

피연산자 **x**가 **y**보다 작으면 음수, 피연산자가 동일하면 0, 그 외에는 양수.

## 관련 항목

* Typedef [args_type](../../icomparer/args_type/)
* Class [DefaultComparer](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)