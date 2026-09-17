---
title: IShape class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/ishape/
---
## IShape класс

Представляет форму на слайде.

Тип IShape раскрывает следующие члены:

## Свойства

| С свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/ishape/is_text_holder/) | Определяет, является ли форма TextHolder.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/ishape/placeholder/) | Возвращает заполнитель для формы.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/ishape/custom_data/) | Возвращает пользовательские данные формы.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/ishape/raw_frame/) | Возвращает или задаёт свойства необработанной рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/ishape/frame/) | Возвращает или задаёт свойства рамки формы.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/ishape/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для формы.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/ishape/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства форматирования линий для формы.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/ishape/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к форме.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/ishape/fill_format/) | Возвращает объект FillFormat, содержащий свойства форматирования заливки для формы.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/ru/aspose.slides/ishape/hidden/) | Определяет, скрыта ли форма.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/ishape/z_order_position/) | Возвращает позицию формы в порядке z.<br/>            Shapes[0] возвращает форму в самом конце порядка z,<br/>            а Shapes[Shapes.Count - 1] возвращает форму в самом начале порядка z.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/ishape/connection_site_count/) | Возвращает количество точек подключения на форме.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/ishape/rotation/) | Возвращает или задаёт количество градусов, на которое заданная форма вращается вокруг оси z.<br/>            Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/ishape/x/) | Получает или задаёт координату x левого верхнего угла формы, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/ishape/y/) | Получает или задаёт координату y левого верхнего угла формы, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/ishape/width/) | Получает или задаёт ширину формы, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/ishape/height/) | Получает или задаёт высоту формы, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/ishape/alternative_text/) | Возвращает или задаёт альтернативный текст, связанный с формой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/ishape/alternative_text_title/) | Возвращает или задаёт заголовок альтернативного текста, связанный с формой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/ishape/name/) | Возвращает или задаёт имя формы.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/ishape/is_decorative/) | Получает или задаёт опцию 'Mark as decorative'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/ishape/shape_lock/) | Возвращает блокировки формы.<br/>            Только для чтения [`IBaseShapeLock`](/slides/python-net/ru/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/ishape/unique_id/) | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя считать постоянным уникальным ключом.<br/>            Только для чтения **int**.<br/>            См. также [`IShape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/ishape/office_interop_shape_id/) | Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение жизни формы и позволяет PowerPoint или коду interop надёжно ссылаться на форму из любого места документа.<br/>            Только для чтения **int**.<br/>            См. также [`IShape.unique_id`](/slides/python-net/ru/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/ishape/is_grouped/) | Определяет, сгруппирована ли форма.<br/>            Только для чтения **bool**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/ishape/black_white_mode/) | Свойство указывает, как форма будет отображаться в режиме чёрно-белого отображения.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/ru/aspose.slides/ishape/parent_group/) | Возвращает объект GroupShape-родитель, если форма сгруппирована. В противном случае возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/ishape/hyperlink_manager/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/ishape/get_image/#) | Возвращает миниатюру формы.<br/>            По умолчанию используется тип ShapeThumbnailBounds.Shape для границ миниатюры формы. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру формы. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/ishape/write_as_svg/#iorawiobase) | Сохраняет содержимое Shape в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое Shape в файл SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/ishape/add_placeholder/#iplaceholder) | Добавляет новый placeholder, если его нет, и задаёт свойства placeholder указанному. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/ishape/remove_placeholder/#) | Определяет, что эта форма не является placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/ishape/get_base_placeholder/#) | Возвращает базовую форму placeholder (форму из макета и/или слайда-шаблона, от которой наследуется текущая форма).<br/>            Возвращает None, если текущая форма не наследуется. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)