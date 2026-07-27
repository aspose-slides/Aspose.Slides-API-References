---
title: set_Mode()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el modo del puntero. Puede alterar los recuentos de referencias del objeto referenciado.
type: docs
weight: 183
url: /es/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) método


Establece el modo del puntero. Puede alterar los recuentos de referencias del objeto referenciado.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Nuevo modo del puntero. 
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
Este ejemplo de código produce la siguiente salida:
Número de punteros compartidos: 1
Número de punteros compartidos: 2
El modo se cambiará a System::SmartPtrMode::Weak
El modo ha sido cambiado a System::SmartPtrMode::Weak
El modo se cambiará a System::SmartPtrMode::Weak
~Item()
El modo ha sido cambiado a System::SmartPtrMode::Weak
El puntero a una instancia de la clase Item expiró: True
*/
``` |

## Ver también

* Enumeración [SmartPtrMode](../../smartptrmode/)
* Clase [SmartPtr](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)