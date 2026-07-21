---
title: ISmartArt
second_title: Aspose.Slides для C++ справка API
description: Представляет диаграмму SmartArt.
type: docs
weight: 1
url: /ru/aspose.slides.smartart/ismartart/
---
## ISmartArt класс

Представляет [SmartArt](../smartart/) диаграмму.

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанные. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | Возвращает коллекцию всех узлов в объекте [SmartArt](../smartart/). Только для чтения [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Возвращает альтернативный текст, связанный с фигурой. Чтение [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Возвращает заголовок альтернативного текста, связанного с фигурой. Чтение [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Чтение [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | Возвращает или задает стиль цвета объекта [SmartArt](../smartart/). Чтение [SmartArtColorType](../smartartcolortype/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Возвращает количество узлов соединения на фигуре. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Возвращает объект [EffectFormat](../../aspose.slides/effectformat/), содержащий пиксельные эффекты, применённые к фигуре. Только для чтения [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Возвращает объект [FillFormat](../../aspose.slides/fillformat/), содержащий свойства заливки для фигуры. Только для чтения [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Возвращает свойства рамки фигуры. Чтение [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Возвращает блокировки фигуры. Только для чтения [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Получает высоту фигуры в пунктах. Чтение **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Определяет, скрыта ли фигура. Чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Возвращает гиперссылку, определённую для щелчка мышью. Чтение [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Менеджер гиперссылок. Только для чтения [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Возвращает гиперссылку, определённую для наведения мышью. Чтение [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | Получает параметр 'Отметить как декоративный'. Чтение/запись **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | Возвращает или задаёт состояние диаграммы [SmartArt](../smartart/) относительно (слева направо) LTR или (справа налево) RTL, если диаграмма поддерживает обратный порядок. Чтение **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Определяет, является ли фигура TextHolder. Только для чтения **bool**. |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | Возвращает или задаёт макет объекта [SmartArt](../smartart/). Чтение [SmartArtLayoutType](../smartartlayouttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Возвращает объект [LineFormat](../../aspose.slides/lineformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Возвращает имя фигуры. Чтение [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | Возвращает узел из коллекции корневых узлов в объекте [SmartArt](../smartart/) по указанному индексу. Только для чтения [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | Возвращает узел из коллекции всех узлов в объекте [SmartArt](../smartart/) по указанному индексу. Только для чтения [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | Возвращает коллекцию корневых узлов в объекте [SmartArt](../smartart/). Только для чтения [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Возвращает уникальный идентификатор, ограниченный слайдом, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду взаимодействия надёжно ссылаться на фигуру из любой части документа. Только для чтения **uint32_t**. См. также [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Возвращает родительский объект [GroupShape](../../aspose.slides/groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Возвращает заполнитель для фигуры. Только для чтения [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | Возвращает или задаёт быстрый стиль объекта [SmartArt](../smartart/). Чтение [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Возвращает свойства необработанной рамки фигуры. Чтение [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Возвращает количество градусов, на которое заданная фигура вращена вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Возвращает объект [ThreeDFormat](../../aspose.slides/threedformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Возвращает внутренний идентификатор, ограниченный презентацией, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Получает ширину фигуры в пунктах. Чтение **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Получает координату x левого верхнего угла фигуры в пунктах. Чтение **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Получает координату y левого верхнего угла фигуры в пунктах. Чтение **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в задней части порядка z, а Shapes[Shapes.Count - 1] — фигуру в передней части. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или главного слайда, от которой унаследована текущая фигура). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнение ссылки типового значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Определяет, что эта фигура не является заполнителем. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Устанавливает альтернативный текст, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Устанавливает заголовок альтернативного текста, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Запись [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | Возвращает или задаёт стиль цвета объекта [SmartArt](../smartart/). Запись [SmartArtColorType](../smartartcolortype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Устанавливает свойства рамки фигуры. Запись [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Устанавливает высоту фигуры в пунктах. Запись **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Определяет, скрыта ли фигура. Запись **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Устанавливает гиперссылку, определённую для щелчка мышью. Запись [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Устанавливает гиперссылку, определённую для наведения мышью. Запись [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | Устанавливает параметр 'Отметить как декоративный'. Запись/чтение **bool**. |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | Возвращает или задаёт состояние диаграммы [SmartArt](../smartart/) относительно (слева направо) LTR или (справа налево) RTL, если диаграмма поддерживает реверс. Запись **bool**. |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | Возвращает или задаёт макет объекта [SmartArt](../smartart/). Запись [SmartArtLayoutType](../smartartlayouttype/). |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Устанавливает имя фигуры. Запись [System::String](../../system/string/). |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | Возвращает или задаёт быстрый стиль объекта [SmartArt](../smartart/). Запись [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Устанавливает свойства необработанной рамки фигуры. Запись [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Устанавливает количество градусов, на которое заданная фигура вращена вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Устанавливает ширину фигуры в пунктах. Запись **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Устанавливает координату x левого верхнего угла фигуры в пунктах. Запись **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Устанавливает координату y левого верхнего угла фигуры в пунктах. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Задает n-ый шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Сохраняет содержимое [Shape](../../aspose.slides/shape/) в файл SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Сохраняет содержимое [Shape](../../aspose.slides/shape/) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Пространство имён [Aspose::Slides::SmartArt](../)
* Библиотека [Aspose.Slides](../../)