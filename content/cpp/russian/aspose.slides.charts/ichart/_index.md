---
title: IChart
second_title: Справочник API Aspose.Slides для C++
description: Представляет графическую диаграмму на слайде.
type: docs
weight: 573
url: /ru/aspose.slides.charts/ichart/
---
## IChart класс

Представляет графическую диаграмму на слайде.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанный. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Возвращает эффективную тему для этого объекта, поддерживающего темы. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Возвращает альтернативный текст, связанный с фигурой. См. [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Возвращает заголовок альтернативного текста, связанного с фигурой. См. [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | Обеспечивает доступ к осям диаграммы. Только для чтения [IAxesManager](../iaxesmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | Возвращает объект, позволяющий изменять формат задней стены 3D-диаграммы. Только для чтения [IChartWall](../ichartwall/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Свойство указывает, как фигура будет отображаться в режиме черно-белого отображения. См. [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | Возвращает диаграмму. Только для чтения [IChart](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | Возвращает информацию о связанных или внедренных данных, связанных с диаграммой. Только для чтения [IChartData](../ichartdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | Возвращает таблицу данных диаграммы. Только для чтения [IDataTable](../idatatable/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | Возвращает заголовок диаграммы. Только для чтения [IChartTitle](../icharttitle/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Возвращает количество точек соединения на фигуре. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | Возвращает способ отображения пустых ячеек на диаграмме. См. [DisplayBlanksAsType](../displayblanksastype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Возвращает объект [EffectFormat](../../aspose.slides/effectformat/), содержащий пиксельные эффекты, применяемые к фигуре. Только для чтения [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Возвращает объект [FillFormat](../../aspose.slides/fillformat/), содержащий свойства заполнения для фигуры. Только для чтения [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | Возвращает объект, позволяющий изменять формат пола 3D-диаграммы. Только для чтения [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Возвращает свойства рамки фигуры. См. [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Возвращает блокировки фигуры. Только для чтения [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | Определяет, содержит ли диаграмма таблицу данных. Только для чтения **bool**. |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | Определяет, содержит ли диаграмма легенду. Только для чтения **bool**. |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | Указывает, что область диаграммы должна иметь скругленные углы. Только для чтения **bool**. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Определяет, имеет ли диаграмма видимый заголовок. Только для чтения **bool**. |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Получает высоту фигуры в пунктах. Только для чтения **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Определяет, скрыта ли фигура. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Возвращает гиперссылку, определенную для щелчка мышью. См. [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Менеджер гиперссылок. Только для чтения [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Возвращает гиперссылку, определенную для наведения мышью. См. [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | Получает параметр «Отметить как декоративный». Чтение/запись **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Определяет, является ли фигура TextHolder. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | Возвращает легенду для диаграммы. Только для чтения [ILegend](../ilegend/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Возвращает объект [LineFormat](../../aspose.slides/lineformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Возвращает имя фигуры. См. [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Возвращает уникальный идентификатор в пределах слайда, остающийся постоянным на протяжении жизни фигуры и позволяющий PowerPoint или коду взаимодействия надёжно ссылаться на фигуру из любой части документа. Только для чтения **uint32_t**. Смотрите также [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Возвращает родительский объект [GroupShape](../../aspose.slides/groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Возвращает заполнитель для фигуры. Только для чтения [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | Представляет область построения диаграммы. Только для чтения [IChartPlotArea](../ichartplotarea/). |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Возвращает свойства сырой рамки фигуры. См. [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Возвращает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Только для чтения **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | Возвращает 3D-вращение диаграммы. Только для чтения [IRotation3D](../irotation3d/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | Указывает, что подписи данных, превышающие максимум диаграммы, должны отображаться. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | Возвращает объект, позволяющий изменять формат боковой стены 3D-диаграммы. Только для чтения [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | Возвращает стиль диаграммы. См. [StyleType](../styletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Возвращает формат текста диаграммы. Только для чтения [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | Возвращает менеджер переопределения темы. Только для чтения [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Возвращает объект [ThreeDFormat](../../aspose.slides/threedformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | Возвращает тип диаграммы. См. [ChartType](../charttype/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. Смотрите также [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | Указывает фигуры, рисуемые поверх диаграммы. Только для чтения [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Получает ширину фигуры в пунктах. Только для чтения **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Получает координату X верхнего левого угла фигуры в пунктах. Только для чтения **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Получает координату Y верхнего левого угла фигуры в пунктах. Только для чтения **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Возвращает положение фигуры в порядке Z. Shapes[0] возвращает фигуру в задней части порядка Z, а Shapes[Shapes.Count - 1] — переднюю. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Возвращает базовую форму заполнителя (фигуру из шаблона и/или главного слайда, от которой наследуется текущая фигура). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператором C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает количество общих ссылок на указанное значение. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Определяет, что эта фигура не является заполнителем. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Устанавливает альтернативный текст, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Устанавливает заголовок альтернативного текста, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Свойство указывает, как фигура будет отображаться в режиме черно-белого отображения. Запись [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | Устанавливает способ отображения пустых ячеек на диаграмме. Запись [DisplayBlanksAsType](../displayblanksastype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Устанавливает свойства рамки фигуры. Запись [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | Определяет, содержит ли диаграмма таблицу данных. Запись **bool**. |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | Определяет, содержит ли диаграмма легенду. Запись **bool**. |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | Указывает, что область диаграммы должна иметь скругленные углы. Запись **bool**. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Определяет, имеет ли диаграмма видимый заголовок. Запись **bool**. |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Устанавливает высоту фигуры в пунктах. Запись **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Определяет, скрыта ли фигура. Запись **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Устанавливает гиперссылку, определенную для щелчка мышью. Запись [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Устанавливает гиперссылку, определенную для наведения мышью. Запись [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | Устанавливает параметр «Отметить как декоративный». Чтение/запись **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Устанавливает имя фигуры. Запись [System::String](../../system/string/). |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки. Запись **bool**. |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Устанавливает свойства сырой рамки фигуры. Запись [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Устанавливает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | Указывает, что подписи данных, превышающие максимум диаграммы, должны отображаться. Запись **bool**. |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | Устанавливает стиль диаграммы. Запись [StyleType](../styletype/). |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | Устанавливает тип диаграммы. Запись [ChartType](../charttype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Устанавливает ширину фигуры в пунктах. Запись **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Устанавливает координату X верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Устанавливает координату Y верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператором C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | Вычисляет фактические значения элементов диаграммы. Фактические значения включают положение элементов, реализующих интерфейс [IActualLayout](../iactuallayout/) ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) и реальные значения осей ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте смарт-указатели или ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Сохраняет содержимое [Shape](../../aspose.slides/shape/) в файл SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Сохраняет содержимое [Shape](../../aspose.slides/shape/) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Класс [IFormattedTextContainer](../iformattedtextcontainer/)
* Класс [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)