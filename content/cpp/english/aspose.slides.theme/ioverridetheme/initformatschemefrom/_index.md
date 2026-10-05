---
title: InitFormatSchemeFrom()
second_title: Aspose.Slides for C++ API Reference
description: Init FormatScheme with new object for overriding FormatScheme of InheritedTheme.
type: docs
weight: 105
url: /aspose.slides.theme/ioverridetheme/initformatschemefrom/
---
## IOverrideTheme::InitFormatSchemeFrom(System::SharedPtr\<IFormatScheme\>) method


Init [FormatScheme](../../formatscheme/) with new object for overriding [FormatScheme](../../formatscheme/) of InheritedTheme.

```cpp
virtual void Aspose::Slides::Theme::IOverrideTheme::InitFormatSchemeFrom(System::SharedPtr<IFormatScheme> formatScheme)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| formatScheme | [System::SharedPtr](../../../system/sharedptr/)\<[IFormatScheme](../../iformatscheme/)\> | Data to initialize from. |

### Exceptions

| Exception | Description |
| --- | --- |
| [System::InvalidOperationException](../../../system/invalidoperationexception/) | Thrown if the [FormatScheme](../../formatscheme/) is already initialized (not null). |
| [System::ArgumentNullException](../../../system/argumentnullexception/) | Thrown if the formatScheme parameter is null. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFormatScheme](../../iformatscheme/)
* Class [IOverrideTheme](../)
* Namespace [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)