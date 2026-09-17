---
title: ICamera class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/icamera/
---
## ICamera класс

Represents Camera.

The ICamera type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/ru/aspose.slides/icamera/camera_type/) | Тип камеры<br/>            Чтение/запись [`CameraPresetType`](/slides/python-net/ru/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/ru/aspose.slides/icamera/field_of_view_angle/) | Поле зрения камеры (0-180°)<br/>            Чтение/запись **float**. |
| [`zoom`](/slides/python-net/ru/aspose.slides/icamera/zoom/) | Масштаб камеры (положительное значение в процентах)<br/>            Чтение/запись **float**. |

## Методы

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/ru/aspose.slides/icamera/set_rotation/#float-float-float) | Вращение задаётся использованием координаты широты<br/>            и координаты долготы, а также оборота вокруг оси <br/>            по координатам широты и долготы.<br/>            Если любое значение координаты является float.NaN, всё вращение неопределено. |
| [`get_rotation(self)`](/slides/python-net/ru/aspose.slides/icamera/get_rotation/#) | Вращение задаётся использованием координаты широты<br/>            и координаты долготы, а также оборота вокруг оси <br/>            по координатам широты и долготы.<br/>            первый элемент в возвращаемом массиве — широта, второй — долгота, третий — оборот.<br/>            Возвращает None, если вращение не определено. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)