---
title: SectionZoomFrame class
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame класс

Представляет объект Section Zoom на слайде.

**Наследование:**[`SectionZoomFrame`](/slides/python-net/ru/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/ru/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

The SectionZoomFrame type exposes the following members:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/sectionzoomframe/is_text_holder/) | Определяет, является ли объект фигурой TextHolder_PPT.<br/>            Только чтение **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/sectionzoomframe/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только чтение [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/sectionzoomframe/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только чтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/sectionzoomframe/raw_frame/) | Возвращает или задает свойства необработанной рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/sectionzoomframe/frame/) | Возвращает или задает свойства рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/sectionzoomframe/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линии для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линии.<br/>            Только чтение [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/sectionzoomframe/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3D-свойств.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/sectionzoomframe/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств эффектов.<br/>            Только чтение [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/sectionzoomframe/fill_format/) | Возвращает объект FillFormat, содержащий свойства заливки для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств заливки.<br/>            Только чтение [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/sectionzoomframe/hyperlink_click/) | Возвращает или задает гиперссылку, определенную для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определенную для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/sectionzoomframe/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только чтение [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/sectionzoomframe/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/sectionzoomframe/z_order_position/) | Возвращает позицию фигуры в порядке z.<br/>            Shapes[0] возвращает фигуру в конце порядка z,<br/>            а Shapes[Shapes.Count - 1] возвращает фигуру в начале порядка z.<br/>            Только чтение **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/sectionzoomframe/connection_site_count/) | Возвращает количество точек соединения на фигуре.<br/>            Только чтение **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/sectionzoomframe/rotation/) | Возвращает или задает количество градусов, на которое указана фигура вращена вокруг оси z.<br/>            Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/sectionzoomframe/x/) | Получает или задает координату x верхнего левого угла фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/sectionzoomframe/y/) | Получает или задает координату y верхнего левого угла фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/sectionzoomframe/width/) | Получает или задает ширину фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/sectionzoomframe/height/) | Получает или задает высоту фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/sectionzoomframe/black_white_mode/) | Свойство определяет, как фигура будет отображаться в черно-белом режиме.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/sectionzoomframe/unique_id/) | Возвращает внутренний идентификатор в рамках презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переназначено пользователем или программно, его нельзя рассматривать<br/>            как постоянный уникальный ключ.<br/>            Только чтение **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/sectionzoomframe/office_interop_shape_id/) | Возвращает уникальный идентификатор в рамках слайда, который остается постоянным на протяжении жизни фигуры и<br/>            позволяет PowerPoint или коду межоперации надежно ссылаться на фигуру из любой части документа.<br/>            Только чтение **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/sectionzoomframe/alternative_text/) | Возвращает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/sectionzoomframe/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/sectionzoomframe/name/) | Возвращает или задает имя фигуры.<br/>            Не должно быть None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/sectionzoomframe/is_decorative/) | Получает или задает параметр 'Mark as decorative'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/sectionzoomframe/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/sectionzoomframe/is_grouped/) | Определяет, сгруппирована ли фигура.<br/>            Только чтение **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/sectionzoomframe/parent_group/) | Возвращает объект GroupShape-родитель, если фигура сгруппирована. В противном случае возвращает None.<br/>            Только чтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/sectionzoomframe/slide/) | Возвращает слайд-родитель фигуры.<br/>            Только чтение [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/sectionzoomframe/presentation/) | Возвращает презентацию-родитель слайда.<br/>            Только чтение [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides/sectionzoomframe/graphical_object_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ru/aspose.slides/sectionzoomframe/image_type/) | Получает или задает тип изображения объекта зум.<br/>            Чтение/запись [`ZoomImageType`](/slides/python-net/ru/aspose.slides/zoomimagetype).<br/>            Значение по умолчанию: Preview |
| [`return_to_parent`](/slides/python-net/ru/aspose.slides/sectionzoomframe/return_to_parent/) | Получает или задает поведение навигации в слайд-шоу.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию: false |
| [`show_background`](/slides/python-net/ru/aspose.slides/sectionzoomframe/show_background/) | Получает или задает значение, указывающее, будет ли Zoom использовать фон целевого слайда.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию: true |
| [`zoom_image`](/slides/python-net/ru/aspose.slides/sectionzoomframe/zoom_image/) | Получает или задает изображение для объекта зум.<br/>            Чтение/запись [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ru/aspose.slides/sectionzoomframe/transition_duration/) | Получает или задает длительность перехода между Zoom и слайдом.<br/>            Чтение/запись **float**.<br/>            Значение по умолчанию: 1.0f |
| [`target_section`](/slides/python-net/ru/aspose.slides/sectionzoomframe/target_section/) | Получает или задает объект раздела, к которому привязан объект Section Zoom.<br/>            Чтение/запись [`ISection`](/slides/python-net/ru/aspose.slides/isection). |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип ShapeThumbnailBounds.Shape для границ миниатюры. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/remove_placeholder/#) | Определяет, что эта фигура не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/get_base_placeholder/#) | Возвращает базовую форму-заполнитель (фигуру из макета и/или мастер-слайда, от которой унаследована текущая фигура).<br/>            Возвращает None, если текущая фигура не унаследована. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/sectionzoomframe/get_visual_bounds/#) | Получает визуальные границы фигуры, рассчитанные из её отрисованного содержимого. |

### См. также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`SectionZoomFrame`](/slides/python-net/ru/aspose.slides/sectionzoomframe)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* класс [`ZoomObject`](/slides/python-net/ru/aspose.slides/zoomobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)