---
title: IRotation3D class
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.charts/irotation3d/
---
## IRotation3D класс

Представляет 3D-поворот диаграммы.

Тип IRotation3D предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`rotation_x`](/slides/python-net/ru/aspose.slides.charts/irotation3d/rotation_x/) | Возвращает или задает угол поворота вокруг оси X, т.е. в направлении Y для 3D-диаграмм (от -90 до 90 градусов).<br/>            Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и параметру "Y Rotation" в PowerPoint 2007+.<br/>            Чтение/запись **int**. |
| [`rotation_y`](/slides/python-net/ru/aspose.slides.charts/irotation3d/rotation_y/) | Возвращает или задает угол поворота вокруг оси Y, т.е. в направлении X для 3D-диаграмм (от 0 до 360 градусов).<br/>            Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и параметру "X Rotation" в PowerPoint 2007+.<br/>            Чтение/запись **int**. |
| [`perspective`](/slides/python-net/ru/aspose.slides.charts/irotation3d/perspective/) | Возвращает или задает значение перспективы (угол поля зрения) для 3D-диаграмм (от 0 до 100).<br/>            Игнорируется, если значение свойства RightAngleAxes равно true.<br/>            Чтение/запись **int**. |
| [`right_angle_axes`](/slides/python-net/ru/aspose.slides.charts/irotation3d/right_angle_axes/) | Определяет, находятся ли оси диаграммы под прямыми углами, а не нарисованы в перспективе.<br/>            Другими словами, определяет, независимы ли углы осей диаграммы от её <br/>            поворота или наклона.<br/>            Чтение/запись **bool**. |
| [`depth_percents`](/slides/python-net/ru/aspose.slides.charts/irotation3d/depth_percents/) | Возвращает или задает глубину 3D-диаграммы в процентах от ширины диаграммы (от 20 до 2000 процентов).<br/>            Чтение/запись **int**. |
| [`height_percents`](/slides/python-net/ru/aspose.slides.charts/irotation3d/height_percents/) | Указывает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 процентов).<br/>            Чтение/запись **int**. |


### Смотрите также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)