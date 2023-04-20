---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Creates the new gradient stop and adds it to the end of collection.
type: docs
weight: 14
url: /cpp/aspose.slides/igradientstopcollection/add/
---
## IGradientStopCollection::Add(float, System::Drawing::Color) method


Creates the new gradient stop and adds it to the end of collection.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, System::Drawing::Color color)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position of the new gradient stop. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Color of the new radient stop. |

### Return Value

Index of the new gradient stop in the collection.

## IGradientStopCollection::Add(float, PresetColor) method


Creates the new gradient stop and adds it to the end of collection.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, PresetColor presetColor)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **float** | Position of the new gradient stop. |
| presetColor | [PresetColor](../../presetcolor/) | Color of the new radient stop. |

### Return Value

Index of the new gradient stop in the collection.

## IGradientStopCollection::Add(float, SchemeColor) method


Creates the new gradient stop and adds it to the end of collection.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, SchemeColor schemeColor)=0
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
* Class [IGradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)