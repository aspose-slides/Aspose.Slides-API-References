---
title: has_print_to_method
second_title: Referensi API Aspose.Slides untuk C++
description: "Memeriksa overload fungsi PrintTo yang menerima tipe yang diberikan sebagai argumen pertama. Jika overload ada, mewarisi std::true_type, sebaliknya mewarisi std::false_type."
type: docs
weight: 27
url: /id/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Memeriksa overload dari fungsi PrintTo yang menerima tipe yang diberikan sebagai argumen pertama. Jika overload ada, mewarisi std::true_type, sebaliknya mewarisi std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to check. |
| Enable | Formal argument for SFINAE to work. |

## See Also

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.Slides](../../)