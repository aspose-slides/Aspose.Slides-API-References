---
title: Action
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डेलीगेट प्रकार जो उन विधियों को संदर्भित करता है जिनका कोई रिटर्न वैल्यू नहीं है।
type: docs
weight: 3602
url: /hi/system/action/
---
## Action टाइपडिफ


Delegate type that references methods that have no return value.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## टिप्पणियाँ


```cpp
#include <system/action.h>

using namespace System;

// पारित स्ट्रिंग को प्रिंट करने वाला फ़ंक्शन।
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Action का एक इंस्टेंस बनाएँ।
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // एक्शन को कॉल करें।
  action(u"Hello, world!");

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
नमस्ते, दुनिया!
*/
```

## संबंधित देखें

* Namespace [System](../)
* Library [Aspose.Slides](../../)