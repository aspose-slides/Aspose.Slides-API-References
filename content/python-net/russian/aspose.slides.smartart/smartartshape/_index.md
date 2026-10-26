---
title: SmartArtShape class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.smartart/smartartshape/
---
## SmartArtShape класс

Представляет форму SmartArt

**Наследование:**[`SmartArtShape`](/slides/python-net/ru/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип SmartArtShape предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/is_text_holder/) | Определяет, является ли форма TextHolder_PPT.<br/>            Только чтение **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/placeholder/) | Возвращает заполнитель для формы. Возвращает None, если у формы нет заполнителя.<br/>            Только чтение [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/custom_data/) | Возвращает пользовательские данные формы.<br/>            Только чтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/raw_frame/) | Возвращает или задает свойства сырой рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/frame/) | Возвращает или задает свойства рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для формы.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет свойств линий.<br/>            Только чтение [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для формы.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет 3D-свойств.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к форме.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет свойств эффектов.<br/>            Только чтение [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/fill_format/) | Возвращает объект FillFormat, содержащий свойства заполнения для формы.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет свойств заполнения.<br/>            Только чтение [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/hyperlink_click/) | Возвращает или задает гиперссылка, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Возвращает или задает гиперссылка, определённую для наведения мыши.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только чтение [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/hidden/) | Определяет, скрыта ли форма.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/z_order_position/) | Возвращает позицию формы в порядке Z.<br/>            Shapes[0] возвращает форму, находящуюся в самом заднем порядке Z,<br/>            а Shapes[Shapes.Count - 1] возвращает форму, находящуюся в самом переднем порядке Z.<br/>            Только чтение **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/connection_site_count/) | Возвращает количество точек соединения на форме.<br/>            Только чтение **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/rotation/) | Возвращает или задает количество градусов, на которое указанная форма вращается вокруг оси Z<br/>            Положительное значение указывает вращение по часовой стрелке; отрицательное значение<br/>            указывает вращение против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/x/) | Получает или задает координату X верхнего левого угла формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/y/) | Получает или задает координату Y верхнего левого угла формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/width/) | Получает или задает ширину формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/height/) | Получает или задает высоту формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/black_white_mode/) | Свойство задаёт, как форма будет отображаться в черно-белом режиме.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/unique_id/) | Возвращает внутренний идентификатор, ограниченный областью презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать<br/>            как постоянный уникальный ключ.<br/>            Только чтение **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Возвращает уникальный идентификатор, ограниченный областью слайда, остающийся постоянным в течение жизни формы и<br/>            позволяющий PowerPoint или коду interop надёжно ссылаться на форму из любой части документа.<br/>            Только чтение **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/alternative_text/) | Возвращает или задает альтернативный текст, связанный с формой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанного с формой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/name/) | Возвращает или задает имя формы.<br/>            Не должно быть None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/is_decorative/) | Получает или задает параметр 'Отметить как декоративный'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/shape_lock/) | Возвращает блокировки формы.<br/>            Только чтение [`IBaseShapeLock`](/slides/python-net/ru/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/is_grouped/) | Определяет, сгруппирована ли форма.<br/>            Только чтение **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/parent_group/) | Возвращает объект родительской группы GroupShape, если форма сгруппирована. В противном случае возвращает None.<br/>            Только чтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/slide/) | Возвращает родительский слайд формы.<br/>            Только чтение [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только чтение [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/shape_style/) | Возвращает объект стиля формы.<br/>            Только чтение [`IShapeStyle`](/slides/python-net/ru/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/shape_type/) | Возвращает или задает тип предустановки геометрии.<br/>            Примечание: при изменении значения все параметры настройки будут сброшены к значениям по умолчанию.<br/>            Чтение/запись [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/adjustments/) | Возвращает коллекцию значений настройки формы.<br/>            Только чтение [`IAdjustValueCollection`](/slides/python-net/ru/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/text_frame/) | Возвращает текст формы SmartArt.<br/>            Только чтение [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/get_image/#) | Возвращает миниатюру формы.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру формы. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Сохраняет содержимое формы в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое формы в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Определяет, что эта форма не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанным. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Возвращает базовую форму-заполнитель (форму из макета и/или мастер-слайда, от которой наследуется текущая форма).<br/>            Возвращает None, если текущая форма не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Получает визуальные границы формы, рассчитанные по её отрисованному содержимому. |
| [`get_geometry_paths(self)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Возвращает копию пути геометрической формы. Координаты относительно левого верхнего угла формы. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Обновляет геометрию формы из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительными к левому<br/>             верхнему углу формы.<br/>             Изменяет тип формы ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Обновляет геометрию формы из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительными к левому<br/>             верхнему углу формы.<br/>             Изменяет тип формы ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/ru/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Создаёт и возвращает массив элементов формы. |

### См. также
* класс [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* класс [`SmartArtShape`](/slides/python-net/ru/aspose.slides.smartart/smartartshape)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)