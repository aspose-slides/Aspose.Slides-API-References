---
title: GeometryPath class
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides/geometrypath/
---
## GeometryPath класс

Представляет геометрический путь объекта GeometryShape

Тип GeometryPath раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/geometrypath/__init__/#) | Создает экземпляр GeometryPath |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`path_data`](/slides/python-net/ru/aspose.slides/geometrypath/path_data/) | Возвращает геометрический путь GeometryShape как массив сегментов пути. |
| [`fill_mode`](/slides/python-net/ru/aspose.slides/geometrypath/fill_mode/) | Устанавливает режим заливки |
| [`stroke`](/slides/python-net/ru/aspose.slides/geometrypath/stroke/) | Устанавливает внешний вид контура |

## Методы

| Метод | Описание |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ru/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Добавляет линию в конец пути |
| [`line_to(self, x, y)`](/slides/python-net/ru/aspose.slides/geometrypath/line_to/#float-float) | Добавляет линию в конец пути |
| [`line_to(self, point, index)`](/slides/python-net/ru/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Добавляет линию в указанное место пути |
| [`line_to(self, x, y, index)`](/slides/python-net/ru/aspose.slides/geometrypath/line_to/#float-float-int) | Добавляет линию в указанное место пути |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ru/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Добавляет кубическую кривую Безье в конец пути |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ru/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Добавляет кубическую кривую Безье в конец пути |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ru/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Добавляет кубическую кривую Безье в указанное место пути |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ru/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Добавляет кубическую кривую Безье в указанное место пути |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ru/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Добавляет квадратичную кривую Безье в конец пути |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ru/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Adds quadratic Bezier curve at the end the path |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ru/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Добавляет квадратичную кривую Безье в указанное место пути |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ru/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Добавляет квадратичную кривую Безье в указанное место пути |
| [`move_to(self, point)`](/slides/python-net/ru/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Устанавливает позицию следующей точки. |
| [`move_to(self, x, y)`](/slides/python-net/ru/aspose.slides/geometrypath/move_to/#float-float) | Устанавливает позицию следующей точки. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides/geometrypath/remove_at/#int) | Удаляет сегмент по указанному индексу геометрического пути. |
| [`close_figure(self)`](/slides/python-net/ru/aspose.slides/geometrypath/close_figure/#) | Замыкает текущую фигуру этого пути |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ru/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Добавляет указанную дугу к пути. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)