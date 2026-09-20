---
title: ICamera class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/icamera/
---
## ICamera třída

Represents Camera.

The ICamera type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`camera_type`](/slides/python-net/cs/aspose.slides/icamera/camera_type/) | Camera type<br/>            Číst/zapisovat [`CameraPresetType`](/slides/python-net/cs/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/cs/aspose.slides/icamera/field_of_view_angle/) | Camera FOV (0-180 deg, zorné pole)<br/>            Číst/zapisovat **float**. |
| [`zoom`](/slides/python-net/cs/aspose.slides/icamera/zoom/) | Camera zoom (kladná hodnota v procentech)<br/>            Číst/zapisovat **float**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/cs/aspose.slides/icamera/set_rotation/#float-float-float) | Rotace je definována pomocí zeměpisné šířky<br/>            souřadnice, zeměpisné délky a otáčení kolem osy <br/>            jako zeměpisné šířky a délky.<br/>            Pokud je některá hodnota souřadnice float.NaN, je celá rotace nedefinovaná. |
| [`get_rotation(self)`](/slides/python-net/cs/aspose.slides/icamera/get_rotation/#) | Rotace je definována pomocí zeměpisné šířky<br/>            souřadnice, zeměpisné délky a otáčení kolem osy <br/>            jako zeměpisné šířky a délky.<br/>            první prvek v návratovém poli - šířka, druhý - délka, třetí - otáčení.<br/>            Vrací None, pokud není žádná rotace definována. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)