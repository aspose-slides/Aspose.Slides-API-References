---
title: Ink class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.ink/ink/
---
## Класс Ink

Представляет объект черни на слайде.

**Наследование:**[`Ink`](/slides/python-net/ru/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип Ink раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides.ink/ink/is_text_holder/) | Определяет, является ли объект фигурой TextHolder_PPT.<br/>            Только чтение **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides.ink/ink/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только чтение [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides.ink/ink/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только чтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides.ink/ink/raw_frame/) | Возвращает или задает свойства исходного кадра фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides.ink/ink/frame/) | Возвращает или задает свойства кадра фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides.ink/ink/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линии.<br/>            Только чтение [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides.ink/ink/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3D-свойств.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides.ink/ink/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств эффекта.<br/>            Только чтение [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides.ink/ink/fill_format/) | Возвращает объект FillFormat, содержащий свойства заполнения для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств заполнения.<br/>            Только чтение [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides.ink/ink/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides.ink/ink/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides.ink/ink/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только чтение [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides.ink/ink/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides.ink/ink/z_order_position/) | Возвращает позицию фигуры в порядке Z.<br/>            Shapes[0] возвращает фигуру в задней части порядка Z,<br/>            а Shapes[Shapes.Count - 1] возвращает фигуру в передней части порядка Z.<br/>            Только чтение **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides.ink/ink/connection_site_count/) | Возвращает количество точек подключения на фигуре.<br/>            Только чтение **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides.ink/ink/rotation/) | Возвращает или задает количество градусов, на которое указанная фигура вращается вокруг оси Z.<br/>            Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides.ink/ink/x/) | Получает или задает координату X верхнего левого угла фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides.ink/ink/y/) | Получает или задает координату Y верхнего левого угла фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides.ink/ink/width/) | Получает или задает ширину фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides.ink/ink/height/) | Получает или задает высоту фигуры, измеренную в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides.ink/ink/black_white_mode/) | Свойство определяет, как фигура будет отображаться в режиме черно-белого отображения.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides.ink/ink/unique_id/) | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования ад-инами или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать<br/>            как постоянный уникальный ключ.<br/>            Только чтение **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides.ink/ink/office_interop_shape_id/) | Возвращает уникальный идентификатор в пределах слайда, который остаётся постоянным в течение срока жизни фигуры и<br/>            позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа.<br/>            Только чтение **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides.ink/ink/alternative_text/) | Возвращает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides.ink/ink/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides.ink/ink/name/) | Возвращает или задает имя фигуры.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides.ink/ink/is_decorative/) | Получает или задает параметр 'Отметить как декоративный'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides.ink/ink/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides.ink/ink/is_grouped/) | Определяет, сгруппирована ли фигура.<br/>            Только чтение **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides.ink/ink/parent_group/) | Возвращает объект родительской группы GroupShape, если фигура сгруппирована. В противном случае возвращает None.<br/>            Только чтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides.ink/ink/slide/) | Возвращает родительский слайд фигуры.<br/>            Только чтение [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides.ink/ink/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только чтение [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides.ink/ink/graphical_object_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/ru/aspose.slides.ink/ink/traces/) | Получает все трассы, содержащиеся в элементе IInk [`IInkTrace`](/slides/python-net/ru/aspose.slides.ink/iinktrace).<br/>            Только чтение. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides.ink/ink/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип ShapeThumbnailBounds.Shape для границ миниатюры. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides.ink/ink/remove_placeholder/#) | Определяет, что эта фигура не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides.ink/ink/get_base_placeholder/#) | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или слайда-шаблона, от которой наследуется текущая фигура).<br/>            Возвращает None, если текущая фигура не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides.ink/ink/get_visual_bounds/#) | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/ru/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Регистрирует изображение в коллекцию пользовательских изображений, используемых для имитации визуальных эффектов кистей черни.<br/>            Эти изображения используются при отрисовке черни с конкретными значениями [`InkEffectType`](/slides/python-net/ru/aspose.slides.ink/inkeffecttype),<br/>            такими как Galaxy, Rainbow и т.д. Предоставив собственные изображения, вы можете контролировать внешний вид каждого эффекта черни. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/ru/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Удаляет регистрацию изображения из коллекции пользовательских изображений, использующихся для имитации визуальных эффектов кистей черни,<br/>            предварительно зарегистрированных через **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Смотрите также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`Ink`](/slides/python-net/ru/aspose.slides.ink/ink)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)