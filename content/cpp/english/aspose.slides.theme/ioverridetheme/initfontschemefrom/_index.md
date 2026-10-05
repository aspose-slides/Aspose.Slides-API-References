---
title: InitFontSchemeFrom()
second_title: Aspose.Slides for C++ API Reference
description: Init FontScheme with new object for overriding FontScheme of InheritedTheme.
type: docs
weight: 66
url: /aspose.slides.theme/ioverridetheme/initfontschemefrom/
---
## IOverrideTheme::InitFontSchemeFrom(System::SharedPtr\<IFontScheme\>) method


Init [FontScheme](../../fontscheme/) with new object for overriding [FontScheme](../../fontscheme/) of InheritedTheme.

```cpp
virtual void Aspose::Slides::Theme::IOverrideTheme::InitFontSchemeFrom(System::SharedPtr<IFontScheme> fontScheme)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontScheme | [System::SharedPtr](../../../system/sharedptr/)\<[IFontScheme](../../ifontscheme/)\> | Data to initialize from. |

### Exceptions

| Exception | Description |
| --- | --- |
| [System::InvalidOperationException](../../../system/invalidoperationexception/) | Thrown if the [FontScheme](../../fontscheme/) is already initialized (not null). |
| [System::ArgumentNullException](../../../system/argumentnullexception/) | Thrown if the fontScheme parameter is null. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontScheme](../../ifontscheme/)
* Class [IOverrideTheme](../)
* Namespace [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)