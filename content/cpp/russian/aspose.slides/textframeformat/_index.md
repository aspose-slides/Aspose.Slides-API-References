---
title: TextFrameFormat
second_title: Aspose.Slides для C++ справки API
description: Содержит свойства formatTextFrameFormatting объекта TextFrame.
type: docs
weight: 5461
url: /ru/aspose.slides/textframeformat/
---
## TextFrameFormat класс

Содержит свойства formatTextFrameFormatting [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Методы

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Возвращает вертикальный якорный текст в [TextFrame](../textframe/). Читайте [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Возвращает режим автоподгонки текста. Читайте [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Если [NullableBool::True](../nullablebool/), то текст должен быть центрирован по горизонтали в коробке. Читайте [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Возвращает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Значение 0 означает неопределённое значение. Читайте **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Возвращает расстояние между столбцами текста в текстовой области (в пунктах). Применяется только когда присутствует более одного столбца. Это значение должно быть положительным числом. В противном случае будет установлено в ноль. Читайте **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Получает признак сохранения текста плоским, даже если применён эффект 3-D вращения. Читайте **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Возвращает нижний отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Возвращает левый отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Возвращает правый отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Возвращает верхний отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Задает пользовательский угол вращения, применяемый к тексту внутри ограничивающего бокса. Если не указано, используется вращение сопутствующей фигуры. Если указано, то применяется независимо от фигуры. То есть фигура может иметь вращение, дополнительно к вращению самого текста. Итоговое значение визуального вращения текста формируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Читайте **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Определяет ориентацию текста. Итоговое значение визуального вращения текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Читайте [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Возвращает объект [ThreeDFormat](../threedformat/), представляющий свойства 3D-эффекта для текста. Только для чтения [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Получает форму переноса текста. Читайте [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True**, если текст перенесён на полях [TextFrame](../textframe/). Читайте [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Получает эффективные данные форматирования text frame с применённым наследованием. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Возвращает код хеша. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Устанавливает вертикальный якорный текст в [TextFrame](../textframe/). Запишите [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Устанавливает режим автоподгонки текста. Запишите [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Если [NullableBool::True](../nullablebool/), то текст должен быть центрирован по горизонтали в коробке. Запишите [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Устанавливает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае будет установлено в ноль. Значение 0 означает неопределённое значение. Запишите **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Устанавливает расстояние между столбцами текста в текстовой области (в пунктах). Применяется только когда присутствует более одного столбца. Это значение должно быть положительным числом. В противном случае будет установлено в ноль. Запишите **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Устанавливает признак сохранения текста плоским, даже если применён эффект 3-D вращения. Запишите **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Устанавливает нижний отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Устанавливает левый отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Устанавливает правый отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Устанавливает верхний отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Задает пользовательский угол вращения, применяемый к тексту внутри ограничивающего бокса. Если не указано, используется вращение сопутствующей фигуры. Если указано, то применяется независимо от фигуры. То есть фигура может иметь вращение, дополнительно к вращению самого текста. Итоговое значение визуального вращения текста формируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Запишите **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Определяет ориентацию текста. Итоговое значение визуального вращения текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Запишите [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Устанавливает форму переноса текста. Запишите [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True**, если текст перенесён на полях [TextFrame](../textframe/). Запишите [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [TextFrameFormat](./textframeformat/)() | Инициализирует новый экземпляр класса [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [PVIObject](../pviobject/)
* Класс [ITextFrameFormat](../itextframeformat/)
* Класс [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)