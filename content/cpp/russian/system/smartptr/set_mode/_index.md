---
title: set_Mode()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает режим указателя. Может изменить счётчики ссылок на объект.
type: docs
weight: 183
url: /ru/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) метод

Устанавливает режим указателя. Может изменить счётчики ссылок на объект.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Новый режим указателя. 
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
Этот пример кода выводит следующее:
Количество общих указателей: 1
Количество общих указателей: 2
Режим будет изменён на System::SmartPtrMode::Weak
Режим был изменён на System::SmartPtrMode::Weak
Режим будет изменён на System::SmartPtrMode::Weak
~Item()
Режим был изменён на System::SmartPtrMode::Weak
Указатель на экземпляр класса Item истек: True
*/
``` |

## См. также

* Перечисление [SmartPtrMode](../../smartptrmode/)
* Класс [SmartPtr](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)