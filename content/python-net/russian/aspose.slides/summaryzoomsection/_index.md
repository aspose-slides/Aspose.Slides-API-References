---
title: SummaryZoomSection class
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection класс

Представляет объект Summary Zoom Section в кадре Summary Zoom.

**Наследование:**[`SummaryZoomSection`](/slides/python-net/ru/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/ru/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/ru/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип SummaryZoomSection открывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/summaryzoomsection/is_text_holder/) | Определяет, является ли объект TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/summaryzoomsection/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/summaryzoomsection/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/summaryzoomsection/raw_frame/) | Возвращает или задаёт свойства необработанной рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/summaryzoomsection/frame/) | Возвращает или задаёт свойства рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/summaryzoomsection/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линий.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/summaryzoomsection/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3D-свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/summaryzoomsection/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/summaryzoomsection/fill_format/) | Возвращает объект FillFormat, содержащий свойства заливки для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств заливки.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/summaryzoomsection/hyperlink_click/) | Возвращает или задаёт гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Возвращает или задаёт гиперссылку, определённую для наведения мыши.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/summaryzoomsection/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/summaryzoomsection/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/summaryzoomsection/z_order_position/) | Возвращает позицию фигуры в порядке z-слоёв.<br/>            Shapes[0] возвращает фигуру, находящуюся в задней части порядка z-слоёв,<br/>            а Shapes[Shapes.Count - 1] возвращает фигуру, находящуюся в передней части порядка z-слоёв.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/summaryzoomsection/connection_site_count/) | Возвращает количество точек подключения на фигуре.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/summaryzoomsection/rotation/) | Возвращает или задаёт количество градусов, на которое указанная фигура вращается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/summaryzoomsection/x/) | Получает или задаёт координату x левого верхнего угла фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/summaryzoomsection/y/) | Получает или задаёт координату y левого верхнего угла фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/summaryzoomsection/width/) | Получает или задаёт ширину фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/summaryzoomsection/height/) | Получает или задаёт высоту фигуры, измеряемую в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/summaryzoomsection/black_white_mode/) | Свойство определяет, как фигура будет отображаться в режиме черно-белого отображения.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/summaryzoomsection/unique_id/) | Возвращает внутренний идентификатор, относящийся к презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переназначено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Возвращает уникальный идентификатор, относящийся к слайду, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/summaryzoomsection/alternative_text/) | Возвращает или задаёт альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/summaryzoomsection/alternative_text_title/) | Возвращает или задаёт заголовок альтернативного текста, связанного с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/summaryzoomsection/name/) | Возвращает или задаёт имя фигуры.<br/>            Не должно быть None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/summaryzoomsection/is_decorative/) | Получает или задаёт параметр «Отметить как декоративный»<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/summaryzoomsection/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/summaryzoomsection/is_grouped/) | Определяет, находится ли фигура в группе.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/summaryzoomsection/parent_group/) | Возвращает объект GroupShape-родителя, если фигура находится в группе. В противном случае возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/summaryzoomsection/slide/) | Возвращает слайд-родитель фигуры.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/summaryzoomsection/presentation/) | Возвращает презентацию-родителя слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides/summaryzoomsection/graphical_object_lock/) | Возвращает блокировки фигуры.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ru/aspose.slides/summaryzoomsection/image_type/) | Получает или задаёт тип изображения объекта зума.<br/>            Чтение/запись [`ZoomImageType`](/slides/python-net/ru/aspose.slides/zoomimagetype).<br/>            Значение по умолчанию: Preview |
| [`return_to_parent`](/slides/python-net/ru/aspose.slides/summaryzoomsection/return_to_parent/) | Получает или задаёт поведение навигации в слайд-шоу.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию: false |
| [`show_background`](/slides/python-net/ru/aspose.slides/summaryzoomsection/show_background/) | Получает или задаёт значение, указывающее, будет ли Zoom использовать фон целевого слайда.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию: true |
| [`zoom_image`](/slides/python-net/ru/aspose.slides/summaryzoomsection/zoom_image/) | Получает или задаёт изображение для объекта зума.<br/>            Чтение/запись [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ru/aspose.slides/summaryzoomsection/transition_duration/) | Получает или задаёт длительность перехода между Zoom и слайдом.<br/>            Чтение/запись **float**.<br/>            Значение по умолчанию: 1.0f |
| [`target_section`](/slides/python-net/ru/aspose.slides/summaryzoomsection/target_section/) | Получает или задаёт объект раздела, к которому привязан объект Section Zoom.<br/>            Чтение/запись [`ISection`](/slides/python-net/ru/aspose.slides/isection). |
| [`title`](/slides/python-net/ru/aspose.slides/summaryzoomsection/title/) | Возвращает текстовый заголовок объекта Summary Zoom Section. |
| [`description`](/slides/python-net/ru/aspose.slides/summaryzoomsection/description/) | Возвращает текстовое описание объекта Summary Zoom Section. |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Сохраняет содержимое Shape в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое Shape в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/remove_placeholder/#) | Определяет, что эта фигура не является заполняющим элементом. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Добавляет новый placeholder, если его нет, и задаёт свойства placeholder указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Возвращает базовую фигуру placeholder (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура).<br/>            Возвращает None, если текущая фигура не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |

### См. также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`SectionZoomFrame`](/slides/python-net/ru/aspose.slides/sectionzoomframe)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* класс [`SummaryZoomSection`](/slides/python-net/ru/aspose.slides/summaryzoomsection)
* класс [`ZoomObject`](/slides/python-net/ru/aspose.slides/zoomobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)