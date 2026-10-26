---
title: Camera class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/camera/
---
## Camera klass

Representerar Camera.

**Inheritance:**[`Camera`](/slides/python-net/sv/aspose.slides/camera) → [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)

Camera-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`camera_type`](/slides/python-net/sv/aspose.slides/camera/camera_type/) | Camera type.<br/>            Läs/skriv [`CameraPresetType`](/slides/python-net/sv/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/sv/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180 grader, field of View).<br/>            Läs/skriv **float**. |
| [`zoom`](/slides/python-net/sv/aspose.slides/camera/zoom/) | Camera zoom (positivt värde i procent).<br/>            Läs/skriv **float**. |
| [`slide`](/slides/python-net/sv/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/camera/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/sv/aspose.slides/camera/set_rotation/#float-float-float) | En rotation definieras genom att använda en latitud<br/>            koordinat, en longitudkoordinat och en revolution kring axeln <br/>            som latitud- och longitudkoordinaterna.<br/>            Om något av koordinatvärdena är float.NaN, är hela rotationen odefinierad. |
| [`get_rotation(self)`](/slides/python-net/sv/aspose.slides/camera/get_rotation/#) | En rotation definieras genom att använda en latitud<br/>            koordinat, en longitudkoordinat och en revolution kring axeln <br/>            som latitud- och longitudkoordinaterna.<br/>            första elementet i returarrayen - latitud, andra - longitud, tredje - revolution.<br/>            Returnerar None om ingen rotation är definierad. |


### Se även
* klass [`Camera`](/slides/python-net/sv/aspose.slides/camera)
* klass [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)