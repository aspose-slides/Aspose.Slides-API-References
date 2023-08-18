---
title: ToType()
second_title: Aspose.Slides for C++ API Reference
description: "Converts the value of this instance to a System::Object of the specified System::Type that has an equivalent value, using the specified culture-specific formatting information."
type: docs
weight: 209
url: /system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) method


Converts the value of this instance to a [System::Object](../../object/) of the specified System::Type that has an equivalent value, using the specified culture-specific formatting information.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | The System::Type to which the value of this instance is converted. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | A [System::IFormatProvider](../../iformatprovider/) interface implementation that supplies culture-specific formatting information. |

### Return Value

A [System::Object](../../object/) instance of type conversionType whose value is equivalent to the value of this instance.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)