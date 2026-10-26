---
title: Predicate
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक प्रेडिकेट का पॉइंटर दर्शाता है - एक इनवोकेबल इकाई जो एकल तर्क लेती है और एक bool मान लौटाती है।
type: docs
weight: 4187
url: /hi/system/predicate/
---
## Predicate टाइपडिफ

एक प्रेडिकेट का पॉइंटर दर्शाता है - एक इनवोकेबल एंटिटी जो एकल तर्क लेती है और एक bool मान लौटाती है।

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## टिप्पणी

```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // ऐरे को भरें।
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // एक प्रेडिकेट बनाएं जो 3 से बड़े ऐरे तत्व को वापस करता है।
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // बनाए गए प्रेडिकेट का उपयोग करके ऐरे का पहला तत्व खोजें और उसे प्रिंट करें।
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
5
*/
```

## देखें भी

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)