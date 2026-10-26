---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Skapar den nya gradientstoppet och lägger till den i slutet av samlingen.
type: docs
weight: 53
url: /sv/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) metod


Skapar den nya gradientstoppet och lägger till den i slutet av samlingen.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position för den nya gradientstoppet. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Färgen på den nya gradientstoppet. |

### Return Value

Index för den nya gradientstoppet i samlingen.

## GradientStopCollection::Add(float, PresetColor) metod


Skapar den nya gradientstoppet och lägger till den i slutet av samlingen.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position för den nya gradientstoppet. |
| presetColor | [PresetColor](../../presetcolor/) | Färgen på den nya gradientstoppet. |

### Return Value

Index för den nya gradientstoppet i samlingen.

## GradientStopCollection::Add(float, SchemeColor) metod


Skapar den nya gradientstoppet och lägger till den i slutet av samlingen.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position för den nya gradientstoppet. |
| schemeColor | [SchemeColor](../../schemecolor/) | Färgen på den nya gradientstoppet. |

### Return Value

Index för den nya gradientstoppet i samlingen.

## Se också

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGradientStop](../../igradientstop/)
* Class [Color](../../../system.drawing/color/)
* Class [GradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)