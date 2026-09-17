---
title: GeometryShape class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/geometryshape/
---
## GeometryShape класс

Представляет родительский класс для всех геометрических фигур.

**Наследование:**[`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип GeometryShape раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/geometryshape/is_text_holder/) | Определяет, является ли фигура TextHolder_PPT.<br/>            Только чтение **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/geometryshape/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только чтение [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/geometryshape/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только чтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/geometryshape/raw_frame/) | Возвращает или задает свойства сырой рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/geometryshape/frame/) | Возвращает или задает свойства рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/geometryshape/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линии для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, которые не имеют свойств линии.<br/>            Только чтение [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/geometryshape/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффекта для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, которые не имеют 3D-свойств.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/geometryshape/effect_format/) | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, которые не имеют свойств эффектов.<br/>            Только чтение [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/geometryshape/fill_format/) | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, которые не имеют свойств заливки.<br/>            Только чтение [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/geometryshape/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/geometryshape/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую при наведении мыши.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/geometryshape/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только чтение [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/geometryshape/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/geometryshape/z_order_position/) | Возвращает позицию фигуры в порядке z.<br/>            Shapes[0] возвращает фигуру в задней части порядка z,<br/>            а Shapes[Shapes.Count - 1] возвращает фигуру в передней части порядка z.<br/>            Только чтение **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/geometryshape/connection_site_count/) | Возвращает количество точек соединения на фигуре.<br/>            Только чтение **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/geometryshape/rotation/) | Возвращает или задает угол в градусах, на который указанная фигура повернута вокруг оси z.<br/>            Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/geometryshape/x/) | Получает или задает координату x левого верхнего угла фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/geometryshape/y/) | Получает или задает координату y левого верхнего угла фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/geometryshape/width/) | Получает или задает ширину фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/geometryshape/height/) | Получает или задает высоту фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/geometryshape/black_white_mode/) | Свойство указывает, как фигура будет отображаться в режиме черно-белого отображения.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/geometryshape/unique_id/) | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переназначено пользователем или программно, его нельзя рассматривать<br/>            как постоянный уникальный ключ.<br/>            Только чтение **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/geometryshape/office_interop_shape_id/) | Возвращает уникальный идентификатор в пределах слайда, который остаётся постоянным в течение жизни фигуры и<br/>            позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа.<br/>            Только чтение **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/geometryshape/alternative_text/) | Возвращает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/geometryshape/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанного с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/geometryshape/name/) | Возвращает или задает имя фигуры.<br/>            Не должно быть None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/geometryshape/is_decorative/) | Получает или задает параметр 'Mark as decorative'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/geometryshape/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IBaseShapeLock`](/slides/python-net/ru/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/geometryshape/is_grouped/) | Определяет, сгруппирована ли фигура.<br/>            Только чтение **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/geometryshape/parent_group/) | Возвращает объект родительской GroupShape, если фигура сгруппирована. В противном случае возвращает None.<br/>            Только чтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/geometryshape/slide/) | Возвращает родительский слайд фигуры.<br/>            Только чтение [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/geometryshape/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только чтение [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ru/aspose.slides/geometryshape/shape_style/) | Возвращает объект стиля фигуры.<br/>            Только чтение [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type/) | Возвращает или задает тип предустановки геометрии.<br/>            Примечание: при изменении значения все значения регулировок будут сброшены к значениям по умолчанию.<br/>            Чтение/запись [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides/geometryshape/adjustments/) | Возвращает коллекцию значений регулировок фигуры.<br/>            Только чтение [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/geometryshape/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/geometryshape/remove_placeholder/#) | Определяет, что эта фигура не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/geometryshape/get_base_placeholder/#) | Возвращает базовую фигуру-заполнитель (фигура из макета и/или мастер-слайда, от которой наследуется текущая фигура).<br/>            Возвращает None, если текущая фигура не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/geometryshape/get_visual_bounds/#) | Получает визуальные границы фигуры, вычисленные на основе её отрисованного содержимого. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/geometryshape/get_geometry_paths/#) | Возвращает копию пути геометрической фигуры. Координаты относительные к левому верхнему углу фигуры. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Обновляет геометрию фигуры из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительными к левому<br/>            верхнему углу фигуры.<br/>            Изменяет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Обновляет геометрию фигуры из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительными к левому<br/>            верхнему углу фигуры.<br/>            Изменяет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/geometryshape/create_shape_elements/#) | Создаёт и возвращает массив элементов фигуры. |

### См. также
* класс [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)