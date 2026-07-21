---
title: ZoomObject
second_title: Справочник API Aspose.Slides для C++
description: Представляет объект Zoom на слайде.
type: docs
weight: 5591
url: /ru/aspose.slides/zoomobject/
---
## ZoomObject класс

Represents an Zoom object in a slide.

```cpp
class ZoomObject : public Aspose::Slides::GraphicalObject,
                   public virtual Aspose::Slides::IZoomObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанный. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Возвращает альтернативный текст, связанный с фигурой. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Возвращает заголовок альтернативного текста, связанного с фигурой. Читать [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Свойство определяет, как фигура будет отображаться в черно-белом режиме.. Читать [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Возвращает количество точек соединения на фигуре. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применённые к фигуре. Примечание: может возвращать null для определённых типов фигур, у которых нет свойств эффектов. Только для чтения [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки для фигуры. Примечание: может возвращать null для определённых типов фигур, у которых нет свойств заливки. Только для чтения [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Возвращает свойства рамки фигуры. Читать [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Возвращает блокировки фигуры. Только для чтения [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Получает высоту фигуры в пунктах. Читать **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Определяет, скрыта ли фигура. Читать **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Возвращает гиперссылку, определённую для щелчка мышью. Читать [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Возвращает менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Возвращает гиперссылка, определённую при наведении мыши. Читать [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() override | Получает тип изображения объекта Zoom. Читать [ZoomImageType](../zoomimagetype/). Значение по умолчанию: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Получает параметр 'Mark as decorative'. Чтение/запись **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Определяет, является ли фигура TextHolder_PPT. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий для фигуры. Примечание: может возвращать null для определённых типов фигур, у которых нет свойств линии. Только для чтения [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Возвращает имя фигуры. Не может быть null. При необходимости используйте пустую строку. Читать [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Возвращает уникальный идентификатор в пределах слайда, который остаётся неизменным на протяжении жизни фигуры и позволяет PowerPoint или коду межоперативного взаимодействия надёжно ссылаться на фигуру из любой части документа. Только для чтения **uint32_t**. См. также [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Возвращает родительский объект [GroupShape](../groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Возвращает родительскую презентацию слайда. Только для чтения [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Возвращает свойства необработанной рамки фигуры. Читать [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](./get_returntoparent/)() override | Получает поведение навигации в слайд-шоу. Читать **bool**. Значение по умолчанию: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Возвращает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Читать **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](./get_showbackground/)() override | Получает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Читать **bool**. Значение по умолчанию: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Возвращает родительский слайд фигуры. Только для чтения [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства 3D-эффекта для фигуры. Примечание: может возвращать null для определённых типов фигур, у которых нет 3D-свойств. Только для чтения [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](./get_transitionduration/)() override | Получает длительность перехода между Zoom и слайдом. Читать **float**. Значение по умолчанию: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования ад-инами или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Получает ширину фигуры в пунктах. Читать **float**. |
| **float** [get_X](../shape/get_x/)() override | Получает координату x верхнего-левого угла фигуры в пунктах. Читать **float**. |
| **float** [get_Y](../shape/get_y/)() override | Получает координату y верхнего-левого угла фигуры в пунктах. Читать **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() override | Получает изображение для объекта Zoom. Читать [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Возвращает позицию фигуры в порядке Z. Shapes[0] возвращает фигуру в задней части порядка Z, а Shapes[Shapes.Count - 1] — в передней. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Возвращает базовую форму заполнителя (форму из макета и/или мастер-слайда, от которой унаследована текущая фигура). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на заданное значение. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Определяет, что эта фигура не является заполнителем. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Устанавливает альтернативный текст, связанный с фигурой. Записать [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Устанавливает заголовок альтернативного текста, связанный с фигурой. Записать [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Свойство определяет, как фигура будет отображаться в черно-белом режиме.. Записать [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает свойства рамки фигуры. Записать [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Устанавливает высоту фигуры в пунктах. Записать **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Определяет, скрыта ли фигура. Записать **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылка, определённую для щелчка мышью. Записать [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылка, определённую при наведении мыши. Записать [IHyperlink](../ihyperlink/). |
| void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Устанавливает тип изображения объекта Zoom. Записать [ZoomImageType](../zoomimagetype/). Значение по умолчанию: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Устанавливает параметр 'Mark as decorative'. Чтение/запись **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Устанавливает имя фигуры. Не может быть null. При необходимости используйте пустую строку. Записать [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает свойства необработанной рамки фигуры. Записать [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](./set_returntoparent/)(**bool**) override | Устанавливает поведение навигации в слайд-шоу. Записать **bool**. Значение по умолчанию: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Устанавливает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Записать **float**. |
| void [set_ShowBackground](./set_showbackground/)(**bool**) override | Устанавливает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Записать **bool**. Значение по умолчанию: true |
| void [set_TransitionDuration](./set_transitionduration/)(**float**) override | Устанавливает длительность перехода между Zoom и слайдом. Записать **float**. Значение по умолчанию: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Устанавливает ширину фигуры в пунктах. Записать **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Устанавливает координату x верхнего-левого угла фигуры в пунктах. Записать **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Устанавливает координату y верхнего-левого угла фигуры в пунктах. Записать **float**. |
| void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Устанавливает изображение для объекта Zoom. Записать [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона в виде слабой ссылки (а не общей). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Очищает все внутренние структуры данных. |

## Смотрите также

* Класс [GraphicalObject](../graphicalobject/)
* Класс [IZoomObject](../izoomobject/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)