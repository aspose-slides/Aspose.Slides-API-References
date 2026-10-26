---
title: has_print_to_method
second_title: Aspose.Slides لمرجع API C++
description: "يتحقق من وجود تحميل زائد لدالة PrintTo التي تقبل النوع المحدد كمعامل أول. إذا كان هناك تحميل زائد، يرث std::true_type، وإلا يرث std::false_type."
type: docs
weight: 27
url: /ar/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

يتحقق من وجود تحميل زائد لدالة PrintTo التي تقبل النوع المحدد كمعامل أول. إذا كان هناك تحميل زائد، يرث std::true_type، وإلا يرث std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | النوع للتحقق منه. |
| Enable | معامل رسمي لجعل SFINAE يعمل. |

## انظر أيضًا

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.Slides](../../)