---
title: set_Mode()
second_title: Aspose.Slides C++ API hivatkozása
description: Beállítja a pointer módját. Megváltoztathatja a hivatkozott objektum referenciaszámlálóit.
type: docs
weight: 183
url: /hu/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) metódus


Beállítja a pointer módját. Megváltoztathatja a hivatkozott objektum referenciaszámlálóit.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Új pointer mód.
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
Ez a kódpélda a következő kimenetet állítja elő:
Megosztott pointerek száma: 1
Megosztott pointerek száma: 2
A módot a System::SmartPtrMode::Weak értékre változtatják
A módot megváltoztatták a System::SmartPtrMode::Weak értékre
A módot a System::SmartPtrMode::Weak értékre változtatják
~Item()
A módot megváltoztatták a System::SmartPtrMode::Weak értékre
Az Item osztály egy példányára mutató pointer lejárt: True
*/
``` |

## Lásd még

* Enum [SmartPtrMode](../../smartptrmode/)
* Osztály [SmartPtr](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)