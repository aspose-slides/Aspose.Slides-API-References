---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert the specified string into equivalent enum constant.
type: docs
weight: 79
url: /cpp/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) method


Tries to convert the specified string into equivalent enum constant.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) that is interpreted as containing the name of enum constant |
| result | E\& | The output parameter that if conversion succeeds contains the result of conversion on function |

### Return Value

True if conversion succeeded, otherwise - false

## Enum::TryParse(const String\&, bool, E\&) method


Tries to convert the specified string into equivalent enum constant.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) that is interpreted as containing the name of enum constant |
| ignoreCase | **bool** | Specifies if the case should be ignored when interpreting the string |
| result | E\& | The output parameter that if conversion succeeds contains the result of conversion on function return |

### Return Value

True if conversion succeeded, otherwise - false

## See Also

* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)