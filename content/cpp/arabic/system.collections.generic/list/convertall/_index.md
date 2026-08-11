---
title: ConvertAll()
second_title: مرجع Aspose.Slides للـ C++ API
description: ينشئ قائمة من العناصر المحوّلة إلى نوع مختلف.
type: docs
weight: 352
url: /ar/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) طريقة

ينشئ قائمة من العناصر التي تم تحويلها إلى نوع مختلف.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| OutputType | نوع عنصر القائمة الناتج. |

### المعطيات

| معلمة | النوع | الوصف |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | المحوّل المستخدم لتحويل العناصر. |

### قيمة الإرجاع

قائمة جديدة تم إنشاؤها من العناصر المحوّلة.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [Converter](../../../system/converter/)
* فئة [List](../)
* مساحة الاسم [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)