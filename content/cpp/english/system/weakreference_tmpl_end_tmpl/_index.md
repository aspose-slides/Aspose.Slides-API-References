---
title: WeakReference<>
second_title: Aspose.Slides for C++ API Reference
description: Represents a weak reference, which references an object while still allowing that object to be deleted.
type: docs
weight: 1470
url: /system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> class


Represents a weak reference, which references an object while still allowing that object to be deleted.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Gets an indication whether the object referenced by the current WeakReference object has been deleted. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Gets the object (the target) referenced by the current WeakReference object. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Sets the object (the target) referenced by the current WeakReference object. |
|  [WeakReference](./weakreference/)() | Default constructor. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Constructor from nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Initializes a new instance of the WeakReference class, referencing the specified object. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Initializes a new instance of the WeakReference class, referencing the specified object. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)