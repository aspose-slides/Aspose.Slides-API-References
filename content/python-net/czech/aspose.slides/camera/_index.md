---
title: Camera class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/camera/
---
## třída Camera

Representuje Camera.

**Dědičnost:**[`Camera`](/slides/python-net/cs/aspose.slides/camera) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ Camera vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`camera_type`](/slides/python-net/cs/aspose.slides/camera/camera_type/) | Typ Camera.<br/>            Číst/zapisovat [`CameraPresetType`](/slides/python-net/cs/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/cs/aspose.slides/camera/field_of_view_angle/) | FOV kamery (0-180 deg, zorné pole).<br/>            Číst/zapisovat **float**. |
| [`zoom`](/slides/python-net/cs/aspose.slides/camera/zoom/) | Zoom kamery (kladná hodnota v procentech).<br/>            Číst/zapisovat **float**. |
| [`slide`](/slides/python-net/cs/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/camera/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/cs/aspose.slides/camera/set_rotation/#float-float-float) | Rotace je definována pomocí souřadnice latitude<br/>            coordinate, souřadnice longitude coordinate a otáčení kolem osy <br/>            jako latitude a longitude coordinates.<br/>            Pokud je některá hodnota souřadnice float.NaN, je celá rotace nedefinována. |
| [`get_rotation(self)`](/slides/python-net/cs/aspose.slides/camera/get_rotation/#) | Rotace je definována pomocí souřadnice latitude<br/>            coordinate, souřadnice longitude coordinate a otáčení kolem osy <br/>            jako latitude a longitude coordinates.<br/>            první prvek v návratovém poli - latitude, druhý - longitude, třetí - revolution.<br/>            Vrací None, pokud není rotace definována. |


### Viz také
* třída [`Camera`](/slides/python-net/cs/aspose.slides/camera)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)