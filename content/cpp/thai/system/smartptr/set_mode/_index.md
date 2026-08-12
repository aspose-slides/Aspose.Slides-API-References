---
title: set_Mode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าโหมดของตัวชี้ อาจทำให้จำนวนการอ้างอิงของอ็อบเจ็กต์ที่ถูกอ้างอิงเปลี่ยนแปลง
type: docs
weight: 183
url: /th/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) เมธอด

ตั้งค่าโหมดของตัวชี้ อาจทำให้จำนวนการอ้างอิงของอ็อบเจ็กต์ที่ถูกอ้างอิงเปลี่ยนแปลง

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดใหม่ของตัวชี้. ```cpp
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
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
จำนวนตัวชี้ที่แชร์: 1
จำนวนตัวชี้ที่แชร์: 2
โหมดจะถูกเปลี่ยนเป็น System::SmartPtrMode::Weak
โหมดได้ถูกเปลี่ยนเป็น System::SmartPtrMode::Weak
โหมดจะถูกเปลี่ยนเป็น System::SmartPtrMode::Weak
~Item()
โหมดได้ถูกเปลี่ยนเป็น System::SmartPtrMode::Weak
ตัวชี้ไปยังอินสแตนซ์ของคลาส Item หมดอายุ: True
*/
``` |

## ดูเพิ่มเติม

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)