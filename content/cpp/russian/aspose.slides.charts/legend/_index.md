---
title: Legend
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства легенды диаграммы.
type: docs
weight: 1262
url: /ru/aspose.slides.charts/legend/
---
## Legend класс

Представляет свойства легенды диаграммы.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Указывает фактическую высоту элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) заранее, чтобы получить реальные значения. Читайте **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Указывает фактическую ширину элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) заранее, чтобы получить реальные значения. Читайте **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Указывает фактическое положение по оси x (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) заранее, чтобы получить реальные значения. Читайте **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Указывает фактическую верхнюю границу элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) заранее, чтобы получить реальные значения. Читайте **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Нижняя граница. Только для чтения **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Получает элементы легенды. Только для чтения [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Получает свойства элемента легенды, соответствующего точке данных в диаграмме по указанному индексу. Для типов диаграмм: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, точка данных берется из первой серии. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Возвращает формат легенды. Только для чтения [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Возвращает высоту легенды как долю от высоты диаграммы. Читайте **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Определяет, разрешено ли другим элементам диаграммы перекрывать легенду. Читайте **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Указывает позицию легенды на диаграмме. Значения X, Y, Width, Heigt, отличные от NaN, переопределяют действие этого свойства. Читайте [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Правая граница. Только для чтения **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Формат текста. Только для чтения [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Возвращает ширину легенды как долю от ширины диаграммы. Читайте **float**. |
| **float** [get_X](./get_x/)() override | Возвращает координату x легенды как долю от ширины диаграммы. Читайте **float**. |
| **float** [get_Y](./get_y/)() override | Возвращает координату y легенды как долю от высоты диаграммы. Читайте **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_Height](./set_height/)(**float**) override | Устанавливает высоту легенды как долю от высоты диаграммы. Записывайте **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Определяет, разрешено ли другим элементам диаграммы перекрывать легенду. Записывайте **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Указывает позицию легенды на диаграмме. Значения X, Y, Width, Heigt, отличные от NaN, переопределяют действие этого свойства. Записывайте [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Устанавливает ширину легенды как долю от ширины диаграммы. Записывайте **float**. |
| void [set_X](./set_x/)(**float**) override | Устанавливает координату x легенды как долю от ширины диаграммы. Записывайте **float**. |
| void [set_Y](./set_y/)(**float**) override | Устанавливает координату y легенды как долю от высоты диаграммы. Записывайте **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [DomObject](../../aspose.slides/domobject/)
* Класс [ILegend](../ilegend/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)