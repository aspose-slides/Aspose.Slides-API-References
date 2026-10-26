---
title: ShapeElement class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/shapeelement/
---
## ShapeElement класс

Представляет часть формы с одинаковыми свойствами контура и заливки.

Тип ShapeElement раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/ru/aspose.slides/shapeelement/parent_shape/) | Возвращает объект Shape_PPT, для которого был создан элемент.<br/>            Только для чтения [`Shape`](/slides/python-net/ru/aspose.slides/shape). |
| [`path_points`](/slides/python-net/ru/aspose.slides/shapeelement/path_points/) | Возвращает массив точек, определяющих геометрию пути элемента. |
| [`path_types`](/slides/python-net/ru/aspose.slides/shapeelement/path_types/) | Возвращает массив байтовых значений, указывающих тип каждой точки в пути элемента.<br/>            <br/>**0**  Указывает, что точка является началом фигуры.<br/><br/><br/>**1**  Указывает, что точка является одной из двух конечных точек линии.<br/><br/><br/>**3**  Указывает, что точка является конечной точкой или контрольной точкой кубического сплайна Безье.<br/><br/><br/>**7**  Маскирует все биты, кроме трех младших, которые указывают тип точки.<br/><br/><br/>**16**  Указывает, что соответствующий сегмент пунктирный.<br/><br/><br/>**32**  Указывает, что точка является маркером.<br/><br/><br/>**128**  Указывает, что точка является последней точкой в закрытом подпути (фигуре).<br/><br/><br/>**129**  Указывает на точку данных, которая одновременно является конечной точкой отрезка линии и последней точкой закрытого подпутя. |
| [`fill_source`](/slides/python-net/ru/aspose.slides/shapeelement/fill_source/) | Возвращает информацию о том, как заполнять элемент.<br/>            Только для чтения [`ShapeElementFillSource`](/slides/python-net/ru/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/ru/aspose.slides/shapeelement/stroke_source/) | Возвращает информацию о том, как обводить элемент.<br/>            Только для чтения [`ShapeElementStrokeSource`](/slides/python-net/ru/aspose.slides/shapeelementstrokesource). |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)