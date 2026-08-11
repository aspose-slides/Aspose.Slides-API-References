---
title: set_Mode()
second_title: مرجع API Aspose.Slides برای C++
description: حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش ارجاع‌های شیء مرجع را تغییر دهد.
type: docs
weight: 183
url: /fa/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) متد


حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش ارجاع‌های شیء مرجع را تغییر دهد.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | حالت جدید اشاره‌گر. 
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
این مثال کد خروجی زیر را تولید می‌کند:
تعداد اشاره‌گرهای مشترک: 1
تعداد اشاره‌گرهای مشترک: 2
حالت به System::SmartPtrMode::Weak تغییر خواهد یافت
حالت به System::SmartPtrMode::Weak تغییر کرده است
حالت به System::SmartPtrMode::Weak تغییر خواهد یافت
~Item()
حالت به System::SmartPtrMode::Weak تغییر کرده است
اشاره‌گر به یک نمونه از کلاس Item منقضی شده است: True
*/
``` |

## مراجع

* enum [SmartPtrMode](../../smartptrmode/)
* کلاس [SmartPtr](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)