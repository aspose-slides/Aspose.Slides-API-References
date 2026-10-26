---
title: IGeometryPath class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/igeometrypath/
---
## IGeometryPath класс

Представляет геометрический путь GeometryShape

Тип IGeometryPath раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`path_data`](/slides/python-net/ru/aspose.slides/igeometrypath/path_data/) | Возвращает геометрический путь GeometryShape в виде массива сегментов пути. |
| [`fill_mode`](/slides/python-net/ru/aspose.slides/igeometrypath/fill_mode/) | Устанавливает режим заливки |
| [`stroke`](/slides/python-net/ru/aspose.slides/igeometrypath/stroke/) | Устанавливает внешний вид обводки |

## Методы

| Метод | Описание |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ru/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Добавляет линию в конец пути |
| [`line_to(self, x, y)`](/slides/python-net/ru/aspose.slides/igeometrypath/line_to/#float-float) | Добавляет линию в конец пути |
| [`line_to(self, point, index)`](/slides/python-net/ru/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Добавляет линию в указанное место пути |
| [`line_to(self, x, y, index)`](/slides/python-net/ru/aspose.slides/igeometrypath/line_to/#float-float-int) | Добавляет линию в указанное место пути |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ru/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Добавляет кубическую кривую Безье в конец пути |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ru/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Добавляет кубическую кривую Безье в конец пути |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ru/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Добавляет кубическую кривую Безье в указанное место пути |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ru/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Добавляет кубическую кривую Безье в указанное место пути |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ru/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Добавляет квадратичную кривую Безье в конец пути |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ru/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Добавляет квадратичную кривую Безье в конец пути |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ru/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Добавляет квадратичную кривую Безье в указанное место пути |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ru/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Добавляет квадратичную кривую Безье в указанное место пути |
| [`move_to(self, point)`](/slides/python-net/ru/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Устанавливает позицию следующей точки. |
| [`move_to(self, x, y)`](/slides/python-net/ru/aspose.slides/igeometrypath/move_to/#float-float) | Устанавливает позицию следующей точки. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/igeometrypath/remove_at/#int) | Удаляет сегмент в указанном индексе геометрического пути. |
| [`close_figure(self)`](/slides/python-net/ru/aspose.slides/igeometrypath/close_figure/#) | Закрывает текущую фигуру этого пути |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ru/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Добавляет указанную дугу к пути. |

### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)