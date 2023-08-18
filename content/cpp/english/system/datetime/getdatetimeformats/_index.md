---
title: GetDateTimeFormats()
second_title: Aspose.Slides for C++ API Reference
description: Returns array of strings where each element is the string representation of the current object formatted with one of the standard date and time format specifiers.
type: docs
weight: 547
url: /system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const method


Returns array of strings where each element is the string representation of the current object formatted with one of the standard date and time format specifiers.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const method


Returns array of strings where each element is the string representation of the current object formatted with the specified standard date and time format specifier.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | char_t | Standard date and time format specifier. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const method


Returns array of strings where each element is the string representation of the current object formatted with one of the standard date and time format specifiers and the specified format provider.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const method


Returns array of strings where each element is the string representation of the current object formatted with the specified standard date and time format specifier and format provider.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| format | char_t | Standard date and time format specifier. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider. |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)