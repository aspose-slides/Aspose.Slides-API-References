---
title: EventHandler
second_title: Aspose.Slides for C++ API Reference
description: "Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 3186
url: /system/eventhandler/
---
## EventHandler typedef


Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)