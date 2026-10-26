---
title: ZoomObject class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/zoomobject/
---
## ZoomObject класс

Представляет объект Zoom на слайде.

**Inheritance:**[`ZoomObject`](/slides/python-net/ru/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип ZoomObject предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/zoomobject/is_text_holder/) | Определяет, является ли объект фигурой TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/zoomobject/placeholder/) | Возвращает заполнитель для формы. Возвращает None, если у формы нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/zoomobject/custom_data/) | Возвращает пользовательские данные формы.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/zoomobject/raw_frame/) | Возвращает или задаёт свойства необработанной рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/zoomobject/frame/) | Возвращает или задаёт свойства рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/zoomobject/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для формы.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет свойств линии.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/zoomobject/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для формы.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет 3D-свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/zoomobject/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к форме.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет свойств эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/zoomobject/fill_format/) | Возвращает объект FillFormat, содержащий свойства заливки для формы.<br/>            Примечание: может возвращать None для некоторых типов форм, у которых нет свойств заливки.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/zoomobject/hyperlink_click/) | Возвращает или задаёт гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/zoomobject/hyperlink_mouse_over/) | Возвращает или задаёт гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/zoomobject/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/zoomobject/hidden/) | Определяет, скрыта ли форма.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/zoomobject/z_order_position/) | Возвращает позицию формы в Z-порядке.<br/>            Shapes[0] возвращает форму, находящуюся сзади в Z-порядке,<br/>            а Shapes[Shapes.Count - 1] — форму, находящуюся спереди.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/zoomobject/connection_site_count/) | Возвращает количество точек соединения на форме.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/zoomobject/rotation/) | Возвращает или задаёт угол вращения формы вокруг оси Z в градусах.<br/>            Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/zoomobject/x/) | Получает или задаёт координату X левого верхнего угла формы в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/zoomobject/y/) | Получает или задаёт координату Y левого верхнего угла формы в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/zoomobject/width/) | Получает или задаёт ширину формы в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/zoomobject/height/) | Получает или задаёт высоту формы в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/zoomobject/black_white_mode/) | Свойство определяет, как форма будет отображаться в чёрно-белом режиме.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/zoomobject/unique_id/) | Возвращает внутренний идентификатор презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя использовать как постоянный уникальный ключ.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/zoomobject/office_interop_shape_id/) | Возвращает уникальный идентификатор слайд-объекта, сохраняющийся неизменным в течение жизни формы и позволяющий PowerPoint или коду межоперативного взаимодействия надёжно ссылаться на форму из любой части документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/zoomobject/alternative_text/) | Возвращает или задаёт альтернативный текст, связанный с формой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/zoomobject/alternative_text_title/) | Возвращает или задаёт заголовок альтернативного текста формы.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/zoomobject/name/) | Возвращает или задаёт имя формы.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/zoomobject/is_decorative/) | Получает или задаёт параметр «Пометить как декоративный».<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/zoomobject/shape_lock/) | Возвращает блокировки формы.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/zoomobject/is_grouped/) | Определяет, находится ли форма в группе.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/zoomobject/parent_group/) | Возвращает родительский объект GroupShape, если форма входит в группу. В противном случае возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/zoomobject/slide/) | Возвращает родительский слайд формы.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/zoomobject/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides/zoomobject/graphical_object_lock/) | Возвращает блокировки формы.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ru/aspose.slides/zoomobject/image_type/) | Получает или задаёт тип изображения объекта Zoom.<br/>            Чтение/запись [`ZoomImageType`](/slides/python-net/ru/aspose.slides/zoomimagetype).<br/>            Значение по умолчанию: Preview |
| [`return_to_parent`](/slides/python-net/ru/aspose.slides/zoomobject/return_to_parent/) | Получает или задаёт поведение навигации в слайд-шоу.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию: false |
| [`show_background`](/slides/python-net/ru/aspose.slides/zoomobject/show_background/) | Получает или задаёт, будет ли Zoom использовать фон целевого слайда.<br/>            Чтение/запись **bool**.<br/>            Значение по умолчанию: true |
| [`zoom_image`](/slides/python-net/ru/aspose.slides/zoomobject/zoom_image/) | Получает или задаёт изображение для объекта Zoom.<br/>            Чтение/запись [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ru/aspose.slides/zoomobject/transition_duration/) | Получает или задаёт длительность перехода между Zoom и слайдом.<br/>            Чтение/запись **float**.<br/>            Значение по умолчанию: 1.0f |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/zoomobject/get_image/#) | Возвращает миниатюру формы.<br/>            По умолчанию используется тип ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру формы. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Сохраняет содержимое формы в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое формы в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/zoomobject/remove_placeholder/#) | Определяет, что эта форма не является заполнительным объектом. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/zoomobject/get_base_placeholder/#) | Возвращает базовую форму-заполнитель (форму из макета и/или шаблона, от которой наследуется текущая форма).<br/>            Возвращает None, если текущая форма не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/zoomobject/get_visual_bounds/#) | Получает визуальные границы формы, вычисленные из её визуального содержимого. |

### Смотрите также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* класс [`ZoomObject`](/slides/python-net/ru/aspose.slides/zoomobject)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)