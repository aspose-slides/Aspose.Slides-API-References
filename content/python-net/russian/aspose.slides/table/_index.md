---
title: Table class
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/table/
---
## Table класс

Представляет таблицу на слайде.

**Наследование:**[`Table`](/slides/python-net/ru/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

Тип Table предоставляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/table/is_text_holder/) | Определяет, является ли фигура TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/table/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/table/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/table/raw_frame/) | Возвращает или задает свойства исходного фрейма фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/table/frame/) | Возвращает или задает свойства фрейма фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/table/line_format/) | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линий.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/table/three_d_format/) | Возвращает объект ThreeDFormat, который содержит свойства 3-D-эффектов для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3-D-свойств.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/table/effect_format/) | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет эффектов.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/table/fill_format/) | Возвращает объект TableFormat.FillFormat, содержащий параметры заливки для Table.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/table/hyperlink_click/) | Возвращает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/table/hyperlink_mouse_over/) | Возвращает или задает гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/table/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/table/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/table/z_order_position/) | Возвращает позицию фигуры в z-порядке.<br/>            Shapes[0] возвращает фигуру в задней части z-порядка,<br/>            а Shapes[Shapes.Count - 1] — в передней части.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/table/connection_site_count/) | Возвращает количество точек соединения у фигуры.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/table/rotation/) | Возвращает или задает угол поворота фигуры вокруг оси z в градусах.<br/>            Положительное значение обозначает вращение по часовой стрелке; отрицательное — против часовой.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/table/x/) | Получает или задает координату x левого верхнего угла фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/table/y/) | Получает или задает координату y левого верхнего угла фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/table/width/) | Получает или задает ширину фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/table/height/) | Получает или задает высоту фигуры в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/table/black_white_mode/) | Свойство определяет, как фигура будет отображаться в чёрно-белом режиме.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/table/unique_id/) | Возвращает внутренний идентификатор, привязанный к презентации, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/table/office_interop_shape_id/) | Возвращает уникальный идентификатор, привязанный к слайду, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду межопределения надёжно ссылаться на фигуру из любого места документа.<br/>            Только для чтения **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/table/alternative_text/) | Возвращает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/table/alternative_text_title/) | Возвращает или задает заголовок альтернативного текста, связанного с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/table/name/) | Возвращает или задает имя фигуры.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/table/is_decorative/) | Получает или задает опцию «Отметить как декоративный».<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/table/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/table/is_grouped/) | Определяет, находится ли фигура в группе.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/table/parent_group/) | Возвращает объект родительской GroupShape, если фигура сгруппирована. Иначе возвращает None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/table/slide/) | Возвращает родительский слайд фигуры.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/table/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides/table/graphical_object_lock/) | Возвращает блокировки фигуры.<br/>            Только для чтения [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/ru/aspose.slides/table/rows/) | Возвращает коллекцию строк.<br/>            Только для чтения [`IRowCollection`](/slides/python-net/ru/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/ru/aspose.slides/table/columns/) | Возвращает коллекцию столбцов.<br/>            Только для чтения [`IColumnCollection`](/slides/python-net/ru/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/ru/aspose.slides/table/table_format/) | Возвращает объект TableFormat, содержащий свойства форматирования этой таблицы.<br/>            Только для чтения [`ITableFormat`](/slides/python-net/ru/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/ru/aspose.slides/table/style_preset/) | Получает или задает встроенный стиль таблицы.<br/>            Чтение/запись [`TableStylePreset`](/slides/python-net/ru/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/ru/aspose.slides/table/right_to_left/) | Определяет, имеет ли таблица порядок чтения справа налево.<br/>            Чтение/запись **bool**. |
| [`first_row`](/slides/python-net/ru/aspose.slides/table/first_row/) | Определяет, должна ли первая строка таблицы отображаться со специальным форматированием.<br/>            Чтение/запись **bool**. |
| [`first_col`](/slides/python-net/ru/aspose.slides/table/first_col/) | Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием.<br/>            Чтение/запись **bool**. |
| [`last_row`](/slides/python-net/ru/aspose.slides/table/last_row/) | Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием.<br/>            Чтение/запись **bool**. |
| [`last_col`](/slides/python-net/ru/aspose.slides/table/last_col/) | Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием.<br/>            Чтение/запись **bool**. |
| [`horizontal_banding`](/slides/python-net/ru/aspose.slides/table/horizontal_banding/) | Определяет, должны ли чётные строки отображаться с другим форматированием.<br/>            Чтение/запись **bool**. |
| [`vertical_banding`](/slides/python-net/ru/aspose.slides/table/vertical_banding/) | Определяет, должны ли чётные столбцы отображаться с другим форматированием.<br/>            Чтение/запись **bool**. |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/table/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/table/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`set_text_format(self, source)`](/slides/python-net/ru/aspose.slides/table/set_text_format/#iportionformat) | Устанавливает заданные свойства формата части для всех частей ячеек таблицы. |
| [`set_text_format(self, source)`](/slides/python-net/ru/aspose.slides/table/set_text_format/#iparagraphformat) | Устанавливает заданные свойства формата абзаца для всех абзацев ячеек таблицы. |
| [`set_text_format(self, source)`](/slides/python-net/ru/aspose.slides/table/set_text_format/#itextframeformat) | Устанавливает заданные свойства формата текстового фрейма для всех текстовых фреймов ячеек таблицы. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/table/remove_placeholder/#) | Определяет, что эта фигура не является заполнительным объектом. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/table/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/table/get_base_placeholder/#) | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или главного слайда, от которой унаследована текущая фигура).<br/>            Возвращает None, если текущая фигура не унаследована. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/table/get_visual_bounds/#) | Получает визуальные границы фигуры, рассчитанные на основе её отрисованного содержимого. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/ru/aspose.slides/table/merge_cells/#icell-icell-bool) | Объединяет соседние ячейки. |

### См. также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* класс [`Table`](/slides/python-net/ru/aspose.slides/table)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)