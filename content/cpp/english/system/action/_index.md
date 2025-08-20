---
title: Action
second_title: Aspose.Slides for C++ API Reference
description: Delegate type that references methods that have no return value.
type: docs
weight: 3277
url: /system/action/
---
## Action typedef


Delegate type that references methods that have no return value.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Remarks



```cpp
#include <system/action.h>

using namespace System;

// The function that prints the passed string.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Create an instance of Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Call the action.
  action(u"Hello, world!");

  return 0;
}
/*
This code example produces the following output:
Hello, world!
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)