---
title: EventHandler
second_title: Aspose.Slides for C++ API Reference
description: "Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 781
url: /cpp/system/eventhandler/
---
## EventHandler class


Represents a method that reacts to and processes an event. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<class TEventArgs>class EventHandler : public System::MulticastDelegate<void(System::SharedPtr<Object>, SharedPtr<EventArgs>)>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TEventArgs | The type of the argument that represents the context of the event |
## Methods

| Method | Description |
| --- | --- |
|  [EventHandler](./eventhandler/)() | Constructor. |
|  [EventHandler](./eventhandler/)(std::nullptr_t) | Null-object constructor. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
