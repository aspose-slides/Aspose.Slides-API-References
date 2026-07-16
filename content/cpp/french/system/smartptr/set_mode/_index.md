---
title: set_Mode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le mode du pointeur. Peut modifier les comptes de références de l'objet référencé.
type: docs
weight: 183
url: /fr/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) méthode

Définit le mode du pointeur. Peut modifier les comptes de références de l'objet référencé.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Nouveau mode du pointeur. 
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
Cet exemple de code produit la sortie suivante :
Nombre de pointeurs partagés : 1
Nombre de pointeurs partagés : 2
Le mode sera changé en System::SmartPtrMode::Weak
Le mode a été changé en System::SmartPtrMode::Weak
Le mode sera changé en System::SmartPtrMode::Weak
~Item()
Le mode a été changé en System::SmartPtrMode::Weak
Le pointeur vers une instance de la classe Item a expiré : True
*/
``` |

## Voir aussi

* Énum [SmartPtrMode](../../smartptrmode/)
* Classe [SmartPtr](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)