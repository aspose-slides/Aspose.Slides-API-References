---
title: Shape
second_title: Справочник API Aspose.Slides для C++
description: Представляет форму на слайде.
type: docs
weight: 5084
url: /ru/aspose.slides/shape/
---
## Класс Shape

Представляет форму на слайде.

```cpp
class Shape : public virtual Aspose::Slides::IShape,
              public Aspose::Slides::IDOMObject
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя в указанный. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() override | Возвращает альтернативный текст, связанный с формой. См. [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() override | Возвращает заголовок альтернативного текста, связанный с формой. См. [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() override | Свойство указывает, как форма будет отображаться в черно-белом режиме. См. [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() override | Возвращает количество точек соединения на форме. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Возвращает пользовательские данные формы. Только для чтения [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применённые к форме. Примечание: может возвращать null для некоторых типов форм, у которых нет свойств эффектов. Только для чтения [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки формы. Примечание: может возвращать null для некоторых типов форм, у которых нет свойств заливки. Только для чтения [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | Возвращает свойства рамки формы. См. [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](./get_height/)() override | Получает высоту формы в пунктах. Только для чтения **float**. |
| **bool** [get_Hidden](./get_hidden/)() override | Определяет, скрыта ли форма. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Возвращает гиперссылку, определённую для клика мышью. См. [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Возвращает менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Возвращает гиперссылку, определённую для наведения мышью. См. [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](./get_isdecorative/)() override | Получает параметр «Отметить как декоративный». Чтение/запись **bool**. |
| **bool** [get_IsGrouped](./get_isgrouped/)() override | Определяет, находится ли форма в группе. Только для чтения **bool**. |
| **bool** [get_IsTextHolder](./get_istextholder/)() override | Определяет, является ли форма TextHolder_PPT. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий формы. Примечание: может возвращать null для некоторых типов форм, у которых нет свойств линий. Только для чтения [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Возвращает имя формы. Должно быть не null. При необходимости используйте пустую строку. См. [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() override | Возвращает уникальный идентификатор в пределах слайда, который остаётся постоянным в течение жизни формы и позволяет PowerPoint или коду интероперации надёжно ссылаться на форму из любой части документа. Только для чтения **uint32_t**. См. также [Shape::get_UniqueId](./get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | Возвращает родительский объект [GroupShape](../groupshape/), если форма сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() override | Возвращает заполнитель для формы. Возвращает null, если у формы нет заполнителя. Только для чтения [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Возвращает родительскую презентацию слайда. Только для чтения [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() override | Возвращает свойства необработанной рамки формы. См. [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](./get_rotation/)() override | Возвращает количество градусов, на которое указана форма вращена вокруг оси Z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Только для чтения **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() override | Возвращает блокировки формы. Только для чтения [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Возвращает родительский слайд формы. Только для чтения [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства 3D-эффекта формы. Примечание: может возвращать null для некоторых типов форм, у которых нет 3D-свойств. Только для чтения [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](./get_uniqueid/)() override | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. См. также [Shape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| **float** [get_Width](./get_width/)() override | Получает ширину формы в пунктах. Только для чтения **float**. |
| **float** [get_X](./get_x/)() override | Получает координату X левого верхнего угла формы в пунктах. Только для чтения **float**. |
| **float** [get_Y](./get_y/)() override | Получает координату Y левого верхнего угла формы в пунктах. Только для чтения **float**. |
| **int32_t** [get_ZOrderPosition](./get_zorderposition/)() override | Возвращает позицию формы в порядке Z. Shapes[0] возвращает форму в самом заднем положении, а Shapes[Shapes.Count - 1] — форму в переднем положении. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](./getbaseplaceholder/)() override | Возвращает базовую форму-заполнитель (форму из макета и/или мастера слайда, от которой унаследована текущая форма). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | Возвращает миниатюру формы. По умолчанию используется тип границ миниатюры [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Возвращает миниатюру формы. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](./getvisualbounds/)() | Получает визуальные границы формы, рассчитанные из её отрисованного содержимого. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает общий счётчик ссылок на указанное значение. |
| void [RemovePlaceholder](./removeplaceholder/)() override | Определяет, что данная форма не является заполнителем. |
| void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) override | Устанавливает альтернативный текст, связанный с формой. Запись [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) override | Устанавливает заголовок альтернативного текста, связанный с формой. Запись [System::String](../../system/string/). |
| void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Свойство указывает, как форма будет отображаться в черно-белом режиме. Запись [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает свойства рамки формы. Запись [IShapeFrame](../ishapeframe/). |
| void [set_Height](./set_height/)(**float**) override | Устанавливает высоту формы в пунктах. Запись **float**. |
| void [set_Hidden](./set_hidden/)(**bool**) override | Определяет, скрыта ли форма. Запись **bool**. |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку, определённую для клика мышью. Запись [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку, определённую для наведения мышью. Запись [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](./set_isdecorative/)(**bool**) override | Устанавливает параметр «Отметить как декоративный». Чтение/запись **bool**. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Устанавливает имя формы. Должно быть не null. При необходимости используйте пустую строку. Запись [System::String](../../system/string/). |
| void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает свойства необработанной рамки формы. Запись [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](./set_rotation/)(**float**) override | Устанавливает количество градусов, на которое указанная форма вращена вокруг оси Z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| void [set_Width](./set_width/)(**float**) override | Устанавливает ширину формы в пунктах. Запись **float**. |
| void [set_X](./set_x/)(**float**) override | Устанавливает координату X левого верхнего угла формы в пунктах. Запись **float**. |
| void [set_Y](./set_y/)(**float**) override | Устанавливает координату Y левого верхнего угла формы в пунктах. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение общего счётчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Сохраняет содержимое [Shape](./) в файл SVG. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Сохраняет содержимое [Shape](./) в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IShape](../ishape/)
* Класс [IDOMObject](../idomobject/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)