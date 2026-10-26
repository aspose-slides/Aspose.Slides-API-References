---
title: set_Mode()
second_title: Aspose.Slides C++ API 参考
description: 设置指针模式。可能会更改被引用对象的引用计数。
type: docs
weight: 183
url: /zh/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) 方法

设置指针模式。可能会更改被引用对象的引用计数。

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针的新模式。 
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
此代码示例产生以下输出：
共享指针数量: 1
共享指针数量: 2
模式将被更改为 System::SmartPtrMode::Weak
模式已被更改为 System::SmartPtrMode::Weak
模式将被更改为 System::SmartPtrMode::Weak
~Item()
模式已被更改为 System::SmartPtrMode::Weak
Item 类实例的指针已过期: True
*/
``` |

## 另请参见

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)