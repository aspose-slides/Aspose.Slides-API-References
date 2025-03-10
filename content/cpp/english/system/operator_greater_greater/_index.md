---
title: operator>>()
second_title: Aspose.Slides for C++ API Reference
description: Gets a string from the input streamusing UTF-8 encoding.
type: docs
weight: 2692
url: /system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) function


Gets a string from the input streamusing UTF-8 encoding.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in | std::istream\& | An input stream object (instantiation of **basic_ostream** with **char**). |
| str | [String](../string/)\& | A string to read from the input stream. |

### Return Value

An input stream from which the string was extracted.

## System::operator>>(std::wistream\&, String\&) function


Gets a string from the input stream.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| in | std::wistream\& | An input stream object (instantiation of **basic_ostream** with ****wchar_t****). |
| str | [String](../string/)\& | A string to read from the input stream. |

### Return Value

An input stream from which the string was extracted.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)