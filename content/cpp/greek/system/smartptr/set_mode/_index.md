---
title: set_Mode()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τις μετρήσεις αναφοράς του αναφερθέντος αντικειμένου.
type: docs
weight: 183
url: /el/system/smartptr/set_mode/
---
## SmartPtr::set_Mode(SmartPtrMode) μέθοδος


Ορίζει τη λειτουργία του δείκτη. Μπορεί να αλλάξει τις μετρήσεις αναφοράς του αντικειμένου.

```cpp
void System::SmartPtr<T>::set_Mode(SmartPtrMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Νέα λειτουργία του δείκτη. 
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
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Αριθμός κοινών δεικτών: 1
Αριθμός κοινών δεικτών: 2
Η λειτουργία θα αλλάξει σε System::SmartPtrMode::Weak
Η λειτουργία έχει αλλάξει σε System::SmartPtrMode::Weak
Η λειτουργία θα αλλάξει σε System::SmartPtrMode::Weak
~Item()
Η λειτουργία έχει αλλάξει σε System::SmartPtrMode::Weak
Ο δείκτης σε μια παρουσία της κλάσης Item έληξε: True
*/
``` |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)