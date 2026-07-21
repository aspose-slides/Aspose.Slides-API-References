---
title: IConnector
second_title: Aspose.Slides для C++ справочника API
description: Представляет соединитель.
type: docs
weight: 1847
url: /ru/aspose.slides/iconnector/
---
## IConnector класс

Представляет соединитель.

```cpp
class IConnector : public virtual Aspose::Slides::IGeometryShape
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанный. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Создаёт и возвращает массив элементов фигуры. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типажа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Возвращает значение коррекции фигуры по указанному индексу. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Возвращает коллекцию значений коррекций фигуры. Только чтение [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Возвращает альтернативный текст, связанный с фигурой. Чтение [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Возвращает заголовок альтернативного текста, связанного с фигурой. Чтение [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Чтение [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Возвращает количество точек подключения на фигуре. Только чтение **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() | Возвращает блокировки [Connector](../connector/). Только чтение [IConnectorLock](../iconnectorlock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Возвращает пользовательские данные фигуры. Только чтение [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применённые к фигуре. Только чтение [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() | Возвращает фигуру, к которой следует присоединить конец соединителя. Чтение [IShape](../ishape/). |
| virtual **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() | Возвращает индекс точки подключения для конечной фигуры. Чтение **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки фигуры. Только чтение [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Возвращает свойства кадра фигуры. Чтение [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Получает высоту фигуры в пунктах. Чтение **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Определяет, скрыта ли фигура. Чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Возвращает гиперссылку, определённую для щелчка мышью. Чтение [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Менеджер гиперссылок. Только чтение [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Возвращает гиперссылку, определённую при наведении мыши. Чтение [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Получает параметр «Mark as decorative». Чтение/запись **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Определяет, сгруппирована ли фигура. Только чтение **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Определяет, является ли фигура TextHolder. Только чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий фигуры. Только чтение [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Возвращает имя фигуры. Чтение [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Возвращает уникальный идентификатор уровня слайда, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду межоперационной связи надёжно ссылаться на фигуру из любого места документа. Только чтение **uint32_t**. См. также [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Возвращает родительский объект [GroupShape](../groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только чтение [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Возвращает заполнитель для фигуры. Только чтение [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только чтение [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Возвращает свойства сырого кадра фигуры. Чтение [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Возвращает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Возвращает блокировки фигуры. Только чтение [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Возвращает объект стиля фигуры. Только чтение [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Возвращает тип предустановки геометрии. Примечание: при изменении значения все параметры коррекции сбрасываются к значениям по умолчанию. Чтение [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Возвращает базовый слайд. Только чтение [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() | Возвращает фигуру, к которой следует присоединить начало соединителя. Чтение [IShape](../ishape/). |
| virtual **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() | Возвращает индекс точки подключения для начальной фигуры. Чтение **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства форматирования линий для фигуры. Только чтение [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Возвращает внутренний идентификатор уровня презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переназначено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только чтение **uint32_t**. См. также [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Получает ширину фигуры в пунктах. Чтение **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Получает координату x верхнего левого угла фигуры в пунктах. Чтение **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Получает координату y верхнего левого угла фигуры в пунктах. Чтение **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в задней части порядка z, а Shapes[Shapes.Count - 1] — фигуру в передней части. Только чтение **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Возвращает базовую форму-заполнитель (фигуру из макета и/или слайда-шаблона, от которой наследуется текущая фигура). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанного с объектом. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Возвращает копию пути геометрической фигуры. Координаты относительно левого верхнего угла фигуры. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Возвращает миниатюру фигуры. Тип границ миниатюры [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) используется по умолчанию. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типажа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Определяет, что эта фигура не является заполнителем. |
| virtual void [Reroute](./reroute/)() | Перенаправляет соединитель, чтобы он прокладывал кратчайший путь между соединяемыми фигурами. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Устанавливает альтернативный текст, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Устанавливает заголовок альтернативного текста, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Запись [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | Устанавливает фигуру, к которой следует присоединить конец соединителя. Запись [IShape](../ishape/). |
| virtual void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) | Устанавливает индекс точки подключения для конечной фигуры. Запись **uint32_t**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Устанавливает свойства кадра фигуры. Запись [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Устанавливает высоту фигуры в пунктах. Запись **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Определяет, скрыта ли фигура. Запись **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определённую для щелчка мышью. Запись [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определённую при наведении мыши. Запись [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Устанавливает параметр «Mark as decorative». Запись/чтение **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Устанавливает имя фигуры. Запись [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Устанавливает свойства сырого кадра фигуры. Запись [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Устанавливает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Устанавливает тип предустановки геометрии. Примечание: при изменении значения все параметры коррекции сбрасываются к значениям по умолчанию. Запись [Slides::ShapeType](../shapetype/). |
| virtual void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | Устанавливает фигуру, к которой следует присоединить начало соединителя. Запись [IShape](../ishape/). |
| virtual void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) | Устанавливает индекс точки подключения для начальной фигуры. Запись **uint32_t**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Устанавливает ширину фигуры в пунктах. Запись **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Устанавливает координату x верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Устанавливает координату y верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Обновляет геометрию фигуры из объекта [IGeometryPath](../igeometrypath/). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([ShapeType](../shapetype/)) на [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Обновляет геометрию фигуры из массива [IGeometryPath](../igeometrypath/). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([ShapeType](../shapetype/)) на [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Сохраняет содержимое [Shape](../shape/) как файл SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Сохраняет содержимое [Shape](../shape/) как файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IGeometryShape](../igeometryshape/)
* Пространство имен [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)