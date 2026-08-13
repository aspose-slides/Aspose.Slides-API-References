---
title: has_print_to_method
second_title: Aspose.Slides for C++ API 참조
description: "주어진 타입을 첫 번째 인수로 받는 PrintTo 함수의 오버로드가 있는지 확인합니다. 오버로드가 존재하면 std::true_type을 상속하고, 그렇지 않으면 std::false_type을 상속합니다."
type: docs
weight: 27
url: /ko/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

주어진 타입을 첫 번째 인수로 받는 PrintTo 함수의 오버로드가 있는지 확인합니다. 오버로드가 존재하면 std::true_type을 상속하고, 그렇지 않으면 std::false_type을 상속합니다.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인할 유형. |
| Enable | SFINAE가 작동하도록 하는 형식 인수. |

## 참고

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)