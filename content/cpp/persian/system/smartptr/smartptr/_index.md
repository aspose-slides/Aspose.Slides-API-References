---
title: SmartPtr()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء SmartPtr با حالت مورد نیاز ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) سازنده

یک شی [SmartPtr](../) با حالت مورد نیاز ایجاد می‌کند.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت اشاره‌گر. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) سازنده

یک شی [SmartPtr](../) با حالت مورد نیاز و اشاره‌گر null ایجاد می‌کند.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| mode | std::nullptr_t | حالت اشاره‌گر. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) سازنده

یک [SmartPtr](../) که به شی تعیین‌شده اشاره می‌کند ایجاد می‌کند، یا اشاره‌گر خام را به [SmartPtr](../) تبدیل می‌کند.

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | شی اشاره‌شده. |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت اشاره‌گر. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) سازنده

یک شی [SmartPtr](../) را با کپی‌سازی ایجاد می‌کند. هر دو اشاره‌گر پس از آن به یک شی یکسان اشاره می‌کنند.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | اشاره‌گر برای کپی. |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت اشاره‌گر. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) سازنده

یک شی [SmartPtr](../) را با کپی‌سازی ایجاد می‌کند. هر دو اشاره‌گر پس از آن به یک شی یکسان اشاره می‌کنند. در صورت امکان، تبدیل نوع انجام می‌دهد.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Q | نوع شی‌ای که x به آن اشاره می‌کند. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | اشاره‌گر برای کپی. |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت اشاره‌گر. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) سازنده

یک شی [SmartPtr](../) را با انتقال ایجاد می‌کند. به طور مؤثر دو اشاره‌گر را تعویض می‌کند، اگر هر دو حالت یکسان داشته باشند. پس از فراخوانی، ممکن است x غیرقابل استفاده باشد.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | اشاره‌گر برای انتقال. |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت اشاره‌گر. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) سازنده

نوع آرایه مرجع را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید است اگر در C# تبدیل نوع آرایه‌ای وجود داشته باشد که در C++ پشتیبانی نمی‌شود.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Y | نوع آرایه منبع. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | اشاره‌گر به آرایه‌ای که کپی آن ایجاد می‌شود، اما با نوع متفاوتی از عناصر. |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت اشاره‌گر. |

## SmartPtr::SmartPtr(const Y&) سازنده

آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Y | محل‌نگهدارنده نوع EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) سازنده

یک [SmartPtr](../) می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر جداگانه و بدون مدیریت p را نگه می‌دارد.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | یک اشاره‌گر هوشمند دیگر برای به‌اشتراک‌گذاری مالکیت از. |
| p | [Pointee_](../pointee_/) * | اشاره‌گر به شی برای مدیریت. |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت اشاره‌گر. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// این کلاس دارای یک فیلد است که چاپ خواهد شد.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// این کلاس حاوی یک نمونه از کلاس Foo است.
class Bar : public System::Object
{
public:
  Foo data;
};

// برای چاپ رشته‌ای از نمونه کلاس Foo استفاده می‌شود.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// تعداد اشاره‌گرهای shared که به شی اشاره می‌کنند را چاپ می‌کند.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // یک SharedPtr برای یک نمونه از کلاس Bar ایجاد می‌کند.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // یک SharedPtr ایجاد می‌کند که به فیلد نمونه کلاس Bar اشاره می‌کند.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // اشاره‌گر 'bar' را به nullptr تنظیم می‌کند.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data هنوز وجود دارد و اشاره‌گر 'foo' معتبر است.
  PrintMessage(foo);

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
تعداد اشاره‌گرهای shared: 1
تعداد اشاره‌گرهای shared: 2
تعداد اشاره‌گرهای shared: 0
سلام، دنیا!
*/
``` |

## مراجع

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)