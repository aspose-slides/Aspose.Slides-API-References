---
title: Camera
second_title: Aspose.Sildes for .NET API Reference
description: Represents Camera.
type: docs
weight: 1070
url: /aspose.slides/camera/
---

## Camera class

Represents Camera.

```csharp
public sealed class Camera : PVIObject, ICamera
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [CameraType](../../aspose.slides/camera/cameratype) { get; set; } | Camera type. Read/write [`CameraPresetType`](../camerapresettype). |
| [FieldOfViewAngle](../../aspose.slides/camera/fieldofviewangle) { get; set; } | Camera FOV (0-180 deg, field of View). Read/write Single. |
| [Zoom](../../aspose.slides/camera/zoom) { get; set; } | Camera zoom (positive value in percentage). Read/write Single. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compares with specified object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |
| [GetRotation](../../aspose.slides/camera/getrotation)() | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined. |
| [SetRotation](../../aspose.slides/camera/setrotation)(float, float, float) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. If any of coordinate value is float.NaN, all rotation is undefined. |

### See Also

* class [PVIObject](../pviobject)
* interface [ICamera](../icamera)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
