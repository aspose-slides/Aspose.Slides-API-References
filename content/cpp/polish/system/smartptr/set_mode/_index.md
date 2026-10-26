---
title: set_Mode()
second_title: Aspose.Slides dla C++ Referencja API
description: Ustawia tryb wskaźnika. Może zmienić liczbę referencji referencjonowanego obiektu.
type: docs
weight: 183
url: /pl/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) metoda


Ustawia tryb wskaźnika. Może zmienić liczby referencji referencjonowanego obiektu.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Nowy tryb wskaźnika. 
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
Ten przykład kodu generuje następujący wynik:
Liczba współdzielonych wskaźników: 1
Liczba współdzielonych wskaźników: 2
Tryb zostanie zmieniony na System::SmartPtrMode::Weak
Tryb został zmieniony na System::SmartPtrMode::Weak
Tryb zostanie zmieniony na System::SmartPtrMode::Weak
~Item()
Tryb został zmieniony na System::SmartPtrMode::Weak
Wskaźnik do instancji klasy Item wygasł: True
*/
``` |

## Zobacz także

* Wyliczenie [SmartPtrMode](../../smartptrmode/)
* Klasa [SmartPtr](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)