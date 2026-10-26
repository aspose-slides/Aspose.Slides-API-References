---
title: Cell
second_title: Aspose.Slides для C++ API справка
description: Представляет ячейку таблицы.
type: docs
weight: 300
url: /ru/aspose.slides/cell/
---
## Cell класс

Представляет ячейку таблицы.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Определяет, выровнено ли текстовое поле по центру внутри ячейки. Чтение **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Возвращает объект [CellFormat](../cellformat/), содержащий свойства форматирования для этой ячейки. Только для чтения [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Возвращает количество колонок сетки в таблице-родителе, которые должна охватывать текущая ячейка. Это свойство позволяет ячейкам выглядеть объединёнными, поскольку они охватывают вертикальные границы других ячеек таблицы. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Получает первую колонку ячейки. Только для чтения [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Возвращает индекс первой колонки, охваченной ячейкой. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Получает первую строку ячейки. Только для чтения [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Возвращает индекс первой строки, охваченной ячейкой. Только для чтения **int32_t**. |
| **double** [get_Height](./get_height/)() override | Возвращает высоту ячейки. Только для чтения **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Возвращает true, если ячейка объединена с любой скорректированной ячейкой, иначе false. Только для чтения **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Возвращает нижний отступ в [TextFrame](../textframe/). Чтение **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Возвращает левый отступ в [TextFrame](../textframe/). Чтение **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Возвращает правый отступ в [TextFrame](../textframe/). Чтение **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Возвращает верхний отступ в [TextFrame](../textframe/). Чтение **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Возвращает минимальную высоту ячейки. Это сумма минимальных высот всех строк, покрываемых ячейкой. Только для чтения **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Возвращает расстояние от левой стороны таблицы до левой стороны ячейки. Только для чтения **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Возвращает расстояние от верхней стороны таблицы до верхней стороны ячейки. Только для чтения **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Возвращает презентацию-родителя ячейки. Только для чтения [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Возвращает количество строк, которые охватывает объединённая ячейка. Это используется совместно с атрибутом vMerge в других ячейках для указания начальной ячейки горизонтального объединения. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Возвращает слайд-родитель ячейки. Только для чтения [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Возвращает объект [Table](../table/)-родитель для ячейки. Только для чтения [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Возвращает тип привязки текста. Чтение [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Возвращает текстовый фрейм ячейки. Только для чтения [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Возвращает тип вертикального текста. Чтение [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Возвращает ширину ячейки. Только для чтения **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект value type с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Определяет, выровнено ли текстовое поле по центру внутри ячейки. Запись **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Устанавливает нижний отступ в [TextFrame](../textframe/). Запись **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Устанавливает левый отступ в [TextFrame](../textframe/). Запись **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Устанавливает правый отступ в [TextFrame](../textframe/). Запись **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Устанавливает верхний отступ в [TextFrame](../textframe/). Запись **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Устанавливает тип привязки текста. Запись [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Устанавливает тип вертикального текста. Запись [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n'tй шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Разделяет ячейку на две ячейки по индексу колонки. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Разделяет ячейку по высоте. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Разделяет ячейку на две ячейки по индексу строки. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Разделяет ячейку по ширине. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IDOMObject](../idomobject/)
* Класс [ICell](../icell/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)