---
title: Camera class
second_title: Aspose.Slides для Python через .NET справку API
description: 
type: docs
url: /ru/aspose.slides/camera/
---
## Camera класс

Представляет Camera.

**Inheritance:**[`Camera`](/slides/python-net/ru/aspose.slides/camera) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

Тип Camera содержит следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/ru/aspose.slides/camera/camera_type/) | Тип Camera.<br/>            Чтение/запись [`CameraPresetType`](/slides/python-net/ru/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/ru/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180°, поле зрения).<br/>            Чтение/запись **float**. |
| [`zoom`](/slides/python-net/ru/aspose.slides/camera/zoom/) | Увеличение камеры (положительное значение в процентах).<br/>            Чтение/запись **float**. |
| [`slide`](/slides/python-net/ru/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/camera/presentation/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/ru/aspose.slides/camera/set_rotation/#float-float-float) | Вращение определяется использованием координаты широты<br/>            координаты долготы и вращения вокруг оси <br/>            как координат широты и долготы.<br/>            Если любое значение координаты равно float.NaN, все вращение не определено. |
| [`get_rotation(self)`](/slides/python-net/ru/aspose.slides/camera/get_rotation/#) | Вращение определяется использованием координаты широты<br/>            координаты долготы и вращения вокруг оси <br/>            как координат широты и долготы.<br/>            первый элемент в возвращаемом массиве — широта, второй — долгота, третий — вращение.<br/>            Возвращает None, если вращение не определено. |


### См. также
* класс [`Camera`](/slides/python-net/ru/aspose.slides/camera)
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)