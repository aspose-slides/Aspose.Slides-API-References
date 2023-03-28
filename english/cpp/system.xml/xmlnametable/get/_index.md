---
title: Get()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, gets the atomized string containing the same characters as the specified range of characters in the given array.
type: docs
weight: 1
url: /cpp/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) method


When overridden in a derived class, gets the atomized string containing the same characters as the specified range of characters in the given array.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | The character array containing the name to look up. |
| offset | **int32_t** | The zero-based index into the array specifying the first character of the name. |
| length | **int32_t** | The number of characters in the name. |

### Return Value

The atomized string or **nullptr** if the string has not already been atomized. If **length** is zero, [String::Empty](../../../system/string/empty/) is returned.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlNameTable::Get(const [String](../../../system/string/)\&) method


When overridden in a derived class, gets the atomized string containing the same value as the specified string.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | The name to look up. |

### Return Value

The atomized string or **nullptr** if the string has not already been atomized.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
