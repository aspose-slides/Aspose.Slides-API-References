---
title: SmartPtr()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن SmartPtr بالوضع المطلوب.
type: docs
weight: 1
url: /ar/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) المُنشئ

ينشئ كائن [SmartPtr](../) بالوضع المطلوب.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | وضع المؤشر. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) المُنشئ

ينشئ كائن [SmartPtr](../) مؤشر فارغ بالوضع المطلوب.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mode | std::nullptr_t | وضع المؤشر. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) المُنشئ

ينشئ [SmartPtr](../) يشير إلى الكائن المحدد، أو يحول المؤشر الخام إلى [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | الكائن المشار إليه. |
| mode | [SmartPtrMode](../../smartptrmode/) | وضع المؤشر. |

## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) المُنشئ

ينشئ كائن [SmartPtr](../) بنسخة. كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | المؤشر للنسخ. |
| mode | [SmartPtrMode](../../smartptrmode/) | وضع المؤشر. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) المُنشئ

ينشئ كائن [SmartPtr](../) بنسخة. كلا المؤشرين يشيران إلى نفس الكائن بعد ذلك. يقوم بالتحويل النوعي إذا كان مسموحًا.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Q | نوع الكائن الذي يشيره x. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | المؤشر للنسخ. |
| mode | [SmartPtrMode](../../smartptrmode/) | وضع المؤشر. |

## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) المُنشئ

ينشئ كائن [SmartPtr](../) بنقل. فعليًا، يبدل المؤشرين إذا كانا من نفس الوضع. قد يصبح x غير قابل للاستخدام بعد الاستدعاء.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | المؤشر للنقل. |
| mode | [SmartPtrMode](../../smartptrmode/) | وضع المؤشر. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) المُنشئ

يحوِّل نوع المصفوفة المشار إليها بإنشاء مصفوفة جديدة من نوع مختلف. مفيد إذا كان في C# هناك تحويل نوع مصفوفة غير مدعوم في C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Y | نوع مصفوفة المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | المؤشر إلى المصفوفة لإنشاء نسخة منها، لكن بنوع عناصر مختلف. |
| mode | [SmartPtrMode](../../smartptrmode/) | وضع المؤشر. |

## SmartPtr::SmartPtr(const Y\&) المُنشئ

يُهيئ مصفوفة فارغة. يُستخدم لترجمة بعض بنى كود C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Y | عنصر نائب من نوع EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) المُنشئ

يبني [SmartPtr](../) يشارك معلومات الملكية مع القيمة الأولية لـ ptr، لكنه يحتفظ بمؤشر غير مرتبط وغير مُدار p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | مؤشر ذكي آخر لمشاركة الملكية من الملكية. |
| p | [Pointee_](../pointee_/) * | مؤشر إلى كائن لإدارته. |
| mode | [SmartPtrMode](../../smartptrmode/) | وضع المؤشر. |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// هذه الفئة تحتوي على حقل سيتم طباعته.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// هذه الفئة تحتوي على نسخة من الفئة Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// يُستخدم لطباعة سلسلة من نسخة فئة Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// يطبع عدد المؤشرات المشتركة التي تشير إلى الكائن.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // إنشاء SharedPtr لنسخة من الفئة Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // إنشاء SharedPtr سيشير إلى حقل نسخة الفئة Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // اجعل مؤشر 'bar' يشير إلى nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // ما زال bar->data موجودًا ومؤشر 'foo' صالحًا.
  PrintMessage(foo);

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرج التالي:
عدد المؤشرات المشتركة: 1
عدد المؤشرات المشتركة: 2
عدد المؤشرات المشتركة: 0
مرحبا، عالم!
*/
``` |

## انظر أيضًا

* تعداد [SmartPtrMode](../../smartptrmode/)
* تعريف نوع [Pointee_](../pointee_/)
* تعريف نوع [SmartPtr_](../smartptr_/)
* فئة [SmartPtr](../)
* فئة [Array](../../array/)
* مساحة الأسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)