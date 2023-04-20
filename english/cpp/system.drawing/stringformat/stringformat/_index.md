---
title: StringFormat()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of StringFormat class.
type: docs
weight: 1
url: /cpp/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() constructor


Constructs a new instance of [StringFormat](../) class.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) constructor


Constructs a new instance of [StringFormat](../) class with the specified format flags and language.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | A bitwise combination of StringFormatFlags enum value that specify the string format to be represented by the object being created |
| language | **int32_t** | A language of the text |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) constructor


Copy constructor.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | A [StringFormat](../) object to copy from |

## See Also

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringFormat](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)