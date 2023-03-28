---
title: UnboxToNullable()
second_title: Aspose.Slides for C++ API Reference
description: Unboxes object to nullable type.
type: docs
weight: 92
url: /cpp/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\&, **bool**) method


Unboxes object to nullable type.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Destination type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to unbox. |
| safe | **bool** | If true, return nullptr on failure, otherwise throw InvalidCastException. |

### Return Value

Unboxed nullable value (could be null).

## See Also

* Class [Nullable](../../nullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
