---
title: Camera class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/camera/
---
## Camera klasa

Reprezentuje Camera.

**Dziedziczenie:**[`Camera`](/slides/python-net/pl/aspose.slides/camera) → [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)

Typ Camera udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/pl/aspose.slides/camera/camera_type/) | Typ kamery.<br/>            Odczyt/zapis [`CameraPresetType`](/slides/python-net/pl/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/pl/aspose.slides/camera/field_of_view_angle/) | FOV kamery (0-180 deg, field of View).<br/>            Odczyt/zapis **float**. |
| [`zoom`](/slides/python-net/pl/aspose.slides/camera/zoom/) | Zoom kamery (wartość dodatnia w procentach).<br/>            Odczyt/zapis **float**. |
| [`slide`](/slides/python-net/pl/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/camera/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/pl/aspose.slides/camera/set_rotation/#float-float-float) | Rotacja jest definiowana przy użyciu współrzędnej szerokości geograficznej<br/>            współrzędnej długości geograficznej oraz obrotu wokół osi <br/>            tak jak współrzędne szerokości i długości geograficznej.<br/>            Jeśli którąkolwiek wartość współrzędnej jest float.NaN, cała rotacja jest niezdefiniowana. |
| [`get_rotation(self)`](/slides/python-net/pl/aspose.slides/camera/get_rotation/#) | Rotacja jest definiowana przy użyciu współrzędnej szerokości geograficznej<br/>            współrzędnej długości geograficznej oraz obrotu wokół osi <br/>            tak jak współrzędne szerokości i długości geograficznej.<br/>            pierwszy element w zwracanej tablicy - szerokość, drugi - długość, trzeci - obrót.<br/>            Zwraca None, jeśli rotacja nie jest zdefiniowana. |


### Zobacz także
* klasa [`Camera`](/slides/python-net/pl/aspose.slides/camera)
* klasa [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)