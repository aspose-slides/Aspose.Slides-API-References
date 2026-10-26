---
title: Chart class
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.charts/chart/
---
## Chart класс

Represents an graphic chart on a slide.

**Inheritance:**[`Chart`](/slides/python-net/ru/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

The Chart type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides.charts/chart/is_text_holder/) | Определяет, является ли фигура TextHolder_PPT.<br/>            Только чтение **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides.charts/chart/placeholder/) | Возвращает заполнитель для фигуры. Возвращает None, если у фигуры нет заполнителя.<br/>            Только чтение [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides.charts/chart/custom_data/) | Возвращает пользовательские данные фигуры.<br/>            Только чтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides.charts/chart/raw_frame/) | Получает или задает свойства необработанной рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides.charts/chart/frame/) | Получает или задает свойства рамки фигуры.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides.charts/chart/line_format/) | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств линии.<br/>            Только чтение [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides.charts/chart/three_d_format/) | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффекта для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет 3D-свойств.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides.charts/chart/effect_format/) | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применяемые к фигуре.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств эффекта.<br/>            Только чтение [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides.charts/chart/fill_format/) | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры.<br/>            Примечание: может возвращать None для некоторых типов фигур, у которых нет свойств заливки.<br/>            Только чтение [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides.charts/chart/hyperlink_click/) | Получает или задает гиперссылку, определённую для щелчка мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides.charts/chart/hyperlink_mouse_over/) | Получает или задает гиперссылку, определённую для наведения мышью.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides.charts/chart/hyperlink_manager/) | Возвращает менеджер гиперссылок.<br/>            Только чтение [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides.charts/chart/hidden/) | Определяет, скрыта ли фигура.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides.charts/chart/z_order_position/) | Возвращает позицию фигуры в порядке z.<br/>            Shapes[0] возвращает фигуру в задней части порядка z,<br/>            а Shapes[Shapes.Count - 1] возвращает фигуру в передней части порядка z.<br/>            Только чтение **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides.charts/chart/connection_site_count/) | Возвращает количество точек подключения на фигуре.<br/>            Только чтение **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides.charts/chart/rotation/) | Получает или задает количество градусов, на которое указанная фигура вращается вокруг оси z.<br/>            Положительное значение обозначает вращение по часовой стрелке; отрицательное — против часовой стрелки.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides.charts/chart/x/) | Получает или задает координату x левого верхнего угла фигуры, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides.charts/chart/y/) | Получает или задает координату y левого верхнего угла фигуры, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides.charts/chart/width/) | Получает или задает ширину фигуры, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides.charts/chart/height/) | Получает или задает высоту фигуры, измеряется в пунктах.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides.charts/chart/black_white_mode/) | Свойство определяет, как фигура будет отображаться в черно-белом режиме.<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides.charts/chart/unique_id/) | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования надстройками или другим кодом.<br/>            Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать<br/>            как постоянный уникальный ключ.<br/>            Только чтение **int**.<br/>            См. также [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides.charts/chart/office_interop_shape_id/) | Возвращает уникальный идентификатор, привязанный к слайду, который остаётся постоянным на протяжении жизни фигуры и<br/>            позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа.<br/>            Только чтение **int**.<br/>            См. также [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides.charts/chart/alternative_text/) | Получает или задает альтернативный текст, связанный с фигурой.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides.charts/chart/alternative_text_title/) | Получает или задает заголовок альтернативного текста, связанного с фигурой.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides.charts/chart/name/) | Получает или задает имя фигуры.<br/>            Должно быть не None. При необходимости используйте пустую строку.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides.charts/chart/is_decorative/) | Получает или задает параметр 'Отметить как декоративный'<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides.charts/chart/shape_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides.charts/chart/is_grouped/) | Определяет, объединена ли фигура в группу.<br/>            Только чтение **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides.charts/chart/parent_group/) | Возвращает объект родительской группы GroupShape, если фигура объединена в группу. Иначе возвращает None.<br/>            Только чтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides.charts/chart/slide/) | Возвращает родительский слайд фигуры.<br/>            Только чтение [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides.charts/chart/presentation/) | Возвращает родительскую презентацию слайда.<br/>            Только чтение [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides.charts/chart/graphical_object_lock/) | Возвращает блокировки фигуры.<br/>            Только чтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/ru/aspose.slides.charts/chart/plot_visible_cells_only/) | Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки.<br/>            Чтение/запись **bool**. |
| [`display_blanks_as`](/slides/python-net/ru/aspose.slides.charts/chart/display_blanks_as/) | Получает или задает способ отображения пустых ячеек на диаграмме.<br/>            Чтение/запись [`DisplayBlanksAsType`](/slides/python-net/ru/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/ru/aspose.slides.charts/chart/chart_data/) | Возвращает информацию о связанных или вложенных данных, связанных с диаграммой.<br/>            Только чтение [`IChartData`](/slides/python-net/ru/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/ru/aspose.slides.charts/chart/has_title/) | Определяет, имеет ли диаграмма видимый заголовок.<br/>            Чтение/запись **bool**. |
| [`chart_title`](/slides/python-net/ru/aspose.slides.charts/chart/chart_title/) | Получает или задает заголовок диаграммы.<br/>            Только чтение [`IChartTitle`](/slides/python-net/ru/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/ru/aspose.slides.charts/chart/has_data_table/) | Определяет, имеет ли диаграмма таблицу данных.<br/>            Чтение/запись **bool**. |
| [`has_legend`](/slides/python-net/ru/aspose.slides.charts/chart/has_legend/) | Определяет, имеет ли диаграмма легенду.<br/>            Чтение/запись **bool**. |
| [`legend`](/slides/python-net/ru/aspose.slides.charts/chart/legend/) | Получает или задает легенду для диаграммы.<br/>            Только чтение [`ILegend`](/slides/python-net/ru/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/ru/aspose.slides.charts/chart/chart_data_table/) | Возвращает таблицу данных диаграммы.<br/>            Только чтение [`IDataTable`](/slides/python-net/ru/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/ru/aspose.slides.charts/chart/style/) | Получает или задает стиль диаграммы.<br/>            Чтение/запись [`StyleType`](/slides/python-net/ru/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/ru/aspose.slides.charts/chart/type/) | Получает или задает тип диаграммы.<br/>            Чтение/запись [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/ru/aspose.slides.charts/chart/plot_area/) | Представляет область построения диаграммы.<br/>            Только чтение [`IChartPlotArea`](/slides/python-net/ru/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/ru/aspose.slides.charts/chart/rotation_3d/) | Возвращает 3D-вращение диаграммы.<br/>            Только чтение [`IRotation3D`](/slides/python-net/ru/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/ru/aspose.slides.charts/chart/back_wall/) | Возвращает объект, позволяющий изменить формат задней стенки 3D-диаграммы.<br/>            Только чтение [`IChartWall`](/slides/python-net/ru/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/ru/aspose.slides.charts/chart/side_wall/) | Возвращает объект, позволяющий изменить формат боковой стенки 3D-диаграммы.<br/>            Только чтение [`IChartWall`](/slides/python-net/ru/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/ru/aspose.slides.charts/chart/floor/) | Возвращает объект, позволяющий изменить формат пола 3D-диаграммы.<br/>            Только чтение [`IChartWall`](/slides/python-net/ru/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/ru/aspose.slides.charts/chart/text_format/) | Возвращает формат текста диаграммы.<br/>            Свойство не применимо к следующим типам: [`ChartType.TREEMAP`](/slides/python-net/ru/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/ru/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/ru/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/ru/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/ru/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/ru/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Только чтение [`IChartTextFormat`](/slides/python-net/ru/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/ru/aspose.slides.charts/chart/theme_manager/) | Возвращает менеджер темы.<br/>            Только чтение [`IOverrideThemeManager`](/slides/python-net/ru/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/ru/aspose.slides.charts/chart/user_shapes/) | Указывает фигуры, отрисованные поверх диаграммы.<br/>            Только чтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/ru/aspose.slides.charts/chart/axes/) | Обеспечивает доступ к осям диаграммы.<br/>            Только чтение [`IAxesManager`](/slides/python-net/ru/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/ru/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Указывает, должны ли отображаться подписи данных выше максимального значения диаграммы.<br/>            Чтение/запись **bool**. |
| [`has_rounded_corners`](/slides/python-net/ru/aspose.slides.charts/chart/has_rounded_corners/) | Указывает, должна ли область диаграммы иметь скруглённые углы.<br/>            Чтение/запись **bool**. |
| [`chart`](/slides/python-net/ru/aspose.slides.charts/chart/chart/) |  |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides.charts/chart/get_image/#) | Возвращает миниатюру фигуры.<br/>            По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Возвращает миниатюру фигуры. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Сохраняет содержимое фигуры в файл SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Сохраняет содержимое фигуры в файл SVG. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides.charts/chart/remove_placeholder/#) | Определяет, что эта фигура не является заполнителем. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides.charts/chart/get_base_placeholder/#) | Возвращает базовую фигуру-заполнитель (фигуру из разметки и/или мастер-слайда, от которой наследуется текущая фигура).<br/>            Возвращает None, если текущая фигура не наследуется. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides.charts/chart/get_visual_bounds/#) | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| [`validate_chart_layout(self)`](/slides/python-net/ru/aspose.slides.charts/chart/validate_chart_layout/#) | Вычисляет фактические значения элементов диаграммы. Фактические значения включают позицию элементов, реализующих интерфейс IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            и фактические значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/ru/aspose.slides.charts/chart/create_theme_effective/#) | Возвращает эффективную тему для этой диаграммы. |

### См. также
* класс [`Chart`](/slides/python-net/ru/aspose.slides.charts/chart)
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)