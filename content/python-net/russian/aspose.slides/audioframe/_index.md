---
title: AudioFrame class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/audioframe/
---
## AudioFrame класс

Represents an audio clip on a slide.

**Inheritance:**[`AudioFrame`](/slides/python-net/ru/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

The AudioFrame type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/audioframe/is_text_holder/) | Определяет, является ли фигура TextHolder_PPT.<br/>            Только чтение **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/audioframe/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только чтение [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/audioframe/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только чтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/audioframe/raw_frame/) | Возвращает или задает свойства исходного кадра фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/audioframe/frame/) | Возвращает или задает свойства кадра фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/audioframe/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линии для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линии.<br/>            Только чтение [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/audioframe/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3D-свойств.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/audioframe/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств эффектов.<br/>            Только чтение [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/audioframe/fill_format/) | Возвращает объект FillFormat, содержащий свойства заполнения для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств заполнения.<br/>            Только чтение [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/audioframe/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для клика мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/audioframe/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/audioframe/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только чтение [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/audioframe/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/audioframe/z_order_position/) | Возвращает позицию фигуры в порядке z.<br/>            Shapes[0] возвращает фигуру в задней части порядка z,<br/>            а Shapes[Shapes.Count - 1] возвращает фигуру в передней части порядка z.<br/>            Только чтение **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/audioframe/connection_site_count/) | Возвращает количество точек подключения на фигуре.<br/>            Только чтение **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/audioframe/rotation/) | Возвращает или задает количество градусов, на которые указанная фигура вращается вокруг оси z.<br/>            Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/audioframe/x/) | Возвращает или задает координату x верхнего левого угла фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/audioframe/y/) | Возвращает или задает координату y верхнего левого угла фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/audioframe/width/) | Возвращает или задает ширину фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/audioframe/height/) | Возвращает или задает высоту фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/audioframe/black_white_mode/) | Свойство определяет, как фигура будет отображаться в черно-белом режиме.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/audioframe/unique_id/) | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования дополнениями или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ.<br/>            Только чтение **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/audioframe/office_interop_shape_id/) | Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа.<br/>            Только чтение **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/audioframe/alternative_text/) | Возвращает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/audioframe/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанного с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/audioframe/name/) | Возвращает или задает имя фигуры.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/audioframe/is_decorative/) | Возвращает или задает опцию «Отметить как декоративную»<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/audioframe/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/audioframe/is_grouped/) | Определяет, сгруппирована ли фигура.<br/>            Только чтение **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/audioframe/parent_group/) | Возвращает объект родительской группы GroupShape, если фигура сгруппирована. В противном случае возвращает None.<br/>            Только чтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/audioframe/slide/) | Возвращает родительский слайд фигуры.<br/>            Только чтение [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/audioframe/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только чтение [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ru/aspose.slides/audioframe/shape_style/) | Возвращает объект стиля фигуры.<br/>            Только чтение [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides/audioframe/shape_type/) | Возвращает или задает тип AutoShape для PictureFrame.<br/>            Допустимы все элементы набора [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype), <br/>            за исключением всех видов линий:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Чтение/запись [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides/audioframe/adjustments/) | Возвращает коллекцию значений регулировки фигуры.<br/>            Только чтение [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ru/aspose.slides/audioframe/picture_frame_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IPictureFrameLock`](/slides/python-net/ru/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ru/aspose.slides/audioframe/picture_format/) | Возвращает объект PictureFillFormat для рамки изображения.<br/>            Только чтение [`IPictureFillFormat`](/slides/python-net/ru/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ru/aspose.slides/audioframe/relative_scale_height/) | Возвращает или задает масштаб высоты (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%.<br/>            Чтение/запись **float**. |
| [`relative_scale_width`](/slides/python-net/ru/aspose.slides/audioframe/relative_scale_width/) | Возвращает или задает масштаб ширины (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%.<br/>            Чтение/запись **float**. |
| [`is_cameo`](/slides/python-net/ru/aspose.slides/audioframe/is_cameo/) | Определяет, является ли PictureFrame объектом Cameo.<br/>            Только чтение **bool**. |
| [`audio_cd_start_track`](/slides/python-net/ru/aspose.slides/audioframe/audio_cd_start_track/) | Возвращает или задает индекс начального трека.<br/>            Чтение/запись **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/ru/aspose.slides/audioframe/audio_cd_start_track_time/) | Возвращает или задает время начала трека.<br/>            Чтение/запись **int**. |
| [`audio_cd_end_track`](/slides/python-net/ru/aspose.slides/audioframe/audio_cd_end_track/) | Возвращает или задает индекс последнего трека.<br/>            Чтение/запись **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/ru/aspose.slides/audioframe/audio_cd_end_track_time/) | Возвращает или задает время последнего трека.<br/>            Чтение/запись **int**. |
| [`volume`](/slides/python-net/ru/aspose.slides/audioframe/volume/) | Возвращает или задает громкость аудио.<br/>            Чтение/запись [`AudioVolumeMode`](/slides/python-net/ru/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ru/aspose.slides/audioframe/play_mode/) | Возвращает или задает режим воспроизведения аудио.<br/>            Чтение/запись [`AudioPlayModePreset`](/slides/python-net/ru/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/ru/aspose.slides/audioframe/hide_at_showing/) | Определяет, скрыт ли AudioFrame.<br/>            Чтение/запись **bool**. |
| [`play_loop_mode`](/slides/python-net/ru/aspose.slides/audioframe/play_loop_mode/) | Определяет, воспроизводится ли аудио в цикле.<br/>            Чтение/запись **bool**. |
| [`play_across_slides`](/slides/python-net/ru/aspose.slides/audioframe/play_across_slides/) | Определяет, воспроизводится ли аудио на всех слайдах.<br/>            Чтение/запись **bool**. |
| [`rewind_audio`](/slides/python-net/ru/aspose.slides/audioframe/rewind_audio/) | Определяет, будет ли аудио автоматически перемотываться в начало после воспроизведения.<br/>            Чтение/запись **bool**. |
| [`embedded`](/slides/python-net/ru/aspose.slides/audioframe/embedded/) | Определяет, встроен ли звук в презентацию.<br/>            Только чтение **bool**. |
| [`link_path_long`](/slides/python-net/ru/aspose.slides/audioframe/link_path_long/) | Возвращает или задает имя аудиофайла, связанного с AudioFrame.<br/>            Чтение/запись **str**. |
| [`embedded_audio`](/slides/python-net/ru/aspose.slides/audioframe/embedded_audio/) | Возвращает или задает встроенный аудиообъект.<br/>            Чтение/запись [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/ru/aspose.slides/audioframe/fade_in_duration/) | Задаёт длительность начального плавного появления медиа в миллисекундах.<br/>            Чтение/запись **float**. |
| [`fade_out_duration`](/slides/python-net/ru/aspose.slides/audioframe/fade_out_duration/) | Задаёт длительность конечного плавного исчезновения медиа в миллисекундах.<br/>            Чтение/запись **float**. |
| [`volume_value`](/slides/python-net/ru/aspose.slides/audioframe/volume_value/) | Возвращает или задает громкость аудио в процентах.<br/>            Чтение/запись **float**. |
| [`trim_from_start`](/slides/python-net/ru/aspose.slides/audioframe/trim_from_start/) | Задаёт длительность, которую нужно удалить с начала медиа при воспроизведении, в миллисекундах.<br/>            Чтение/запись **float**. |
| [`trim_from_end`](/slides/python-net/ru/aspose.slides/audioframe/trim_from_end/) | Задаёт длительность, которую нужно удалить с конца медиа при воспроизведении, в миллисекундах.<br/>            Чтение/запись **float**. |
| [`caption_tracks`](/slides/python-net/ru/aspose.slides/audioframe/caption_tracks/) | Получает коллекцию закрытых субтитров, связанных с аудио-кадром.<br/>            Это свойство только для чтения и возвращает [`ICaptionsCollection`](/slides/python-net/ru/aspose.slides/icaptionscollection), содержащий все дорожки субтитров. |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/audioframe/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип границ миниатюры фигуры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/audioframe/remove_placeholder/#) | Определяет, что эта фигура не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/audioframe/get_base_placeholder/#) | Возвращает базовую форму заполнителя (фигуру из макета и/или главного слайда, от которой наследуется текущая фигура).<br/>            Возвращает None, если текущая фигура не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/audioframe/get_visual_bounds/#) | Получает визуальные границы фигуры, рассчитанные на основе её отрисованного содержимого. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides/audioframe/get_geometry_paths/#) | Возвращает копию пути геометрической фигуры. Координаты относительны к левому верхнему углу фигуры. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Обновляет геометрию фигуры из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительны к левому<br/>             верхнему углу фигуры.<br/>             Меняет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Обновляет геометрию фигуры из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительны к левому<br/>             верхнему углу фигуры.<br/>             Меняет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides/audioframe/create_shape_elements/#) | Создаёт и возвращает массив элементов фигуры. |

### См. также
* класс [`AudioFrame`](/slides/python-net/ru/aspose.slides/audioframe)
* класс [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* класс [`PictureFrame`](/slides/python-net/ru/aspose.slides/pictureframe)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)