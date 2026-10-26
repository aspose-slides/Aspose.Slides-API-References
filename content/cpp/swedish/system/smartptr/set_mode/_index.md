---
title: set_Mode()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in pekarläget. Kan ändra det refererade objektets referensräkningar.
type: docs
weight: 183
url: /sv/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) metod

Ställer in pekarläget. Kan ändra det refererade objektets referensräkningar.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Nytt läge för pekaren.
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
Det här kodexemplet ger följande utskrift:
Antal delade pekare: 1
Antal delade pekare: 2
Läget kommer att ändras till System::SmartPtrMode::Weak
Läget har ändrats till System::SmartPtrMode::Weak
Läget kommer att ändras till System::SmartPtrMode::Weak
~Item()
Läget har ändrats till System::SmartPtrMode::Weak
Pekaren till en instans av Item-klassen har löpt ut: True
*/
``` |

## Se också

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)