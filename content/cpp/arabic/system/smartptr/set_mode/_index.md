---
title: set_Mode()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط وضع المؤشر. قد يغيّر عدّات الإشارة للكائن المشار إليه.
type: docs
weight: 183
url: /ar/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) طريقة

يضبط وضع المؤشر. قد يغيّر عدّات الإشارة للكائن المشار إليه.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | الوضع الجديد للمؤشر.
```cpp
#include "system/smart_ptr.h"
#include <iostream>

class Item final : public System::Object
{
public:
  ~Item() final
  {
    std::cout << "~Item()" << std::endl;
  }
};

using ItemPtr = System::SmartPtr<Item>;

void PrintSharedCount(ItemPtr &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

void ChangeModeToWeak(ItemPtr &ptr)
{
  std::cout << "The mode will be changed to System::SmartPtrMode::Weak" << std::endl;
  ptr.set_Mode(System::SmartPtrMode::Weak);
  std::cout << "The mode has been changed to System::SmartPtrMode::Weak" << std::endl;
}

int main()
{
  ItemPtr ptr1 = System::MakeObject<Item>();
  ItemPtr ptr2{ptr1, System::SmartPtrMode::Weak};
  PrintSharedCount(ptr1);

  ptr2.set_Mode(System::SmartPtrMode::Shared);
  PrintSharedCount(ptr1);

  ChangeModeToWeak(ptr1);
  ChangeModeToWeak(ptr2);
  std::cout <<
    "The pointer to an instance of the Item class expired: " <<
    (static_cast<System::WeakPtr<ItemPtr::Pointee_>>(ptr1).expired() ? "True" : "False") <<
    std::endl;

  return 0;
}
/*
مثال الشيفرة هذا ينتج الإخراج التالي:
عدد مؤشرات المشاركة: 1
عدد مؤشرات المشاركة: 2
سيتم تغيير الوضع إلى System::SmartPtrMode::Weak
تم تغيير الوضع إلى System::SmartPtrMode::Weak
سيتم تغيير الوضع إلى System::SmartPtrMode::Weak
~Item()
تم تغيير الوضع إلى System::SmartPtrMode::Weak
المؤشر إلى كائن من فئة Item انتهى صلاحيته: True
*/
``` |

## انظر أيضًا

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* المكتبة [Aspose.Slides](../../../)