---
title: has_method_compareto_shared_ptr
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يتحقق مما إذا كانت طريقة CompareTo(SharedPtr<T>) موجودة في النوع المحدد. إذا كان الأمر كذلك، يرث std::true_type، وإلا يرث std::false_type. يمكن استخدامها في std::enable_if."
type: docs
weight: 183
url: /ar/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr بنية

يتحقق مما إذا كانت طريقة CompareTo(SharedPtr<T>) موجودة في النوع المحدد. إذا كان الأمر كذلك، يرث std::true_type، وإلا يرث std::false_type. يمكن استخدامها في std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```

### معامل القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع للتحقق من وجود طريقة Equals. |
| Sfinae | معامل قالب رسمي لعمل SFINAE. |

## انظر أيضًا

* النطاق [System::Collections::Generic::Details](../)
* المكتبة [Aspose.Slides](../../)