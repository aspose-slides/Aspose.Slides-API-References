---
title: set_Mode()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定指標模式。可能會改變被參照物件的參考計數。
type: docs
weight: 183
url: /zh-hant/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) 方法

設定指標模式。可能會改變被參照物件的參考計數。

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | 指標的新模式。```cpp
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
此程式碼範例會產生以下輸出：
共享指標的數量： 1
共享指標的數量： 2
模式將被更改為 System::SmartPtrMode::Weak
模式已被更改為 System::SmartPtrMode::Weak
模式將被更改為 System::SmartPtrMode::Weak
~Item()
模式已被更改為 System::SmartPtrMode::Weak
Item 類別的實例指標已過期： True
*/
``` |

## 另請參閱

* 列舉 [SmartPtrMode](../../smartptrmode/)
* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)