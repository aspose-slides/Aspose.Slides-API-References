---
title: Delegate()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: منشئ افتراضي. يُنشئ كائن الـ delegate الذي لا يشير إلى أي شيء.
type: docs
weight: 1
url: /ar/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() طريقة


منشئ افتراضي. يُنشئ كائن الـ delegate الذي لا يشير إلى أي شيء.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) طريقة




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) طريقة


منشئ نسخة نقلي. يأخذ ملكية الكيان الذي يُشير إليه الـ delegate المحدد.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| o | Delegate\&& | كائن Delegate لنقل الكيان المشار إليه منه |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) طريقة


منشئ. يُنشئ كائن delegate من المؤشر المحدد إلى دالة حرة أو طريقة ثابتة.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


### معلمات القالب

| معامل | وصف |
| --- | --- |
| The | نوع المؤشر إلى الدالة أو الطريقة الثابتة الذي يقبله المنشئ كوسيطة |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| function | T | مؤشر إلى دالة أو طريقة ثابتة سيُشير إليها كائن Delegate الذي تم إنشاؤه حديثاً |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) طريقة


منشئ. يُنشئ delegate من المؤشر المحدد إلى كائن الدالة المولّد بواسطة std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


### معلمات القالب

| معامل | وصف |
| --- | --- |
| The | نوع كائن الدالة المولّد بواسطة std::bind() الذي يقبله المنشئ كوسيطة |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| function | T | مؤشر إلى “تعبير ربط” - مؤشر دالة تم توليده بواسطة std::bind() - سيُشير إليه كائن Delegate الذي تم إنشاؤه حديثاً |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) طريقة


منشئ. يُنشئ delegate من كائن الدالة المحدد.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


### معلمات القالب

| معامل | وصف |
| --- | --- |
| T | نوع كائن الدالة الذي يقبله المنشئ كوسيطة |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| functor_tag | int | قيمة عددية وهمية؛ يُستخدم هذا الوسيط لحل الغموض |
| functor | T\& | كائن دالة سيُشير إليه الـ delegate الجديد المُنشأ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) طريقة


منشئ نقلي. يُنشئ delegate من كائن الدالة المحدد.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


### معلمات القالب

| معامل | وصف |
| --- | --- |
| T | نوع كائن الدالة الذي يقبله المنشئ كوسيطة |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| functor_tag | long | قيمة عددية وهمية؛ يُستخدم هذا الوسيط لحل الغموض |
| functor | T\&& | كائن دالة سيُشير إليه الـ delegate الجديد المُنشأ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) طريقة


منشئ. يُنشئ delegate يشير إلى الطريقة غير الثابتة المحددة للكائن المحدد.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


### معلمات القالب

| معامل | وصف |
| --- | --- |
| MemberType | نوع الطريقة غير الثابتة التي يقبلها المنشئ كوسيطة |
| ClassType | نوع الكائن الذي يقبله المنشئ كوسيطة |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| member | MemberType ClassType::* | مؤشر إلى الطريقة غير الثابتة التي سيُشير إليها الـ delegate الجديد المُنشأ |
| obj | ClassType * | مؤشر إلى كائن عضو سيتوجه إليه الـ delegate الجديد المُنشأ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) طريقة


منشئ. يُنشئ delegate يشير إلى الطريقة غير الثابتة المحددة للكائن المحدد.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


### معلمات القالب

| معامل | وصف |
| --- | --- |
| MemberType | نوع الطريقة غير الثابتة التي يقبلها المنشئ كوسيطة |
| ClassType | نوع الكائن الذي يقبله المنشئ كوسيطة |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| member | MemberType MemberClass::* | مؤشر إلى الطريقة غير الثابتة التي سيُشير إليها الـ delegate الجديد المُنشأ |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | مؤشر مشترك إلى كائن عضو سيتوجه إليه الـ delegate الجديد المُنشأ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) طريقة


يُنشئ كائن delegate يشير إلى كائن دالة std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


### معلمات القالب

| معامل | وصف |
| --- | --- |
| R | نوع القيمة المرجعة لكائن الدالة الذي يقبله المنشئ كوسيطة |
| Args | قائمة الوسائط لكائن الدالة الذي يقبله المنشئ كوسيطة |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| f | std::function\<R(Args...)> | كائن دالة سيُشير إليه كائن delegate الذي تم إنشاؤه حديثاً |

## انظر أيضاً

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Delegate< ReturnType(ArgumentTypes...)>](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)