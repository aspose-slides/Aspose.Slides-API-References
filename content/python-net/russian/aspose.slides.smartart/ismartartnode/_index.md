---
title: ISmartArtNode class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode класс

Представляет узел диаграммы SmartArt.

Тип ISmartArtNode открывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`child_nodes`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/child_nodes/) | Возвращает коллекцию всех дочерних узлов текущего узла.<br/>            Только для чтения [`ISmartArtNodeCollection`](/slides/python-net/ru/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/shapes/) | Возвращает коллекцию всех фигур, связанных с узлом.<br/>            Только для чтения [`ISmartArtShapeCollection`](/slides/python-net/ru/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/text_frame/) | Возвращает или задает текст узла.<br/>            Только для чтения [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/is_assistant/) | Возвращает или задает узел как помощника.<br/>            Чтение/запись **bool**. |
| [`level`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/level/) | Возвращает уровень вложенности узла.<br/>            Только для чтения **int**. |
| [`bullet_fill_format`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | Возвращает объект FillFormat, содержащий свойства форматирования заливки для маркера узла.<br/>            Примечание: может вернуть None для некоторых типов макета SmartArt, которые не предоставляют маркеры для узлов.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/position/) | Возвращает или задает нулевую позицию узла среди одноуровневых узлов.<br/>            Чтение/запись **int**. |
| [`is_hidden`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/is_hidden/) | Возвращает true, если этот узел является скрытым узлом в модели данных.<br/>            Только для чтения **bool**. |
| [`organization_chart_layout`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | Возвращает или задает тип макета организационной схемы, связанный с текущим узлом.<br/>            Чтение/запись [`OrganizationChartLayoutType`](/slides/python-net/ru/aspose.slides.smartart/organizationchartlayouttype). |

## Методы

| Метод | Описание |
| :- | :- |
| [`remove(self)`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode/remove/#) | Удалить текущий узел. |

### См. также
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)