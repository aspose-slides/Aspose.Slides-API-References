---
title: BitVector32
second_title: Aspose.Slides for C++ API Reference
description: Provides a simple light bit vector with easy integer or Boolean access to a 32 bit storage.
type: docs
weight: 1
url: /cpp/system.collections.specialized/bitvector32/
---
## BitVector32 class


Provides a simple light bit vector with easy integer or [Boolean](../../system/boolean/) access to a 32 bit storage.

```cpp
class BitVector32
```

## Methods

| Method | Description |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Initializes a new empty instance of the [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Initializes a new instance of the [BitVector32](./) structure with the specified internal data. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Initializes a new instance of the [BitVector32](./) structure with the information in the specified value. |
| static **int32_t** [CreateMask](./createmask/)() | Creates the first mask in a series. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Creates the next mask in a series. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Creates the first section in a series, with the specified maximum value. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Creates the next section in a series, with the specified maximum value. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Determines whether the specified object is the same as the current. |
| **int32_t** [get_Data](./get_data/)() | returns the raw data stored in this bit vector... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Gets a value indicating whether all the specified bits are set. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Gets the value for the specified section. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Sets a value indicating whether all the specified bits are set. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Sets the value for the specified section. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Converts value represented by value parameter to string. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converts value represented by current object to string. |
## See Also

* Namespace [System::Collections::Specialized](../)
* Library [Aspose.Slides](../../)
