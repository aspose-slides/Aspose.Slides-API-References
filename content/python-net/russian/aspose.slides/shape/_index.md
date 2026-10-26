---
title: Shape class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shape/
---
## Класс Shape

Представляет форму на слайде.

Тип Shape раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/shape/is_text_holder/) | Определяет, является ли форма TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/shape/placeholder/) | Возвращает заполнитель для формы. Возвращает None, если у формы нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/shape/custom_data/) | Возвращает пользовательские данные формы.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/shape/raw_frame/) | Возвращает или задает свойства необработанной рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/shape/frame/) | Возвращает или задает свойства рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/shape/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для формы.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет свойств линий.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/shape/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для формы.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет 3D-свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/shape/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к форме.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет свойств эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/shape/fill_format/) | Возвращает объект FillFormat, содержащий свойства заполнения для формы.<br/>            Примечание: может вернуть None для некоторых типов форм, у которых нет свойств заполнения.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/shape/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/shape/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую для наведения курсора.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/shape/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/shape/hidden/) | Определяет, скрыта ли форма.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/shape/z_order_position/) | Возвращает позицию формы в порядке z-координат.<br/>            Shapes[0] возвращает форму в задней части порядка z-координат,<br/>            а Shapes[Shapes.Count - 1] возвращает форму в передней части порядка z-координат.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/shape/connection_site_count/) | Возвращает количество точек соединения на форме.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/shape/rotation/) | Возвращает или задает количество градусов, на которое указана форма вращается вокруг оси z.<br/>            Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/shape/x/) | Получает или задает координату x левого верхнего угла формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/shape/y/) | Получает или задает координату y левого верхнего угла формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/shape/width/) | Получает или задает ширину формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/shape/height/) | Получает или задает высоту формы, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/shape/black_white_mode/) | Свойство определяет, как форма будет отображаться в режиме черно-белого отображения.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id/) | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переименовано пользователем или программно, его нельзя рассматривать<br/>            как постоянный уникальный ключ.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id/) | Возвращает уникальный идентификатор в пределах слайда, который остаётся неизменным на протяжении жизни формы и<br/>            позволяет PowerPoint или коду взаимодействия надежно ссылаться на форму из любой части документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/shape/alternative_text/) | Возвращает или задает альтернативный текст, связанный с формой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/shape/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанный с формой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/shape/name/) | Возвращает или задает имя формы.<br/>            Не должно быть None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/shape/is_decorative/) | Получает или задает параметр 'Отметить как декоративный'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/shape/shape_lock/) | Возвращает блокировки формы.<br/>            Только для чтения [`IBaseShapeLock`](/slides/python-net/ru/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/shape/is_grouped/) | Определяет, сгруппирована ли форма.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/shape/parent_group/) | Возвращает объект родительской группы GroupShape, если форма сгруппирована. В противном случае возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/shape/slide/) | Возвращает родительский слайд формы.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/shape/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/shape/get_image/#) | Возвращает миниатюру формы.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру формы. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/shape/write_as_svg/#iorawiobase) | Сохраняет содержимое Shape в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое Shape в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/shape/remove_placeholder/#) | Определяет, что эта форма не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/shape/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанным. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/shape/get_base_placeholder/#) | Возвращает базовую форму-заполнитель (форму из макета и/или главного слайда, от которой унаследована текущая форма).<br/>            Возвращает None, если текущая форма не унаследована. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/shape/get_visual_bounds/#) | Получает визуальные границы формы, вычисленные из её отрисованного содержимого. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)