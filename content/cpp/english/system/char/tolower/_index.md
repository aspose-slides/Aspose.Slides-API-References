---
title: ToLower()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified character to lower case.
type: docs
weight: 235
url: /system/char/tolower/
---
## Char::ToLower(char_t) method


Converts the specified character to lower case.

```cpp
static char_t System::Char::ToLower(char_t c)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character to convert |

### Return Value

The specified character in lower case if the specified character is an upper case letter, otherwise - the specified character

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) method


Converts the specified character to lower case.

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character to convert |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | An object that supplies culture-specific casing rules. |

### Return Value

The specified character in lower case if the specified character is an upper case letter, otherwise - the specified character

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Char](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)