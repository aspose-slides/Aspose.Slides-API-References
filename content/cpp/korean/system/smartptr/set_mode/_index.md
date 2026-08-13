---
title: set_Mode()
second_title: Aspose.Slides for C++ API 참조
description: 포인터 모드를 설정합니다. 참조된 객체의 참조 카운트를 변경할 수 있습니다.
type: docs
weight: 183
url: /ko/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) 메서드

포인터 모드를 설정합니다. 참조된 객체의 참조 카운트를 변경할 수 있습니다.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | 포인터의 새 모드.
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
이 코드 예제는 다음 출력 결과를 생성합니다:
공유 포인터 수: 1
공유 포인터 수: 2
모드는 System::SmartPtrMode::Weak 로 변경됩니다
모드가 System::SmartPtrMode::Weak 로 변경되었습니다
모드는 System::SmartPtrMode::Weak 로 변경됩니다
~Item()
모드가 System::SmartPtrMode::Weak 로 변경되었습니다
Item 클래스 인스턴스에 대한 포인터가 만료되었습니다: True
*/
``` |

## 참고

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)