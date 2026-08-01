---
title: set_Mode()
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt de pointermodus in. Kan de referentietellingen van het verwezen object wijzigen.
type: docs
weight: 183
url: /nl/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) methode

Stelt de pointermodus in. Kan de referentietellingen van het verwezen object wijzigen.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Nieuwe modus van de pointer. 
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
Dit codevoorbeeld produceert de volgende output:
Aantal gedeelde pointers: 1
Aantal gedeelde pointers: 2
De modus wordt gewijzigd naar System::SmartPtrMode::Weak
De modus is gewijzigd naar System::SmartPtrMode::Weak
De modus wordt gewijzigd naar System::SmartPtrMode::Weak
~Item()
De modus is gewijzigd naar System::SmartPtrMode::Weak
De pointer naar een instantie van de Item-klasse is verlopen: True
*/
``` |

## Zie ook

* Enum [SmartPtrMode](../../smartptrmode/)
* Klasse [SmartPtr](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)