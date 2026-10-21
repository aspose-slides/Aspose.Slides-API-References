---
title: InitColorSchemeFrom()
second_title: Aspose.Slides for C++ API Reference
description: Init ColorScheme with new object for overriding ColorScheme of InheritedTheme.
type: docs
weight: 27
url: /aspose.slides.theme/ioverridetheme/initcolorschemefrom/
---
## IOverrideTheme::InitColorSchemeFrom(System::SharedPtr\<IColorScheme\>) method


Init [ColorScheme](../../colorscheme/) with new object for overriding [ColorScheme](../../colorscheme/) of InheritedTheme.

```cpp
virtual void Aspose::Slides::Theme::IOverrideTheme::InitColorSchemeFrom(System::SharedPtr<IColorScheme> colorScheme)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| colorScheme | [System::SharedPtr](../../../system/sharedptr/)\<[IColorScheme](../../icolorscheme/)\> | Data to initialize from. |

### Exceptions

| Exception | Description |
| --- | --- |
| [System::InvalidOperationException](../../../system/invalidoperationexception/) | Thrown if the [ColorScheme](../../colorscheme/) is already initialized (not null). |
| [System::ArgumentNullException](../../../system/argumentnullexception/) | Thrown if the colorScheme parameter is null. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorScheme](../../icolorscheme/)
* Class [IOverrideTheme](../)
* Namespace [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)