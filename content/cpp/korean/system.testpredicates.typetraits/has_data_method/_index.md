---
title: has_data_method
second_title: Aspose.Slides for C++ API 레퍼런스
description: "형식에 data() 메서드가 있는지 확인합니다. 있으면 std::true_type를 상속하고, 없으면 std::false_type를 상속합니다."
type: docs
weight: 1
url: /ko/system.testpredicates.typetraits/has_data_method/
---
## has_data_method 구조체


형식에 data() 메서드가 있는지 확인합니다. 있으면 std::true_type를 상속하고, 없으면 std::false_type를 상속합니다.

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인할 형식. |
| Enable | SFINAE가 작동하도록 하는 형식 인수. |

## 참고

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)