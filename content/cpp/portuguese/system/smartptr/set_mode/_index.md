---
title: set_Mode()
second_title: Referência da API Aspose.Slides para C++
description: Define o modo do ponteiro. Pode alterar as contagens de referência do objeto referenciado.
type: docs
weight: 183
url: /pt/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) método


Define o modo do ponteiro. Pode alterar as contagens de referência do objeto referenciado.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Novo modo do ponteiro. 
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
Este exemplo de código produz a seguinte saída:
Número de ponteiros compartilhados: 1
Número de ponteiros compartilhados: 2
O modo será alterado para System::SmartPtrMode::Weak
O modo foi alterado para System::SmartPtrMode::Weak
O modo será alterado para System::SmartPtrMode::Weak
~Item()
O modo foi alterado para System::SmartPtrMode::Weak
O ponteiro para uma instância da classe Item expirou: True
*/
``` |

## Ver Também

* Enum [SmartPtrMode](../../smartptrmode/)
* Classe [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)