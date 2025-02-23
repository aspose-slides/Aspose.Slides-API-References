---
title: ToUpper()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified character to upper case.
type: docs
weight: 222
url: /system/char/toupper/
---
## Char::ToUpper(char_t) method


Converts the specified character to upper case.

```cpp
static char_t System::Char::ToUpper(char_t c)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character to convert |

### Return Value

The specified character in upper case if the specified character is a lower case letter, otherwise - the specified character

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) method


Converts the specified character to upper case.

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Character to convert |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | An object that supplies culture-specific casing rules. |

### Return Value

The specified character in upper case if the specified character is a lower case letter, otherwise - the specified character

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Char](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)