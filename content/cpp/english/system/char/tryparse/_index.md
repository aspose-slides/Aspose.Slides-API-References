---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a string consisting of a single character into UTF-16 character. The function succeeds only when input string is not null and has length of exactly one character.
type: docs
weight: 300
url: /system/char/tryparse/
---
## Char::TryParse(const System::String\&, char_t\&) method


Tries to convert a string consisting of a single character into UTF-16 character. The function succeeds only when input string is not null and has length of exactly one character.

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [System::String](../../string/)\& | [String](../../string/) to convert |
| result | char_t\& | The output variable that will contain the result of conversion if conversion succeeds |

### Return Value

True if conversion succeeded, otherwise - false

## See Also

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)