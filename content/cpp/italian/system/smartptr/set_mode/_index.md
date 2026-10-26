---
title: set_Mode()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la modalità del puntatore. Può modificare i conteggi di riferimento dell'oggetto referenziato.
type: docs
weight: 183
url: /it/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) metodo

Imposta la modalità del puntatore. Può modificare i conteggi di riferimento dell'oggetto referenziato.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Nuova modalità del puntatore. 
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
Questo esempio di codice produce il seguente output:
Numero di puntatori condivisi: 1
Numero di puntatori condivisi: 2
La modalità verrà cambiata in System::SmartPtrMode::Weak
La modalità è stata cambiata in System::SmartPtrMode::Weak
La modalità verrà cambiata in System::SmartPtrMode::Weak
~Item()
La modalità è stata cambiata in System::SmartPtrMode::Weak
Il puntatore a un'istanza della classe Item è scaduto: True
*/
``` |

## Vedi anche

* Enum [SmartPtrMode](../../smartptrmode/)
* Classe [SmartPtr](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)