---
title: set_Mode()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur mode pointer. Dapat mengubah hitungan referensi objek yang dirujuk.
type: docs
weight: 183
url: /id/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) metode

Mengatur mode pointer. Dapat mengubah hitungan referensi objek yang dirujuk.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode baru pointer. 
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
Contoh kode ini menghasilkan output berikut:
Jumlah pointer bersama: 1
Jumlah pointer bersama: 2
Mode akan diubah menjadi System::SmartPtrMode::Weak
Mode telah diubah menjadi System::SmartPtrMode::Weak
Mode akan diubah menjadi System::SmartPtrMode::Weak
~Item()
Mode telah diubah menjadi System::SmartPtrMode::Weak
Pointer ke sebuah instance dari kelas Item telah kedaluwarsa: True
*/
``` |

## Lihat Juga

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)