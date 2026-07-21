---
title: ITextFrameFormat
second_title: Aspose.Slides для C++ справочник API
description: Содержит свойства форматирования TextFrame.
type: docs
weight: 4083
url: /ru/aspose.slides/itextframeformat/
---
## ITextFrameFormat класс


Содержит свойства форматирования [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Возвращает вертикальный якорный текст в [TextFrame](../textframe/). Читайте [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Возвращает режим автоподгонки текста. Читайте [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Если [NullableBool::True](../nullablebool/), то текст должен быть выровнен по центру горизонтально в рамке. Читайте [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Возвращает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Значение 0 означает неопределённое значение. Читайте **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Возвращает расстояние между текстовыми столбцами в текстовой области (в пунктах). Это применимо только при наличии более одного столбца. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Читайте **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Возвращает или задаёт удержание текста полностью вне 3D-сцены. Читайте **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Возвращает нижний отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Возвращает левый отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Возвращает правый отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Возвращает верхний отступ (в пунктах) в [TextFrame](../textframe/). Читайте **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Указывает пользовательский поворот, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется поворот сопутствующей фигуры. Если указано, то применяется независимо от фигуры. То есть фигура может иметь свой поворот, дополнительно к повороту самого текста. Полученное значение визуального поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Читайте **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Возвращает стиль текста. Только для чтения [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Определяет ориентацию текста. Полученное значение визуального поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Читайте [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Возвращает объект [ThreeDFormat](../threedformat/), представляющий свойства 3D-эффекта для текста. Только для чтения [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Получает форму обтекания текста. Читайте [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True**, если текст обтекает границы [TextFrame](../textframe/). Читайте [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Получает эффективные данные форматирования текстового кадра с учётом наследования. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Устанавливает вертикальный якорный текст в [TextFrame](../textframe/). Запишите [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Устанавливает режим автоподгонки текста. Запишите [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Если [NullableBool::True](../nullablebool/), то текст должен быть выровнен по центру горизонтально в рамке. Запишите [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Устанавливает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Значение 0 означает неопределённое значение. Запишите **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Устанавливает расстояние между текстовыми столбцами в текстовой области (в пунктах). Это применимо только при наличии более одного столбца. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Запишите **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Устанавливает/возвращает удержание текста полностью вне 3D-сцены. Запишите **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Устанавливает нижний отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Устанавливает левый отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Устанавливает правый отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Устанавливает верхний отступ (в пунктах) в [TextFrame](../textframe/). Запишите **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Указывает пользовательский поворот, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется поворот сопутствующей фигуры. Если указано, то применяется независимо от фигуры. То есть фигура может иметь свой поворот, дополнительно к повороту самого текста. Полученное значение визуального поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Запишите **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Определяет ориентацию текста. Полученное значение визуального поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Запишите [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Устанавливает форму обтекания текста. Запишите [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True**, если текст обтекает границы [TextFrame](../textframe/). Запишите [NullableBool](../nullablebool/). |
| virtual [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкт C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Разрушает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)