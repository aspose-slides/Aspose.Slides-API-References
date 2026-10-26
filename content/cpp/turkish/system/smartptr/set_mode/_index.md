---
title: set_Mode()
second_title: Aspose.Slides for C++ API Referansı
description: İşaretçi kipini ayarlar. Başvurulan nesnenin referans sayılarını değiştirebilir.
type: docs
weight: 183
url: /tr/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) metodu

İşaretçi kipini ayarlar. Başvurulan nesnenin referans sayısını değiştirebilir.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | İşaretçinin yeni modu. 
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
Bu kod örneği aşağıdaki çıktıyı üretir:
Paylaşımlı işaretçi sayısı: 1
Paylaşımlı işaretçi sayısı: 2
Mod System::SmartPtrMode::Weak olarak değiştirilecektir
Mod System::SmartPtrMode::Weak olarak değiştirildi
Mod System::SmartPtrMode::Weak olarak değiştirilecektir
~Item()
Mod System::SmartPtrMode::Weak olarak değiştirildi
Item sınıfının bir örnekine işaretçi süresi doldu: True
*/
``` |

## Bakınız

* Enum [SmartPtrMode](../../smartptrmode/)
* Sınıf [SmartPtr](../)
* İsimUzayı [System](../../)
* Library [Aspose.Slides](../../../)