---
title: set_Mode()
second_title: Aspose.Slides for C++ API Reference
description: Sets pointer mode. May alter referenced object's reference counts.
type: docs
weight: 183
url: /system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) method


Sets pointer mode. May alter referenced object's reference counts.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | New mode of pointer. 
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
This code example produces the following output:
Number of shared pointers: 1
Number of shared pointers: 2
The mode will be changed to System::SmartPtrMode::Weak
The mode has been changed to System::SmartPtrMode::Weak
The mode will be changed to System::SmartPtrMode::Weak
~Item()
The mode has been changed to System::SmartPtrMode::Weak
The pointer to an instance of the Item class expired: True
*/
``` |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)