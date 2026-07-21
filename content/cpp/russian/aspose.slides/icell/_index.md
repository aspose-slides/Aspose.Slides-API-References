---
title: ICell
second_title: Aspose.Slides для C++ API Reference
description: Представляет ячейку в таблице.
type: docs
weight: 1639
url: /ru/aspose.slides/icell/
---
## ICell класс

Представляет ячейку в таблице.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочных типов в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимых типов в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, даже несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, даже несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Определяет, центрирован ли текстовый блок внутри ячейки. Чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Возвращает объект [CellFormat](../cellformat/), содержащий свойства форматирования этой ячейки. Только для чтения [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Возвращает количество столбцов сетки в таблице-родителе, которые должна покрывать текущая ячейка. Это свойство позволяет ячейкам выглядеть объединёнными, так как они охватывают вертикальные границы других ячеек в таблице. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Получает первый столбец ячейки. Только для чтения [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Возвращает индекс первого столбца, покрытого ячейкой. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Получает первую строку ячейки. Только для чтения [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Возвращает индекс первой строки, покрытой ячейкой. Только для чтения **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Возвращает высоту ячейки. Только для чтения **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Возвращает true, если ячейка объединена с любой смежной ячейкой, иначе false. Только для чтения **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Возвращает нижний отступ в [TextFrame](../textframe/). Чтение **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Возвращает левый отступ в [TextFrame](../textframe/). Чтение **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Возвращает правый отступ в [TextFrame](../textframe/). Чтение **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Возвращает верхний отступ в [TextFrame](../textframe/). Чтение **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Возвращает минимальную высоту ячейки. Это сумма минимальных высот всех строк, покрываемых ячейкой. Только для чтения **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Возвращает расстояние от левой стороны таблицы до левой стороны ячейки. Только для чтения **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Возвращает расстояние от верхней стороны таблицы до верхней стороны ячейки. Только для чтения **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Возвращает количество строк, которые охватывает объединённая ячейка. Используется в сочетании с атрибутом vMerge у других ячеек для указания начальной ячейки горизонтального объединения. Только для чтения **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Возвращает объект-родитель [Table](../table/) для ячейки. Только для чтения [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Возвращает тип привязки текста. Чтение [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Возвращает текстовый фрейм ячейки. Только для чтения [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Возвращает тип вертикального текста. Чтение [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Возвращает ширину ячейки. Только для чтения **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Определяет, центрирован ли текстовый блок внутри ячейки. Запись **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Устанавливает нижний отступ в [TextFrame](../textframe/). Запись **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Устанавливает левый отступ в [TextFrame](../textframe/). Запись **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Устанавливает правый отступ в [TextFrame](../textframe/). Запись **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Устанавливает верхний отступ в [TextFrame](../textframe/). Запись **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Устанавливает тип привязки текста. Запись [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Устанавливает тип вертикального текста. Запись [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент в виде слабого указателя (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Разделяет ячейку на две ячейки по индексу столбца. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Разделяет ячейку по высоте. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Разделяет ячейку на две ячейки по индексу строки. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Разделяет ячейку по ширине. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ISlideComponent](../islidecomponent/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)