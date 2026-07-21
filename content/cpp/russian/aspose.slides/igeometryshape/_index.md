---
title: IGeometryShape
second_title: Справочник API Aspose.Slides для C++
description: Представляет базовый класс для всех геометрических фигур.
type: docs
weight: 2354
url: /ru/aspose.slides/igeometryshape/
---
## IGeometryShape класс

Представляет базовый класс для всех геометрических фигур.

```cpp
class IGeometryShape : public virtual Aspose::Slides::IShape
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанный. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](./createshapeelements/)() | Создаёт и возвращает массив элементов фигуры. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](./get_adjustment/)(**int32_t**) | Возвращает значение коррекции фигуры по указанному индексу. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](./get_adjustments/)() | Возвращает коллекцию значений коррекций фигуры. Только для чтения [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Возвращает альтернативный текст, связанный с фигурой. Чтение [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Возвращает заголовок альтернативного текста, связанного с фигурой. Чтение [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Свойство определяет, как фигура будет отображаться в чёрно-белом режиме. Чтение [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Возвращает количество точек подключения на фигуре. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применённые к фигуре. Только для чтения [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки для фигуры. Только для чтения [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Возвращает свойства кадра фигуры. Чтение [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Получает высоту фигуры в пунктах. Чтение **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Определяет, скрыта ли фигура. Чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Возвращает гиперссылку, определённую для щелчка мышью. Чтение [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Возвращает гиперссылку, определённую для наведения мыши. Чтение [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Получает опцию «Отметить как декоративный». Чтение/запись **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Определяет, является ли фигура TextHolder. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Возвращает имя фигуры. Чтение [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Возвращает уникальный идентификатор в пределах слайда, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду взаимодействия надёжно ссылаться на фигуру из любого места документа. Только для чтения **uint32_t**. См. также [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Возвращает объект-родитель [GroupShape](../groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Возвращает заполнитель для фигуры. Только для чтения [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Возвращает свойства необработанного кадра фигуры. Чтение [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Возвращает количество градусов, на которое указанная фигура повернута вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](./get_shapestyle/)() | Возвращает объект стиля фигуры. Только для чтения [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() | Возвращает тип предустановки геометрии. Примечание: при изменении значения все коррекционные параметры сбрасываются к значениям по умолчанию. Чтение [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства форматирования линий для фигуры. Только для чтения [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Возвращает внутренний идентификатор, привязанный к презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Получает ширину фигуры в пунктах. Чтение **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Получает координату X верхнего левого угла фигуры в пунктах. Чтение **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Получает координату Y верхнего левого угла фигуры в пунктах. Чтение **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Возвращает позицию фигуры в порядке Z. Shapes[0] возвращает фигуру в задней части порядка Z, а Shapes[Shapes.Count - 1] — фигуру в передней части порядка Z. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Возвращает базовый заполнитель (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](./getgeometrypaths/)() | Возвращает копию пути геометрической фигуры. Координаты заданы относительно левого верхнего угла фигуры. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Определяет, что эта фигура не является заполнителем. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Устанавливает альтернативный текст, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Устанавливает заголовок альтернативного текста, связанный с фигурой. Запись [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Свойство определяет, как фигура будет отображаться в чёрно-белом режиме. Запись [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Устанавливает свойства кадра фигуры. Запись [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Устанавливает высоту фигуры в пунктах. Запись **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Определяет, скрыта ли фигура. Запись **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определённую для щелчка мышью. Запись [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определённую для наведения мыши. Запись [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Устанавливает параметр «Отметить как декоративный». Чтение/запись **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Устанавливает имя фигуры. Запись [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Устанавливает свойства необработанного кадра фигуры. Запись [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Устанавливает количество градусов, на которое указанная фигура поворачивается вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| virtual void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Устанавливает тип предустановки геометрии. Примечание: при изменении значения все коррекционные параметры сбрасываются к значениям по умолчанию. Запись [Slides::ShapeType](../shapetype/). |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Устанавливает ширину фигуры в пунктах. Запись **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Устанавливает координату X верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Устанавливает координату Y верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [SetGeometryPath](./setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Обновляет геометрию фигуры из объекта [IGeometryPath](../igeometrypath/). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([ShapeType](../shapetype/)) на [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](./setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Обновляет геометрию фигуры из массива [IGeometryPath](../igeometrypath/). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([ShapeType](../shapetype/)) на [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IShape](../ishape/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)