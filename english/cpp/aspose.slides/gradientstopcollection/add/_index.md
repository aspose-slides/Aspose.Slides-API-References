---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Creates the new gradient stop and adds it to the end of collection.
type: docs
weight: 53
url: /cpp/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) method


Creates the new gradient stop and adds it to the end of collection.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position of the new gradient stop. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Color of the new radient stop. |

### Return Value

Index of the new gradient stop in the collection.

## GradientStopCollection::Add(float, PresetColor) method


Creates the new gradient stop and adds it to the end of collection.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position of the new gradient stop. |
| presetColor | [PresetColor](../../presetcolor/) | Color of the new radient stop. |

### Return Value

Index of the new gradient stop in the collection.

## GradientStopCollection::Add(float, SchemeColor) method


Creates the new gradient stop and adds it to the end of collection.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position of the new gradient stop. |
| schemeColor | [SchemeColor](../../schemecolor/) | Color of the new radient stop. |

### Return Value

Index of the new gradient stop in the collection.

## See Also

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGradientStop](../../igradientstop/)
* Class [Color](../../../system.drawing/color/)
* Class [GradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)