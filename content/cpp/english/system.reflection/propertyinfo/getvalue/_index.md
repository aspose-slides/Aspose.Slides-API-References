---
title: GetValue()
second_title: Aspose.Slides for C++ API Reference
description: Gets property value from specific object.
type: docs
weight: 1
url: /system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) method


Gets property value from specific object.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) to read property from. |

### Return Value

Value of specified property for specified object.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method


Gets property value from specific object.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) to read property from. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | These are optional index values for indexed properties. For non-indexed properties, this value should be null. |

### Return Value

Value of specified property for specified object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)