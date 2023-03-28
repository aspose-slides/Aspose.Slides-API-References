---
title: Guid
second_title: Aspose.Slides for C++ API Reference
description: "Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 833
url: /cpp/system/guid/
---
## Guid class


Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Guid
```

## Methods

| Method | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Performs arithmetic comparison of the GUIDs represented by the current and specified objects. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Determines if the GUIDs represented by the current and specified objects are equal. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
|  [Guid](./guid/)() | Constructs an object that represents a GUID consisting of all zeroes. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Constructs an object that represents a GUID specified as an array of unsigned 8-bit integer values. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Constructs an object that represents a GUID specified as an array view of unsigned 8-bit integer values. |
|  [Guid](./guid/)(const [String](../string/)\&) | Constructs an object that represents a GUID specified as a string. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Constructs an instance of [Guid](./) class from the specified GUID components. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Constructs an instance of [Guid](./) class from the specified GUID components. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Constructs an instance of [Guid](./) class from the specified unsigned integers and bytes. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Constructs an instance of [Guid](./) class from the specified unsigned integers and bytes. |
|  [Guid](./guid/)(const [Guid](./)\&) | Constructs an object that represents the same GUID as the specified object. |
| static [Guid](./) [NewGuid](./newguid/)() | Generates a new GUID and returns a [Guid](./) object that represents it. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Determines if the GUIDs represented by the current and specified objects are not equal. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Assigns to the current object the GUID value represented by the specified [Guid](./) object. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Determines if the GUIDs represented by the current and specified objects are equal. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Converts the specified string representation of a GUID into equivalent [Guid](./) object. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Converts the GUID represented by the current object into array of bytes. |
| [String](../string/) [ToString](./tostring/)() const | Converts the GUID represented by the current object to its string representation. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converts the GUID represented by the current object to its string representation using the specified string format. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converts the GUID represented by the current object to its string representation using the specified string format and Culture. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Tries to convert the specified string into [Guid](./) object. |
|  [~Guid](./~guid/)() | Destructor. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Represents a GUID that has a value of 0. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
