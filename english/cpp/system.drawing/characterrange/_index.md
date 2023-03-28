---
title: CharacterRange
second_title: Aspose.Slides for C++ API Reference
description: "Represents a range of character positions in a string. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 40
url: /cpp/system.drawing/characterrange/
---
## CharacterRange class


Represents a range of character positions in a string. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class CharacterRange
```

## Methods

| Method | Description |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Constructs a new instance of [CharacterRange](./) class that represents the specified range. |
|  [CharacterRange](./characterrange/)() | Constructs a new instance of [CharacterRange](./) class that represents an empty range. |
| **int32_t** [get_First](./get_first/)() const | Returns the position of the first character of the range represented by the current object. |
| **int32_t** [get_Length](./get_length/)() const | Returns the number of characters in the range represented by the current object. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Determines if the current and specified objects represent distinct ranges. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Determines if the current and specified objects represent the same range. |
| void [set_First](./set_first/)(**int32_t**) | Sets the position of the first character of the range represented by the current object. |
| void [set_Length](./set_length/)(**int32_t**) | Returns the number of characters in the range represented by the current object. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)
