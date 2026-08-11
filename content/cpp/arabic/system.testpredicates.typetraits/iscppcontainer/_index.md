---
title: IsCppContainer
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يتحقق مما إذا كان النوع المحدد حاوية ذات نمط STL. للقيام بذلك، يتحقق من وجود نوعي العضو iterator و const_iterator. إذا كان كلاهما موجودًا، يرث std::true_type، وإلا يرث std::false_type."
type: docs
weight: 40
url: /ar/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer بنية

يتحقق مما إذا كان النوع المحدد حاوية على نمط STL. للقيام بذلك، يتحقق من وجود نوعي العضو iterator و const_iterator. إذا كان كلاهما موجودًا، يرث std::true_type، وإلا يرث std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع للتحقق منه. |
| Enable | الحجة الرسمية لتمكين SFINAE. |

## انظر أيضًا

* نطاق [System::TestPredicates::TypeTraits](../)
* مكتبة [Aspose.Slides](../../)