---
title: ICamera class
second_title: Aspose.Slides för Python via .NET API Reference
description: 
type: docs
url: /sv/aspose.slides/icamera/
---
## ICamera klass

Representerar kamera.

ICamera-typen visar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`camera_type`](/slides/python-net/sv/aspose.slides/icamera/camera_type/) | Kameratyp<br/>            Läsa/skriva [`CameraPresetType`](/slides/python-net/sv/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/sv/aspose.slides/icamera/field_of_view_angle/) | Kamera-FOV (0-180 grad, synfält)<br/>            Läsa/skriva **float**. |
| [`zoom`](/slides/python-net/sv/aspose.slides/icamera/zoom/) | Kamerazoom (positivt värde i procent)<br/>            Läsa/skriva **float**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/sv/aspose.slides/icamera/set_rotation/#float-float-float) | En rotation definieras genom att använda en latitud<br/>            koordinat, en longitudkoordinat och en revolution kring axeln <br/>            som latitud- och longitudkoordinaterna.<br/>            Om något koordinatvärde är float.NaN är hela rotationen odefinierad. |
| [`get_rotation(self)`](/slides/python-net/sv/aspose.slides/icamera/get_rotation/#) | En rotation definieras genom att använda en latitud<br/>            koordinat, en longitudkoordinat och en revolution kring axeln <br/>            som latitud- och longitudkoordinaterna.<br/>            första elementet i returarrayen - latitud, andra - longitud, tredje - revolution.<br/>            Returnerar None om ingen rotation definierad. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)