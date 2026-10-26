---
title: TupleFactory
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ट्यूपल ऑब्जेक्ट बनाने के लिए स्थैतिक विधियाँ प्रदान करता है।
type: docs
weight: 1366
url: /hi/system/tuplefactory/
---
## TupleFactory क्लास

ट्यूपल ऑब्जेक्ट बनाने के लिए स्थैतिक विधियाँ प्रदान करता है।

```cpp
class TupleFactory
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | एक नया ट्यूपल ऑब्जेक्ट बनाता है। |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | एक नया 8-ट्यूपल बनाता है। 8वां तत्व [Tuple](../tuple/) के भीतर रखा जाता है। |
## टिप्पणियाँ



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
Item 1: 256
Item 2: 16
Item 3: 64
*/
```

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)