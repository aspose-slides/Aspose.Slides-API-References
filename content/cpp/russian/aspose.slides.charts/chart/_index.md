---
title: Chart
second_title: Справочник API Aspose.Slides для C++
description: Представляет графическую диаграмму на слайде.
type: docs
weight: 53
url: /ru/aspose.slides.charts/chart/
---
## Chart класс

Represents an graphic chart on a slide.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанный. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | Возвращает фактическую тему для этой диаграммы. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Возвращает альтернативный текст, связанный с фигурой. Чтение [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Возвращает заголовок альтернативного текста, связанный с фигурой. Чтение [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | Обеспечивает доступ к осям диаграммы. Только для чтения [IAxesManager](../iaxesmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | Возвращает объект, позволяющий изменить формат задней стенки 3D-диаграммы. Только для чтения [IChartWall](../ichartwall/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Чтение [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | Возвращает информацию о связанных или встроенных данных, связанных с диаграммой. Только для чтения [IChartData](../ichartdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | Возвращает таблицу данных диаграммы. Только для чтения [IDataTable](../idatatable/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | Возвращает заголовок диаграммы. Только для чтения [IChartTitle](../icharttitle/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Возвращает количество точек подключения на фигуре. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../../aspose.slides/icustomdata/). |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | Возвращает способ отображения пустых ячеек на диаграмме. Чтение [DisplayBlanksAsType](../displayblanksastype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Возвращает объект [EffectFormat](../../aspose.slides/effectformat/), содержащий пиксельные эффекты, применяемые к фигуре. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств эффектов. Только для чтения [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Возвращает объект [FillFormat](../../aspose.slides/fillformat/), содержащий свойства заливки для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств заливки. Только для чтения [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | Возвращает объект, позволяющий изменить формат пола 3D-диаграммы. Только для чтения [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Возвращает свойства кадра фигуры. Чтение [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Возвращает блокировки фигуры. Только для чтения [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | Определяет, имеет ли диаграмма таблицу данных. Чтение **bool**. |
| **bool** [get_HasLegend](./get_haslegend/)() override | Определяет, имеет ли диаграмма легенду. Чтение **bool**. |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | Указывает, что область диаграммы должна иметь скруглённые углы. Чтение **bool**. |
| **bool** [get_HasTitle](./get_hastitle/)() override | Определяет, имеет ли диаграмма видимый заголовок. Чтение **bool**. |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Получает высоту фигуры в пунктах. Чтение **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Определяет, скрыта ли фигура. Чтение **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Возвращает гиперссылку, определённую для клика мышью. Чтение [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Возвращает менеджер гиперссылок. Только для чтения [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Возвращает гиперссылку, определённую для наведения мышью. Чтение [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Получает параметр 'Пометить как декоративный'. Чтение/запись **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Определяет, является ли фигура TextHolder_PPT. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | Возвращает легенду для диаграммы. Только для чтения [ILegend](../ilegend/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Возвращает объект [LineFormat](../../aspose.slides/lineformat/), содержащий свойства форматирования линий для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств линии. Только для чтения [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Возвращает имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Чтение [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение существования фигуры и позволяет PowerPoint или коду межоперации надёжно ссылаться на фигуру из любого места документа. Только для чтения **uint32_t**. См. также [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Возвращает родительский объект [GroupShape](../../aspose.slides/groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | Представляет область построения диаграммы. Только для чтения [IChartPlotArea](../ichartplotarea/). |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки. Чтение **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Возвращает презентацию-родитель слайда. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Возвращает необработанные свойства кадра фигуры. Чтение [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Возвращает количество градусов, на которое заданная фигура повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | Возвращает 3D-поворот диаграммы. Только для чтения [IRotation3D](../irotation3d/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | Указывает, что подписи данных над максимумом диаграммы должны отображаться. Чтение **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | Возвращает объект, позволяющий изменить формат боковой стенки 3D-диаграммы. Только для чтения [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Возвращает слайд-родитель фигуры. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | Возвращает стиль диаграммы. Чтение [StyleType](../styletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Возвращает формат текста диаграммы. Свойство не применимо к следующим типам: [ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/). Только для чтения [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Возвращает менеджер темы. Только для чтения [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Возвращает объект [ThreeDFormat](../../aspose.slides/threedformat/), содержащий свойства 3D-эффекта для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет 3D-свойств. Только для чтения [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | Возвращает тип диаграммы. Чтение [ChartType](../charttype/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | Указывает фигуры, нарисованные над диаграммой. Только для чтения [IGroupShape](../../aspose.slides/igroupshape/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Получает ширину фигуры в пунктах. Чтение **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Получает координату x верхнего левого угла фигуры в пунктах. Чтение **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Получает координату y верхнего левого угла фигуры в пунктах. Чтение **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в задней части порядка z, а Shapes[Shapes.Count - 1] — в передней. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Возвращает базовую форму-заполнитель (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры фигуры [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли объект экземпляром типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Определяет, что эта фигура не является заполнителем. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Устанавливает альтернативный текст, связанный с фигурой. Запись [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Устанавливает заголовок альтернативного текста, связанный с фигурой. Запись [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Запись [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | Устанавливает способ отображения пустых ячеек на диаграмме. Запись [DisplayBlanksAsType](../displayblanksastype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Устанавливает свойства кадра фигуры. Запись [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | Определяет, имеет ли диаграмма таблицу данных. Запись **bool**. |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | Определяет, имеет ли диаграмма легенду. Запись **bool**. |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | Указывает, что область диаграммы должна иметь скруглённые углы. Запись **bool**. |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Определяет, имеет ли диаграмма видимый заголовок. Запись **bool**. |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Устанавливает высоту фигуры в пунктах. Запись **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Определяет, скрыта ли фигура. Запись **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Устанавливает гиперссылку, определённую для клика мышью. Запись [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Устанавливает гиперссылка, определённую для наведения мышью. Запись [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Устанавливает параметр 'Пометить как декоративный'. Запись/чтение **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Устанавливает имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Запись [System::String](../../system/string/). |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки. Запись **bool**. |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Устанавливает необработанные свойства кадра фигуры. Запись [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Устанавливает количество градусов, на которое заданная фигура повернута вокруг оси z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | Указывает, что подписи данных над максимумом диаграммы должны отображаться. Запись **bool**. |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | Устанавливает стиль диаграммы. Запись [StyleType](../styletype/). |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | Устанавливает тип диаграммы. Запись [ChartType](../charttype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Устанавливает ширину фигуры в пунктах. Запись **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Устанавливает координату x верхнего левого угла фигуры в пунктах. Запись **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Устанавливает координату y верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как weak-указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| void [ValidateChartLayout](./validatechartlayout/)() override | Вычисляет реальные значения элементов диаграммы. Реальные значения включают позицию элементов, реализующих интерфейс [IActualLayout](../iactuallayout/) ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) и реальные значения осей ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик weak-ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик weak-ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Сохраняет содержимое [Shape](../../aspose.slides/shape/) в файл SVG. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Сохраняет содержимое [Shape](../../aspose.slides/shape/) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [GraphicalObject](../../aspose.slides/graphicalobject/)
* Класс [IChart](../ichart/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)