---
title: ITable
second_title: Aspose.Slides для C++ справочник API
description: Представляет таблицу на слайде.
type: docs
weight: 4018
url: /ru/aspose.slides/itable/
---
## ITable класс

Represents a table on a slide.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанному. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Возвращает альтернативный текст, связанный с фигурой. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Возвращает заголовок альтернативного текста, связанный с фигурой. Читать [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Свойство указывает, как фигура будет отображаться в режиме черно-белого отображения. Читать [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | Возвращает столбец по указанному индексу. Только для чтения [Aspose::Slides::IColumn](../icolumn/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | Возвращает коллекцию столбцов. Только для чтения [IColumnCollection](../icolumncollection/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Возвращает количество точек соединения на фигуре. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применённые к фигуре. Только для чтения [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки для фигуры. Только для чтения [IFillFormat](../ifillformat/). |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | Определяет, должен ли первый столбец таблицы быть отрисован со специальным форматированием. Читать **bool**. |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | Определяет, должна ли первая строка таблицы быть отрисована со специальным форматированием. Читать **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Возвращает свойства кадра фигуры. Читать [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Возвращает блокировки фигуры. Только для чтения [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Получает высоту фигуры, измеренную в пунктах. Читать **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Определяет, скрыта ли фигура. Читать **bool**. |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | Определяет, должны ли чётные строки быть отрисованы с различным форматированием. Читать **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Возвращает гиперссылку, определённую для клика мышью. Читать [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Возвращает гиперссылку, определённую для наведения мыши. Читать [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Получает параметр 'Отметить как декоративный'. Чтение/запись **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Определяет, является ли фигура TextHolder. Только для чтения **bool**. |
| virtual **bool** [get_LastCol](./get_lastcol/)() | Определяет, должен ли последний столбец таблицы быть отрисован со специальным форматированием. Читать **bool**. |
| virtual **bool** [get_LastRow](./get_lastrow/)() | Определяет, должна ли последняя строка таблицы быть отрисована со специальным форматированием. Читать **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Возвращает имя фигуры. Читать [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Возвращает уникальный идентификатор в пределах слайда, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду межоперации надёжно ссылаться на фигуру из любого места документа. Только для чтения **uint32_t**. См. также [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Возвращает родительский объект [GroupShape](../groupshape/), если фигура сгруппирована. Иначе возвращает null. Только для чтения [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Возвращает заполнитель для фигуры. Только для чтения [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Возвращает свойства необработанного кадра фигуры. Читать [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Определяет, имеет ли таблица порядок чтения справа налево. Читать **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Возвращает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Читать **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | Возвращает строку по указанному индексу. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | Возвращает коллекцию строк. Только для чтения [IRowCollection](../irowcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../ibaseslide/). |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | Получает или задает встроенный стиль таблицы. Читать [TableStylePreset](../tablestylepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | Возвращает объект [TableFormat](../tableformat/), содержащий свойства форматирования для этой таблицы. Только для чтения [ITableFormat](../itableformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | Определяет, должны ли чётные столбцы быть отрисованы с различным форматированием. Читать **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Получает ширину фигуры, измеренную в пунктах. Читать **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Получает координату X левой верхней точки фигуры, измеренную в пунктах. Читать **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Получает координату Y левой верхней точки фигуры, измеренную в пунктах. Читать **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в задней части порядка z, а Shapes[Shapes.Count - 1] — в передней части. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Возвращает базовую форму-заполнитель (форму из шаблона и/или мастер-слайда, от которой унаследована текущая форма). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Возвращает эскиз фигуры. По умолчанию используется тип границ эскиза [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Возвращает эскиз фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Возвращает ячейку по указанным индексам столбца и строки. Только для чтения [ICell](../icell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | Объединяет соседние ячейки. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значений со ссылкой на nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Определяет, что эта фигура не является заполнителем. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Задаёт альтернативный текст, связанный с фигурой. Записать [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Задаёт заголовок альтернативного текста, связанный с фигурой. Записать [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Свойство указывает, как фигура будет отображаться в режиме черно-белого отображения. Записать [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | Определяет, должен ли первый столбец таблицы быть отрисован со специальным форматированием. Записать **bool**. |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | Определяет, должна ли первая строка таблицы быть отрисована со специальным форматированием. Записать **bool**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Задаёт свойства кадра фигуры. Записать [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Задаёт высоту фигуры, измеренную в пунктах. Записать **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Определяет, скрыта ли фигура. Записать **bool**. |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | Определяет, должны ли чётные строки быть отрисованы с различным форматированием. Записать **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Задаёт гиперссылку, определённую для клика мышью. Записать [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Задаёт гиперссылка, определённую для наведения мышью. Записать [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Задаёт параметр 'Отметить как декоративный'. Чтение/запись **bool**. |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | Определяет, должен ли последний столбец таблицы быть отрисован со специальным форматированием. Записать **bool**. |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | Определяет, должна ли последняя строка таблицы быть отрисована со специальным форматированием. Записать **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Задаёт имя фигуры. Записать [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Задаёт свойства необработанного кадра фигуры. Записать [IShapeFrame](../ishapeframe/). |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | Определяет, имеет ли таблица порядок чтения справа налево. Записывает **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Задаёт количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Записать **float**. |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | Получает или задает встроенный стиль таблицы. Записать [TableStylePreset](../tablestylepreset/). |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | Определяет, должны ли чётные столбцы быть отрисованы с различным форматированием. Записать **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Задаёт ширину фигуры, измеренную в пунктах. Записать **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Задает координату X левой верхней точки фигуры, измеренную в пунктах. Записать **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Задает координату Y левой верхней точки фигуры, измеренную в пунктах. Записать **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Задаёт n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | Задает определённые свойства формата части всем частям элемента. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | Задает определённые свойства формата абзаца всем абзацам элемента. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | Задает определённые свойства формата текстового кадра всем текстовым кадрам элемента. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IGraphicalObject](../igraphicalobject/)
* Класс [IBulkTextFormattable](../ibulktextformattable/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)