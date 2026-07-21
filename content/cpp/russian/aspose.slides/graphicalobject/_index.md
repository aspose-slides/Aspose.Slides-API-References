---
title: GraphicalObject
second_title: Справочник API Aspose.Slides для C++
description: Представляет абстрактный графический объект.
type: docs
weight: 1171
url: /ru/aspose.slides/graphicalobject/
---
## GraphicalObject класс

Представляет абстрактный графический объект.

```cpp
class GraphicalObject : public Aspose::Slides::Shape,
                        public virtual Aspose::Slides::IGraphicalObject
```

## Методы

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанный. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Возвращает альтернативный текст, связанный с фигурой. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Возвращает заголовок альтернативного текста, связанный с фигурой. Читать [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Свойство указывает, как фигура будет отображаться в черно-белом режиме. Чтение [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Возвращает количество точек подключения на фигуре. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применяемые к фигуре. Примечание: может вернуть null для некоторых типов фигур, у которых нет свойств эффектов. Только для чтения [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки для фигуры. Примечание: может вернуть null для некоторых типов фигур, у которых нет свойств заливки. Только для чтения [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Возвращает свойства рамки фигуры. Чтение [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](./get_graphicalobjectlock/)() override | Возвращает блокировки фигуры. Только для чтения [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Получает высоту фигуры в пунктах. Только для чтения **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Определяет, скрыта ли фигура. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Возвращает гиперссылку, определённую для щелчка мышью. Чтение [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Возвращает менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Возвращает гиперссылка, определённую для наведения мышью. Чтение [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Получает параметр «Mark as decorative». Чтение/запись **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Определяет, является ли фигура TextHolder_PPT. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий для фигуры. Примечание: может вернуть null для некоторых типов фигур, у которых нет свойств линий. Только для чтения [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Возвращает имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Чтение [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Возвращает уникальный идентификатор в пределах слайда, остающийся постоянным в течение жизни фигуры и позволяющий PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа. Только для чтения **uint32_t**. См. также [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Возвращает родительский объект [GroupShape](../groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Возвращает родительскую презентацию слайда. Только для чтения [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Возвращает свойства необработанной рамки фигуры. Чтение [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Возвращает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Только для чтения **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Возвращает родительский слайд фигуры. Только для чтения [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства 3D-эффекта для фигуры. Примечание: может вернуть null для некоторых типов фигур, у которых нет 3D-свойств. Только для чтения [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Возвращает внутренний идентификатор, scoped к презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Получает ширину фигуры в пунктах. Только для чтения **float**. |
| **float** [get_X](../shape/get_x/)() override | Получает координату x верхнего левого угла фигуры в пунктах. Только для чтения **float**. |
| **float** [get_Y](../shape/get_y/)() override | Получает координату y верхнего левого угла фигуры в пунктах. Только для чтения **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в задней части порядка z, а Shapes[Shapes.Count - 1] возвращает фигуру в передней части порядка z. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Возвращает базовую форму заполнителя (форму из макета и/или мастер-слайда, от которой унаследована текущая форма). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку C# lock(). Вызывайте напрямую или используйте сторожевой объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Определяет, что эта фигура не является заполнителем. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Устанавливает альтернативный текст, связанный с фигурой. Запись [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Устанавливает заголовок альтернативного текста, связанный с фигурой. Запись [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Свойство задаёт, как фигура будет отображаться в черно-белом режиме. Запись [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает свойства рамки фигуры. Запись [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Устанавливает высоту фигуры в пунктах. Запись **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Определяет, скрыта ли фигура. Запись **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку, определённую для щелчка мышью. Запись [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку, определённую для наведения мышью. Запись [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Устанавливает параметр «Mark as decorative». Чтение/запись **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Устанавливает имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Запись [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает свойства необработанной рамки фигуры. Запись [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Устанавливает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Устанавливает ширину фигуры в пунктах. Запись **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Устанавливает координату x верхнего левого угла фигуры в пунктах. Запись **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Устанавливает координату y верхнего левого угла фигуры в пунктах. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку C# lock(). Вызывайте напрямую или используйте сторожевой объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Сохраняет содержимое [Shape](../shape/) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Shape](../shape/)
* Класс [IGraphicalObject](../igraphicalobject/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)