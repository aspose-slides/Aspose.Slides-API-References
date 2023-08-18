---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: "Converts the value of this instance to an equivalent System::String using the specified culture-specific formatting information."
type: docs
weight: 196
url: /system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) method


Converts the value of this instance to an equivalent [System::String](../../string/) using the specified culture-specific formatting information.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | A [System::IFormatProvider](../../iformatprovider/) interface implementation that supplies culture-specific formatting information. |

### Return Value

A [System::String](../../string/) instance equivalent to the value of this instance.

## IConvertible::ToString() const method


Analog of C# [Object.ToString()](../../object/tostring/) method. Enables converting custom objects to string.

```cpp
virtual String System::Object::ToString() const
```


### Return Value

[String](../../string/) representation as provided by final class.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)