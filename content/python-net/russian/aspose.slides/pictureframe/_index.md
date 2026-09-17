---
title: PictureFrame class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/pictureframe/
---
## PictureFrame класс

Представляет рамку с изображением внутри.

**Inheritance:**[`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип PictureFrame предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/pictureframe/is_text_holder/) | Определяет, является ли фигура TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/pictureframe/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/pictureframe/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/pictureframe/raw_frame/) | Возвращает или задает свойства необработанной рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/pictureframe/frame/) | Возвращает или задает свойства рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/pictureframe/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линий.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/pictureframe/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3-d эффекта для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3-d свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/pictureframe/effect_format/) | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/pictureframe/fill_format/) | Возвращает объект FillFormat, содержащий свойства заливки для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств заливки.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/pictureframe/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/pictureframe/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/pictureframe/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/pictureframe/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/pictureframe/z_order_position/) | Возвращает позицию фигуры в порядке z-слоя.<br/>            Shapes[0] возвращает фигуру, находящуюся в заднем плане z-слоя,<br/>            а Shapes[Shapes.Count - 1] — фигуру, находящуюся в переднем плане.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/pictureframe/connection_site_count/) | Возвращает количество точек подключения на фигуре.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/pictureframe/rotation/) | Возвращает или задает угол поворота фигуры вокруг оси z в градусах.<br/>            Положительное значение — по часовой стрелке; отрицательное — против часовой.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/pictureframe/x/) | Получает или задает координату x левого верхнего угла фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/pictureframe/y/) | Получает или задает координату y левого верхнего угла фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/pictureframe/width/) | Получает или задает ширину фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/pictureframe/height/) | Получает или задает высоту фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/pictureframe/black_white_mode/) | Свойство указывает, как фигура будет отображаться в режиме черно-белого.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/pictureframe/unique_id/) | Возвращает внутренний идентификатор, привязанный к презентации, предназначенный для использования дополнениями или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя считать постоянным уникальным ключом.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/pictureframe/office_interop_shape_id/) | Возвращает уникальный идентификатор, привязанный к слайду, который остаётся неизменным в течение жизни фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/pictureframe/alternative_text/) | Возвращает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/pictureframe/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанного с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/pictureframe/name/) | Возвращает или задает имя фигуры.<br/>            Не должно быть None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/pictureframe/is_decorative/) | Получает или задает параметр «Отметить как декоративный»<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/pictureframe/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только для чтения [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/pictureframe/is_grouped/) | Определяет, сгруппирована ли фигура.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/pictureframe/parent_group/) | Возвращает объект родительской GroupShape, если фигура сгруппирована. Иначе возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/pictureframe/slide/) | Возвращает родительский слайд фигуры.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/pictureframe/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ru/aspose.slides/pictureframe/shape_style/) | Возвращает объект стиля фигуры.<br/>            Только для чтения [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides/pictureframe/shape_type/) | Возвращает или задает тип AutoShape для PictureFrame.<br/>            Допустимы все элементы множества [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype), <br/>            кроме всех видов линий:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Чтение/запись [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides/pictureframe/adjustments/) | Возвращает коллекцию значений коррекции фигуры.<br/>            Только для чтения [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ru/aspose.slides/pictureframe/picture_frame_lock/) | Возвращает блокировки фигуры.<br/>            Только для чтения [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ru/aspose.slides/pictureframe/picture_format/) | Возвращает объект PictureFillFormat для рамки изображения.<br/>            Только для чтения [`IPictureFillFormat`](/slides/python-net/ru/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ru/aspose.slides/pictureframe/relative_scale_height/) | Возвращает или задает масштаб высоты (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100 %.<br/>            Чтение/запись **float**. |
| [`relative_scale_width`](/slides/python-net/ru/aspose.slides/pictureframe/relative_scale_width/) | Возвращает или задает масштаб ширины (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100 %.<br/>            Чтение/запись **float**. |
| [`is_cameo`](/slides/python-net/ru/aspose.slides/pictureframe/is_cameo/) | Определяет, является ли PictureFrame объектом Cameo.<br/>            Только для чтения **bool**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/pictureframe/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/pictureframe/remove_placeholder/#) | Определяет, что эта фигура не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя заданному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/pictureframe/get_base_placeholder/#) | Возвращает базовый объект-заполнитель (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура).<br/>            Возвращает None, если текущая фигура не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/pictureframe/get_visual_bounds/#) | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/pictureframe/get_geometry_paths/#) | Возвращает копию пути геометрической фигуры. Координаты относительны левому верхнему углу фигуры. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Обновляет геометрию фигуры из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительны левому<br/>             верхнему углу фигуры.<br/>             Меняет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Обновляет геометрию фигуры из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительны левому<br/>             верхнему углу фигуры.<br/>             Меняет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/pictureframe/create_shape_elements/#) | Создаёт и возвращает массив элементов фигуры. |


### См. также
* class [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* class [`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe)
* class [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)