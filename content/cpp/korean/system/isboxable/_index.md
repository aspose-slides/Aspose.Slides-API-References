---
title: IsBoxable
second_title: Aspose.Slides for C++ API 참조
description: 지정된 유형에 대한 박싱이 지원되는지 확인하는 템플릿 술어입니다.
type: docs
weight: 1665
url: /ko/system/isboxable/
---
## IsBoxable 구조체

지정된 유형에 대한 박싱이 지원되는지 확인하는 템플릿 술어입니다.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| T | 체크할 타입 |

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)