---
title: IterateOver()
second_title: مرجع API Aspose.Slides للغة C++
description: "هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable بدون أساليب begin()، end() مع معامل نوع الهدف لـ (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /ar/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) الدالة

هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable بدون أساليب begin()، end() مع معامل نوع الهدف لـ (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الهدف، يجب إرجاعه من iterator |
| Enumerable | نوع الكائن المغلف |

## System::IterateOver(System::SmartPtr\<Enumerable\>) الدالة

هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable بدون أساليب begin()، end() مع معامل نوع الهدف الافتراضي لـ (auto& value : IterateOver(enumerable)) مماثل للكود التالي في C# foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Enumerable | نوع الكائن المغلف |

## System::IterateOver(System::SmartPtr\<Enumerable\>) الدالة

هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامه مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable مع أساليب begin()، end() مع معامل نوع الهدف الافتراضي لـ (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Enumerable | نوع الكائن المغلف |

## System::IterateOver(System::SmartPtr\<Enumerable\>) الدالة

هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامها مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable مع أساليب begin()، end() مع نوع الهدف نفسه كنوع value_type الأصلي للـ iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Enumerable | نوع الكائن المغلف |
| T | نوع الهدف الذي يجب إرجاعه من iterator |

## System::IterateOver(System::SmartPtr\<Enumerable\>) الدالة

هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامها مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable مع أساليب begin()، end() مع نوع هدف مختلف ونوع value_type الأصلي للـ iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Enumerable | نوع الكائن المغلف |
| T | نوع الهدف الذي يجب إرجاعه من iterator |

## System::IterateOver(const Enumerable *) الدالة

هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامها مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable مع نوع الهدف الافتراضي.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Enumerable | نوع الكائن المغلف |

## System::IterateOver(const Enumerable *) الدالة

هذه الخاصية الدالة تُغلف كائنًا قابلًا للتعداد (أو قابلًا للتكرار) بحيث يمكن استخدامها مع حلقة for المستندة إلى النطاق. هذا التحميل الزائد لـ Enumerable بدون أساليب begin()، end() مع معامل نوع الهدف لـ (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الهدف، يجب إرجاعه من iterator |
| Enumerable | نوع الكائن المغلف |

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* البنية [IsSmartPtr](../issmartptr/)
* مساحة الأسماء [System](../)
* المكتبة [Aspose.Slides](../../)