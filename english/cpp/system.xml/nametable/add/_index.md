---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Atomizes the specified string and adds it to the NameTable.
type: docs
weight: 14
url: /cpp/system.xml/nametable/add/
---
## NameTable::Add(const [String](../../../system/string/)\&) method


Atomizes the specified string and adds it to the [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | The string to add. |

### Return Value

The atomized string or the existing string if it already exists in the [NameTable](../).

## See Also

* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## NameTable::Add(const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) method


Atomizes the specified string and adds it to the [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | The character array containing the string to add. |
| start | **int32_t** | The zero-based index into the array specifying the first character of the string. |
| len | **int32_t** | The number of characters in the string. |

### Return Value

The atomized string or the existing string if one already exists in the [NameTable](../). If **len** is zero, [String::Empty](../../../system/string/empty/) is returned.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
