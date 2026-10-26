---
title: set_Mode()
second_title: Aspose.Slides für C++ API Referenz
description: Setzt den Zeigermodus. Kann die Referenzzählungen des referenzierten Objekts ändern.
type: docs
weight: 183
url: /de/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) Methode

Setzt den Zeigermodus. Kann die Referenzzählungen des referenzierten Objekts ändern.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Neuer Modus des Zeigers. 
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
Dieses Code-Beispiel erzeugt die folgende Ausgabe:
Anzahl der geteilten Zeiger: 1
Anzahl der geteilten Zeiger: 2
Der Modus wird zu System::SmartPtrMode::Weak geändert
Der Modus wurde zu System::SmartPtrMode::Weak geändert
Der Modus wird zu System::SmartPtrMode::Weak geändert
~Item()
Der Modus wurde zu System::SmartPtrMode::Weak geändert
Der Zeiger auf eine Instanz der Klasse Item ist abgelaufen: True
*/
``` |

## Siehe auch

* Aufzählung [SmartPtrMode](../../smartptrmode/)
* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)