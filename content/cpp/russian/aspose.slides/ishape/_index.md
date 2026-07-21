---
title: IShape
second_title: Справка по API Aspose.Slides для C++
description: Представляет форму на слайде.
type: docs
weight: 3641
url: /ru/aspose.slides/ishape/
---
## IShape класс

Represents a shape on a slide.

```cpp
class IShape : public virtual Aspose::Slides::ISlideComponent,
               public Aspose::Slides::IHyperlinkContainer
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя указанным. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() | Возвращает альтернативный текст, связанный с формой. См. [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() | Возвращает заголовок альтернативного текста, связанный с формой. См. [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() | Свойство определяет, как форма будет отображаться в черно-белом режиме.. См. [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() | Возвращает количество точек подключения на форме. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | Возвращает пользовательские данные формы. Только для чтения [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применённые к форме. Только для чтения [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки формы. Только для чтения [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() | Возвращает свойства кадра формы. См. [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](./get_height/)() | Получает высоту формы, измеренную в пунктах. Только для чтения **float**. |
| virtual **bool** [get_Hidden](./get_hidden/)() | Определяет, скрыта ли форма. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Возвращает гиперссылку, определенную для щелчка мышью. См. [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Возвращает гиперссылку, определенную для наведения мыши. См. [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](./get_isdecorative/)() | Получает параметр 'Mark as decorative'. Чтение/запись **bool**. |
| virtual **bool** [get_IsGrouped](./get_isgrouped/)() | Определяет, сгруппирована ли форма. Только для чтения **bool**. |
| virtual **bool** [get_IsTextHolder](./get_istextholder/)() | Определяет, является ли форма TextHolder. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий формы. Только для чтения [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | Возвращает имя формы. См. [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() | Возвращает уникальный идентификатор в пределах слайда, который остаётся постоянным в течение жизни формы и позволяет PowerPoint или коду взаимодействия надёжно ссылаться на форму из любой части документа. Только для чтения **uint32_t**. См. также [IShape::get_UniqueId](./get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() | Возвращает родительский объект [GroupShape](../groupshape/), если форма сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() | Возвращает заполнитель для формы. Только для чтения [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() | Возвращает свойства необработанного кадра формы. См. [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](./get_rotation/)() | Возвращает количество градусов, на которое заданная форма вращается вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Только для чтения **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() | Возвращает блокировки формы. Только для чтения [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства форматирования линий формы. Только для чтения [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](./get_uniqueid/)() | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [IShape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| virtual **float** [get_Width](./get_width/)() | Получает ширину формы в пунктах. Только для чтения **float**. |
| virtual **float** [get_X](./get_x/)() | Получает координату x верхнего левого угла формы в пунктах. Только для чтения **float**. |
| virtual **float** [get_Y](./get_y/)() | Получает координату y верхнего левого угла формы в пунктах. Только для чтения **float**. |
| virtual **int32_t** [get_ZOrderPosition](./get_zorderposition/)() | Возвращает позицию формы в порядке Z. Shapes[0] возвращает форму, находящуюся в задней части порядка Z, а Shapes[Shapes.Count - 1] — форму, находящуюся спереди. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](./)\> [GetBasePlaceholder](./getbaseplaceholder/)() | Возвращает базовый объект placeholder (форму из макета и/или слайда-шаблона, от которой унаследована текущая форма). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | Возвращает миниатюру формы. По умолчанию используется тип [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) границ миниатюры формы. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Возвращает миниатюру формы. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со ссылкой на nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| virtual void [RemovePlaceholder](./removeplaceholder/)() | Определяет, что данная форма не является placeholder. |
| virtual void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) | Устанавливает альтернативный текст, связанный с формой. Записать [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) | Устанавливает заголовок альтернативного текста, связанный с формой. Записать [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Свойство определяет, как форма будет отображаться в черно-белом режиме.. Записать [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Устанавливает свойства кадра формы. Записать [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](./set_height/)(**float**) | Устанавливает высоту формы, измеренную в пунктах. Записать **float**. |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | Устанавливает, скрыта ли форма. Записать **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определенную для щелчка мышью. Записать [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определенную для наведения мыши. Записать [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](./set_isdecorative/)(**bool**) | Устанавливает параметр 'Mark as decorative'. Чтение/запись **bool**. |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | Устанавливает имя формы. Записать [System::String](../../system/string/). |
| virtual void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Устанавливает свойства необработанного кадра формы. Записать [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](./set_rotation/)(**float**) | Устанавливает количество градусов, на которое заданная форма вращается вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Записать **float**. |
| virtual void [set_Width](./set_width/)(**float**) | Устанавливает ширину формы в пунктах. Записать **float**. |
| virtual void [set_X](./set_x/)(**float**) | Устанавливает координату x верхнего левого угла формы в пунктах. Записать **float**. |
| virtual void [set_Y](./set_y/)(**float**) | Устанавливает координату y верхнего левого угла формы в пунктах. Записать **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (в отличие от shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкт C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Сохраняет содержимое [Shape](../shape/) в SVG-файл. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Сохраняет содержимое [Shape](../shape/) в SVG-файл. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ISlideComponent](../islidecomponent/)
* Класс [IHyperlinkContainer](../ihyperlinkcontainer/)
* Пространство имён [Aspose::Slides](../)
* Library [Aspose.Slides](../../)