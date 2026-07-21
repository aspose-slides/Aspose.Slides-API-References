---
title: IChartTextBlockFormat
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства форматирования для текстовых элементов диаграммы.
type: docs
weight: 885
url: /ru/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat класс

Представляет свойства форматирования для элементов текста диаграммы.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Возвращает вертикальный якорный текст в [TextFrame](../../aspose.slides/textframe/). Читать [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Возвращает режим автоподгонки текста. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Читать [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | Если [NullableBool::True](../../aspose.slides/nullablebool/), то текст должен быть центрирован по горизонтали в рамке. Читать [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Возвращает нижний отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Читать **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Возвращает левый отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Читать **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Возвращает правый отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Читать **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Возвращает верхний отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Читать **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется поворот сопряжённой фигуры. Если указано, то применяется независимо от фигуры. То есть фигура может иметь поворот, дополнительно к повороту самого текста. Полученное визуальное значение поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Читать **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Определяет ориентацию текста. Полученное визуальное значение поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Читать [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** если текст переносится по полям [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2007/2013). Читать [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанного с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Устанавливает вертикальный якорный текст в [TextFrame](../../aspose.slides/textframe/). Записать [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Устанавливает режим автоподгонки текста. Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Записать [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | Если [NullableBool::True](../../aspose.slides/nullablebool/), то текст должен быть центрирован по горизонтали в рамке. Записать [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Устанавливает нижний отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Записать **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Устанавливает левый отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Записать **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Устанавливает правый отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Записать **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Устанавливает верхний отступ (в пунктах) в [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2013; в PowerPoint 2007 нет эффекта при рендеринге). Записать **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Указывает пользовательский угол поворота, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется поворот сопряжённой фигуры. Если указано, то применяется независимо от фигуры. То есть фигура может иметь поворот, дополнительно к повороту самого текста. Полученное визуальное значение поворота текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Записать **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Определяет ориентацию текста. Полученное визуальное значение поворота текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Записать [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** если текст переносится по полям [TextFrame](../../aspose.slides/textframe/). Изменение этого свойства может оказывать влияние только на следующие части диаграммы: [DataLabel](../datalabel/) и [DataLabelFormat](../datalabelformat/) (полная поддержка в PowerPoint 2007/2013). Записать [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не совместный). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)