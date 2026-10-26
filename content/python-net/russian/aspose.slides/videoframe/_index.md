---
title: VideoFrame class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/videoframe/
---
## VideoFrame класс

Представляет видеоклип на слайде.

**Наследование:**[`VideoFrame`](/slides/python-net/ru/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип VideoFrame раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/videoframe/is_text_holder/) | Определяет, является ли объект формой TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/videoframe/placeholder/) | Возвращает заполнитель для формы. Возвращает None, если у формы нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/videoframe/custom_data/) | Возвращает пользовательские данные формы.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/videoframe/raw_frame/) | Возвращает или задаёт необработанные свойства фрейма формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/videoframe/frame/) | Возвращает или задаёт свойства фрейма формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/videoframe/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для формы.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет свойств линий.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/videoframe/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для формы.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет 3D-свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/videoframe/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к форме.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет свойств эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/videoframe/fill_format/) | Возвращает объект FillFormat, содержащий свойства заливки для формы.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет свойств заливки.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/videoframe/hyperlink_click/) | Возвращает или задаёт гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/videoframe/hyperlink_mouse_over/) | Возвращает или задаёт гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/videoframe/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/videoframe/hidden/) | Определяет, скрыта ли форма.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/videoframe/z_order_position/) | Возвращает позицию формы в порядке z.<br/>            Shapes[0] возвращает форму, находящуюся в самом заднем положении порядка z,<br/>            а Shapes[Shapes.Count - 1] — форму в самом переднем положении.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/videoframe/connection_site_count/) | Возвращает количество точек соединения на форме.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/videoframe/rotation/) | Возвращает или задаёт угол в градусах, на который указана форма повёрнута вокруг оси z.<br/>            Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/videoframe/x/) | Получает или задаёт координату x левого верхнего угла формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/videoframe/y/) | Получает или задаёт координату y левого верхнего угла формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/videoframe/width/) | Получает или задаёт ширину формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/videoframe/height/) | Получает или задаёт высоту формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/videoframe/black_white_mode/) | Свойство указывает, как форма будет отображаться в режиме черно-белого отображения.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/videoframe/unique_id/) | Возвращает внутренний идентификатор, ограниченный областью презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя использовать как постоянный уникальный ключ.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/videoframe/office_interop_shape_id/) | Возвращает уникальный идентификатор, ограниченный областью слайда, который остаётся неизменным в течение всего срока жизни формы и позволяет PowerPoint или коду межоперационного взаимодействия надёжно ссылаться на форму из любой части документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/videoframe/alternative_text/) | Возвращает или задаёт альтернативный текст, связанный с формой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/videoframe/alternative_text_title/) | Возвращает или задаёт заголовок альтернативного текста, связанного с формой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/videoframe/name/) | Возвращает или задаёт имя формы.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/videoframe/is_decorative/) | Получает или задаёт параметр «Отметить как декоративный»<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/videoframe/shape_lock/) | Возвращает блокировки формы.<br/>            Только для чтения [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/videoframe/is_grouped/) | Определяет, объединена ли форма в группу.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/videoframe/parent_group/) | Возвращает объект родительской группы GroupShape, если форма находится в группе. В противном случае возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/videoframe/slide/) | Возвращает родительский слайд формы.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/videoframe/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ru/aspose.slides/videoframe/shape_style/) | Возвращает объект стиля формы.<br/>            Только для чтения [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides/videoframe/shape_type/) | Возвращает или задаёт тип AutoShape для PictureFrame.<br/>            Допустимы все элементы набора [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype), за исключением всех видов линий:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Чтение/запись [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides/videoframe/adjustments/) | Возвращает коллекцию значений корректировок формы.<br/>            Только для чтения [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ru/aspose.slides/videoframe/picture_frame_lock/) | Возвращает блокировки формы.<br/>            Только для чтения [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ru/aspose.slides/videoframe/picture_format/) | Возвращает объект PictureFillFormat для кадра изображения.<br/>            Только для чтения [`IPictureFillFormat`](/slides/python-net/ru/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ru/aspose.slides/videoframe/relative_scale_height/) | Возвращает или задаёт масштаб высоты (относительно оригинального размера изображения) кадра изображения. Значение 1.0 соответствует 100 %.<br/>            Чтение/запись **float**. |
| [`relative_scale_width`](/slides/python-net/ru/aspose.slides/videoframe/relative_scale_width/) | Возвращает или задаёт масштаб ширины (относительно оригинального размера изображения) кадра изображения. Значение 1.0 соответствует 100 %.<br/>            Чтение/запись **float**. |
| [`is_cameo`](/slides/python-net/ru/aspose.slides/videoframe/is_cameo/) | Определяет, является ли объект PictureFrame объектом Cameo.<br/>            Только для чтения **bool**. |
| [`rewind_video`](/slides/python-net/ru/aspose.slides/videoframe/rewind_video/) | Определяет, будет ли видео автоматически перемотываться в начало, как только воспроизведение завершится.<br/>            Чтение/запись **bool**. |
| [`play_loop_mode`](/slides/python-net/ru/aspose.slides/videoframe/play_loop_mode/) | Определяет, воспроизводится ли видео в цикле.<br/>            Чтение/запись **bool**. |
| [`hide_at_showing`](/slides/python-net/ru/aspose.slides/videoframe/hide_at_showing/) | Определяет, скрыт ли VideoFrame.<br/>            Чтение/запись **bool**. |
| [`volume`](/slides/python-net/ru/aspose.slides/videoframe/volume/) | Возвращает или задаёт громкость аудио.<br/>            Чтение/запись [`AudioVolumeMode`](/slides/python-net/ru/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ru/aspose.slides/videoframe/play_mode/) | Возвращает или задаёт режим воспроизведения видео.<br/>            Чтение/запись [`VideoPlayModePreset`](/slides/python-net/ru/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/ru/aspose.slides/videoframe/full_screen_mode/) | Определяет, отображается ли видео в полноэкранном режиме.<br/>            Чтение/запись **bool**. |
| [`link_path_long`](/slides/python-net/ru/aspose.slides/videoframe/link_path_long/) | Возвращает или задаёт имя видеофайла, связанного с VideoFrame.<br/>            Чтение/запись **str**. |
| [`embedded_video`](/slides/python-net/ru/aspose.slides/videoframe/embedded_video/) | Возвращает или задаёт встроенный объект видео.<br/>            Чтение/запись [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/ru/aspose.slides/videoframe/trim_from_start/) | Обрезка начала [мс] |
| [`trim_from_end`](/slides/python-net/ru/aspose.slides/videoframe/trim_from_end/) | Обрезка конца [мс] |
| [`caption_tracks`](/slides/python-net/ru/aspose.slides/videoframe/caption_tracks/) | Получает коллекцию закрытых субтитров, связанных с видеокадром.<br/>             Это свойство только для чтения и возвращает [`ICaptionsCollection`](/slides/python-net/ru/aspose.slides/icaptionscollection), содержащий все дорожки субтитров. |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_image/#) | Возвращает миниатюру формы.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру формы. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Сохраняет содержимое формы в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое формы в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/videoframe/remove_placeholder/#) | Определяет, что эта форма не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанным. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_base_placeholder/#) | Возвращает базовую форму-заполнитель (форму из макета и/или шаблона слайда, от которой наследуется текущая форма).<br/>            Возвращает None, если текущая форма не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_visual_bounds/#) | Получает визуальные границы формы, вычисленные по её отрисованному содержимому. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/videoframe/get_geometry_paths/#) | Возвращает копию пути геометрической формы. Координаты заданы относительно левого верхнего угла формы. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Обновляет геометрию формы из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть заданы относительно левого<br/>            верхнего угла формы.<br/>            Меняет тип формы ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Обновляет геометрию формы из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть заданы относительно левого<br/>            верхнего угла формы.<br/>            Меняет тип формы ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/videoframe/create_shape_elements/#) | Создаёт и возвращает массив элементов формы. |


### См. также
* class [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* class [`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe)
* class [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* class [`VideoFrame`](/slides/python-net/ru/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)