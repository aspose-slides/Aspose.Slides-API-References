---
title: GetValueOf()
second_title: Aspose.Slides for C++ API Reference
description: Returns boxed value of the enum constant with the specified name.
type: docs
weight: 53
url: /system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const method


Returns boxed value of the enum constant with the specified name.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | The name of the enum constant |
| ignoreCase | **bool** | Specifeis if the case should be ignored when interpreting the name of the enum constant |

### Return Value

A boxed value of the enum constant whose name is specified in **str**.

## EnumValues::GetValueOf(long) const method


Returns boxed value of the enum constant with the specified value.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| val | long | The value of the enum constant |

### Return Value

A boxed value of the enum constant whose vakye is specified in **str**.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)