---
title: set_Mode()
second_title: Aspose.Slides for C++ APIリファレンス
description: ポインタモードを設定します。参照対象オブジェクトの参照カウントが変更される可能性があります。
type: docs
weight: 183
url: /ja/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) メソッド


ポインタのモードを設定します。参照対象オブジェクトの参照カウントが変更される可能性があります。

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタの新しいモード。 
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
このコード例は以下の出力を生成します:
共有ポインタの数: 1
共有ポインタの数: 2
モードは System::SmartPtrMode::Weak に変更されます
モードは System::SmartPtrMode::Weak に変更されました
モードは System::SmartPtrMode::Weak に変更されます
~Item()
モードは System::SmartPtrMode::Weak に変更されました
Item クラスのインスタンスへのポインタが期限切れです: True
*/
``` |

## 参照

* 列挙体 [SmartPtrMode](../../smartptrmode/)
* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)