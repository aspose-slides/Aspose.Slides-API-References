---
title: set_Mode()
second_title: Aspose.Slides का C++ API संदर्भ
description: पॉइंटर मोड सेट करता है। संदर्भित ऑब्जेक्ट की रेफ़रेंस काउंट को बदल सकता है।
type: docs
weight: 183
url: /hi/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) मेथड


पॉइंटर मोड सेट करता है। संदर्भित ऑब्जेक्ट की रेफ़रेंस काउंट को बदल सकता है।

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | पॉइंटर का नया मोड। 
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
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
साझा पॉइंटर्स की संख्या: 1
साझा पॉइंटर्स की संख्या: 2
मोड को System::SmartPtrMode::Weak में बदल दिया जाएगा
मोड को System::SmartPtrMode::Weak में बदल दिया गया है
मोड को System::SmartPtrMode::Weak में बदल दिया जाएगा
~Item()
मोड को System::SmartPtrMode::Weak में बदल दिया गया है
Item क्लास की एक इंस्टेंस का पॉइंटर समाप्त हो गया है: True
*/
``` |

## संबंधित देखें

* एनम [SmartPtrMode](../../smartptrmode/)
* क्लास [SmartPtr](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)