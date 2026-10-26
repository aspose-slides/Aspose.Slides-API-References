---
title: ChartTitle
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства заголовка диаграммы.
type: docs
weight: 326
url: /ru/aspose.slides.charts/charttitle/
---
## ChartTitle класс

Представляет свойства заголовка диаграммы.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Методы

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Инициализирует TextFrameForOverriding текстом из параметра «text». Если TextFrameForOverriding уже инициализирован, просто изменяет его текст. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типом значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Указывает фактическую высоту элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед получением фактических значений. Чтение **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Указывает фактическую ширину элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед получением фактических значений. Чтение **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Указывает фактическую позицию x (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед получением фактических значений. Чтение **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Указывает фактическую позицию сверху элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед получением фактических значений. Чтение **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Нижний край. Только для чтения **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Возвращает родительскую диаграмму. Только для чтения [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Возвращает стили заливки, линии и эффектов заголовка. Только для чтения [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Возвращает высоту заголовка как долю высоты диаграммы. Чтение **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Определяет, разрешено ли другим элементам диаграммы перекрывать заголовок. Чтение **bool**. |
| **float** [get_Right](./get_right/)() override | Правый край. Только для чтения **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Возвращает формат текста. Только для чтения [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Может содержать текст с расширенным форматированием. Если это свойство не равно null, то отформатированный текст переопределяет автоматически сгенерированный. Автогенерируемый текст является неявным свойством метки данных, метки единиц оси значений, названия оси, заголовка диаграммы, метки тренд-линии. Автогенерируемый текст форматируется свойством [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Только для чтения [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Возвращает ширину заголовка как долю ширины диаграммы. Чтение **float**. |
| **float** [get_X](./get_x/)() override | Возвращает координату x заголовка как долю ширины диаграммы. Чтение **float**. |
| **float** [get_Y](./get_y/)() override | Возвращает координату y заголовка как долю высоты диаграммы. Чтение **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# «is». |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналог C# lock(). Вызывается напрямую или через объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Height](./set_height/)(**float**) override | Устанавливает высоту заголовка как долю высоты диаграммы. Запись **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Определяет, разрешено ли другим элементам диаграммы перекрывать заголовок. Запись **bool**. |
| void [set_Width](./set_width/)(**float**) override | Устанавливает ширину заголовка как долю ширины диаграммы. Запись **float**. |
| void [set_X](./set_x/)(**float**) override | Устанавливает координату x заголовка как долю ширины диаграммы. Запись **float**. |
| void [set_Y](./set_y/)(**float**) override | Устанавливает координату y заголовка как долю высоты диаграммы. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналог C# lock(). Вызывается напрямую или через объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Class [IChartTitle](../icharttitle/)
* Class [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)