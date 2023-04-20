---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Converts the GUID represented by the current object to its string representation.
type: docs
weight: 79
url: /cpp/system/guid/tostring/
---
## Guid::ToString() const method


Converts the GUID represented by the current object to its string representation.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const method


Converts the GUID represented by the current object to its string representation using the specified string format.

```cpp
String System::Guid::ToString(const String &format) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | The format to use |

### Return Value

The string representation of the GUID value represented by the current object

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const method


Converts the GUID represented by the current object to its string representation using the specified string format and Culture.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | The format to use |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture to use |

### Return Value

The string representation of the GUID value represented by the current object

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Guid](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)