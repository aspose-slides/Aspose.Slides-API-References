---
title: ICamera class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/icamera/
---
## ICamera class

Kamerát képviseli.

Az ICamera típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`camera_type`](/slides/python-net/hu/aspose.slides/icamera/camera_type/) | Kamera típusa<br/>            Olvasás/írás [`CameraPresetType`](/slides/python-net/hu/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/hu/aspose.slides/icamera/field_of_view_angle/) | Kamera FOV (0-180 fok, látótér)<br/>            Olvasás/írás **float**. |
| [`zoom`](/slides/python-net/hu/aspose.slides/icamera/zoom/) | Kamera zoom (pozitív érték százalékban)<br/>            Olvasás/írás **float**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/hu/aspose.slides/icamera/set_rotation/#float-float-float) | Egy forgatás a szélességi<br/>            koordináta, a hosszúsági koordináta és egy tengely körüli forogás használatával van definiálva<br/>            a szélességi és hosszúsági koordinátákként.<br/>            Ha bármely koordináták értéke float.NaN, a forgatás nem definiált. |
| [`get_rotation(self)`](/slides/python-net/hu/aspose.slides/icamera/get_rotation/#) | Egy forgatás a szélességi<br/>            koordináta, a hosszúsági koordináta és a tengely körüli forogás használatával van definiálva<br/>            a szélességi és hosszúsági koordinátákként.<br/>            A visszatérő tömb első eleme – szélesség, második – hosszúság, harmadik – forogás.<br/>            None-t ad vissza, ha nincs definiált forgatás. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)