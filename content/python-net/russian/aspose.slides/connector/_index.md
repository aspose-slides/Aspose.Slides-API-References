---
title: Connector class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/connector/
---
## Connector класс

Represents a connector.

**Inheritance:**[`Connector`](/slides/python-net/ru/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

The Connector type exposes the following members:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/connector/is_text_holder/) | Определяет, является ли фигура TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/connector/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/connector/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/connector/raw_frame/) | Возвращает или задает свойства необработанной рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/connector/frame/) | Возвращает или задает свойства рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/connector/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линий.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/connector/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3D-свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/connector/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/connector/fill_format/) | Возвращает объект FillFormat, содержащий свойства заполнения для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств заполнения.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/connector/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/connector/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую для наведения мыши.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/connector/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/connector/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/connector/z_order_position/) | Возвращает позицию фигуры в порядке z-слоёв.<br/>            Shapes[0] возвращает фигуру, находящуюся в самом заднем слое,<br/>            а Shapes[Shapes.Count - 1] — в самом переднем слое.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/connector/connection_site_count/) | Возвращает количество точек подключения на фигуре.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/connector/rotation/) | Возвращает или задает количество градусов, на которое указанная фигура вращается вокруг оси z.<br/>            Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/connector/x/) | Получает или задает координату x верхнего левого угла фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/connector/y/) | Получает или задает координату y верхнего левого угла фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/connector/width/) | Получает или задает ширину фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/connector/height/) | Получает или задает высоту фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/connector/black_white_mode/) | Свойство определяет, как фигура будет отображаться в режиме черно-белого отображения..<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/connector/unique_id/) | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать<br/>            как постоянный уникальный ключ.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/connector/office_interop_shape_id/) | Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся неизменным на протяжении жизни фигуры и<br/>            позволяет PowerPoint или коду межопроведения надёжно ссылаться на фигуру из любой части документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/connector/alternative_text/) | Возвращает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/connector/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/connector/name/) | Возвращает или задает имя фигуры.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/connector/is_decorative/) | Получает или задает параметр 'Отметить как декоративный'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/connector/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только для чтения [`IConnectorLock`](/slides/python-net/ru/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/connector/is_grouped/) | Определяет, сгруппирована ли фигура.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/connector/parent_group/) | Возвращает объект родительской группы GroupShape, если фигура сгруппирована. В противном случае возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/connector/slide/) | Возвращает родительский слайд фигуры.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/connector/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ru/aspose.slides/connector/shape_style/) | Возвращает объект стиля фигуры.<br/>            Только для чтения [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides/connector/shape_type/) | Возвращает или задает тип AutoShape.<br/>            Чтение/запись [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides/connector/adjustments/) | Возвращает коллекцию значений регулировки фигуры.<br/>            Только для чтения [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/ru/aspose.slides/connector/connector_lock/) | Возвращает блокировки соединителя.<br/>            Только для чтения [`IConnectorLock`](/slides/python-net/ru/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ru/aspose.slides/connector/start_shape_connected_to/) | Возвращает или задает фигуру, к которой прикрепляется начало соединителя.<br/>            Чтение/запись [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ru/aspose.slides/connector/end_shape_connected_to/) | Возвращает или задает фигуру, к которой прикрепляется конец соединителя.<br/>            Чтение/запись [`IShape`](/slides/python-net/ru/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ru/aspose.slides/connector/start_shape_connection_site_index/) | Возвращает или задает индекс точки подключения для начальной фигуры.<br/>            Чтение/запись **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ru/aspose.slides/connector/end_shape_connection_site_index/) | Возвращает или задает индекс точки подключения для конечной фигуры.<br/>            Чтение/запись **int**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/connector/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/connector/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/connector/remove_placeholder/#) | Определяет, что эта фигура не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/connector/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/connector/get_base_placeholder/#) | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура).<br/>            Возвращает None, если текущая фигура не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/connector/get_visual_bounds/#) | Получает визуальные границы фигуры, вычисленные на основе её отрисованного содержимого. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/connector/get_geometry_paths/#) | Возвращает копию пути геометрической фигуры. Координаты относительны левому верхнему углу фигуры. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/connector/set_geometry_path/#igeometrypath) | Обновляет геометрию фигуры из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительны левому<br/>             верхнему углу фигуры.<br/>             Изменяет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Обновляет геометрию фигуры из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительны левому<br/>             верхнему углу фигуры.<br/>             Изменяет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/connector/create_shape_elements/#) | Создаёт и возвращает массив элементов фигуры. |
| [`reroute(self)`](/slides/python-net/ru/aspose.slides/connector/reroute/#) | Перенаправляет соединитель так, чтобы он выбирал самый короткий возможный путь между соединяемыми фигурами. |

### Смотрите также
* класс [`Connector`](/slides/python-net/ru/aspose.slides/connector)
* класс [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)