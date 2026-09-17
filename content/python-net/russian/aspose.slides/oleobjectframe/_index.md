---
title: OleObjectFrame class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/oleobjectframe/
---
## OleObjectFrame класс

Представляет объект OLE на слайде.

**Наследование:**[`OleObjectFrame`](/slides/python-net/ru/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип OleObjectFrame раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/oleobjectframe/is_text_holder/) | Определяет, является ли объект TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/oleobjectframe/placeholder/) | Возвращает заполнитель для объекта. Возвращает None, если у объекта нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/oleobjectframe/custom_data/) | Возвращает пользовательские данные объекта.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/oleobjectframe/raw_frame/) | Возвращает или задает свойства необработанного кадра объекта.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/oleobjectframe/frame/) | Возвращает или задает свойства кадра объекта.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/oleobjectframe/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для объекта.<br/>            Примечание: может вернуть None для некоторых типов объектов, у которых нет свойств линий.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/oleobjectframe/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3-d эффекта для объекта.<br/>            Примечание: может вернуть None для некоторых типов объектов, у которых нет 3-d свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/oleobjectframe/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к объекту.<br/>            Примечание: может вернуть None для некоторых типов объектов, у которых нет свойств эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/oleobjectframe/fill_format/) | Возвращает объект FillFormat, содержащий свойства заливки для объекта.<br/>            Примечание: может вернуть None для некоторых типов объектов, у которых нет свойств заливки.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/oleobjectframe/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/oleobjectframe/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/oleobjectframe/hidden/) | Определяет, скрыт ли объект.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/oleobjectframe/z_order_position/) | Возвращает положение объекта в порядке z-слоя.<br/>            Shapes[0] возвращает объект, находящийся в самом заднем слое,<br/>            а Shapes[Shapes.Count - 1] — в самом переднем.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/oleobjectframe/connection_site_count/) | Возвращает количество точек соединения на объекте.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/oleobjectframe/rotation/) | Возвращает или задает угол поворота объекта вокруг оси z в градусах.<br/>            Положительное значение — по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/oleobjectframe/x/) | Возвращает или задает координату x левого верхнего угла объекта в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/oleobjectframe/y/) | Возвращает или задает координату y левого верхнего угла объекта в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/oleobjectframe/width/) | Возвращает или задает ширину объекта в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/oleobjectframe/height/) | Возвращает или задает высоту объекта в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/oleobjectframe/black_white_mode/) | Свойство определяет, как объект будет отображаться в режиме черно-белого отображения.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/oleobjectframe/unique_id/) | Возвращает внутренний идентификатор, привязанный к презентации, предназначенный для использования дополнениями или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/oleobjectframe/office_interop_shape_id/) | Возвращает уникальный идентификатор, ограниченный слайдом, постоянный в течение жизненного цикла объекта и позволяющий PowerPoint или коду интероп надёжно ссылаться на объект из любой части документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/oleobjectframe/alternative_text/) | Возвращает или задает альтернативный текст, связанный с объектом.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/oleobjectframe/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанного с объектом.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/oleobjectframe/name/) | Возвращает или задает имя объекта.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/oleobjectframe/is_decorative/) | Возвращает или задает параметр «Отметить как декоративный».<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/oleobjectframe/shape_lock/) | Возвращает блокировки объекта.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/oleobjectframe/is_grouped/) | Определяет, сгруппирован ли объект.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/oleobjectframe/parent_group/) | Возвращает родительский объект GroupShape, если объект сгруппирован. В противном случае возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/oleobjectframe/slide/) | Возвращает родительский слайд объекта.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/oleobjectframe/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides/oleobjectframe/graphical_object_lock/) | Возвращает блокировки объекта.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/ru/aspose.slides/oleobjectframe/substitute_picture_format/) | Возвращает объект свойств заливки изображения OleObject.<br/>            Только для чтения [`IPictureFillFormat`](/slides/python-net/ru/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/ru/aspose.slides/oleobjectframe/substitute_picture_title/) | Возвращает или задает заголовок для значка OleObject.<br/>            Чтение/запись **str**. |
| [`object_name`](/slides/python-net/ru/aspose.slides/oleobjectframe/object_name/) | Возвращает или задает имя объекта.<br/>            Чтение/запись **str**. |
| [`object_prog_id`](/slides/python-net/ru/aspose.slides/oleobjectframe/object_prog_id/) | Возвращает ProgID объекта.<br/>            Только для чтения **str**. |
| [`link_file_name`](/slides/python-net/ru/aspose.slides/oleobjectframe/link_file_name/) | Возвращает полный путь к связанному файлу. Будет использовано короткое имя файла.<br/>            Только для чтения **str**. |
| [`link_path_long`](/slides/python-net/ru/aspose.slides/oleobjectframe/link_path_long/) | Возвращает полный путь к связанному файлу. Будет использовано полное имя файла.<br/>            Чтение/запись **str**. |
| [`link_path_relative`](/slides/python-net/ru/aspose.slides/oleobjectframe/link_path_relative/) | Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку.<br/>            Только для чтения **str**. |
| [`embedded_file_label`](/slides/python-net/ru/aspose.slides/oleobjectframe/embedded_file_label/) | Возвращает имя файла встроенного OLE-объекта |
| [`embedded_file_name`](/slides/python-net/ru/aspose.slides/oleobjectframe/embedded_file_name/) | Возвращает путь к встроенному OLE-объекту |
| [`embedded_data`](/slides/python-net/ru/aspose.slides/oleobjectframe/embedded_data/) | Возвращает или задает информацию о встроенных данных OLE.<br/>            Чтение/запись [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/ru/aspose.slides/oleobjectframe/is_object_icon/) | Определяет, отображается ли объект как значок.<br/>            Чтение/запись **bool**. |
| [`is_object_link`](/slides/python-net/ru/aspose.slides/oleobjectframe/is_object_link/) | Определяет, связан ли объект с внешним файлом.<br/>            Только для чтения **bool**. |
| [`update_automatic`](/slides/python-net/ru/aspose.slides/oleobjectframe/update_automatic/) | Определяет, обновляется ли связанный встроенный объект автоматически при открытии или печати презентации.<br/>            Чтение/запись **bool**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/oleobjectframe/get_image/#) | Возвращает миниатюру объекта.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру объекта. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Сохраняет содержимое объекта как файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое объекта как файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/oleobjectframe/remove_placeholder/#) | Определяет, что этот объект не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/oleobjectframe/get_base_placeholder/#) | Возвращает базовый объект-заполнитель (объект из макета и/или шаблона слайда, от которого наследуется текущий объект).<br/>            Возвращает None, если текущий объект не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/oleobjectframe/get_visual_bounds/#) | Получает визуальные границы объекта, рассчитанные по его отрисованному содержимому. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/ru/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Задаёт информацию о встроенных данных OLE.<br/>            <br/>            Этот метод изменяет свойства объекта в соответствии с новыми данными и<br/>            устанавливает флаг IsObjectLink в false, указывая, что объект OLE встроен. |

### См. также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`OleObjectFrame`](/slides/python-net/ru/aspose.slides/oleobjectframe)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)