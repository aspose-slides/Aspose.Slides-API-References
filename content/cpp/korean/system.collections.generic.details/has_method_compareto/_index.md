---
title: has_method_compareto
second_title: Aspose.Slides for C++ API 레퍼런스
description: "지정된 형식에 CompareTo 메서드가 존재하는지 확인합니다. 존재하면 std::true_type을 상속하고, 그렇지 않으면 std::false_type을 상속합니다. std::enable_if에서 사용할 수 있습니다."
type: docs
weight: 170
url: /ko/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

지정된 타입에 CompareTo 메서드가 존재하는지 확인합니다. 존재하면 `std::true_type`을 상속하고, 그렇지 않으면 `std::false_type`을 상속합니다. `std::enable_if`에서 사용할 수 있습니다.

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### Template 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Equals 메서드 존재를 확인할 타입. |
| Sfinae | SFINAE가 작동하도록 하는 형식 템플릿 인수. |

## 참고

* 네임스페이스 [System::Collections::Generic::Details](../)
* 라이브러리 [Aspose.Slides](../../)