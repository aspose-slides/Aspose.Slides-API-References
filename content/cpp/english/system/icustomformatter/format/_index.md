---
title: Format()
second_title: Aspose.Slides for C++ API Reference
description: Returns a string representation of a value represented by the current object using the specified format.
type: docs
weight: 1
url: /system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method


Returns a string representation of a value represented by the current object using the specified format.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | [System::String](../../string/) | The string format |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | The object to be formatted |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | The object providing the formatting information |

### Return Value

The string representation of **arg** formatted according to the format specified by **format** and **formatProvider**

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)