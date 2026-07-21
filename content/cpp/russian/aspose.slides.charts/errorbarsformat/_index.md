---
title: ErrorBarsFormat
second_title: Справочник API Aspose.Slides для C++
description: "Представляет линии ошибок серии диаграммы. Пользовательские значения ErrorBars находятся в IChartDataPointCollection (в свойстве IChartDataPoint::get_ErrorBarsCustomValues())."
type: docs
weight: 482
url: /ru/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat класс

Represents error bars of chart series. ErrorBars custom values are in [IChartDataPointCollection](../ichartdatapointcollection/) (in [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) property).

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Возвращает родительскую диаграмму. Только для чтения [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Представляет формат линий ошибок. Чтение [IFormat](../iformat/). |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | Указывает, что конец кончика не рисуется на линиях ошибок. Чтение **bool**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Получает видимость линий ошибок. Чтение **bool**. |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | Получает тип линий ошибок. Чтение [ErrorBarType](../errorbartype/). |
| **float** [get_Value](./get_value/)() override | Получает значение, которое используется с типами значений Fixed, Percentage и StandardDeviation для определения длины линий ошибок. В любом другом случае будет возвращать NaN. Чтение **float**. |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | Представляет возможные способы определения длины линий ошибок. В случае пользовательского типа значения для указания значения используйте свойство [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) конкретной точки данных в коллекции DataPoints серии. В случае типа Fixed, Percentage или StandardDeviation используйте свойство Value для указания значения.  

 Чтение [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Представляет формат линий ошибок. Запись [IFormat](../iformat/). |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | Указывает, что конец кончика не рисуется на линиях ошибок. Запись **bool**. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Устанавливает видимость линий ошибок. Запись **bool**. |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | Устанавливает тип линий ошибок. Запись [ErrorBarType](../errorbartype/). |
| void [set_Value](./set_value/)(**float**) override | Устанавливает значение, которое используется с типами Fixed, Percentage и StandardDeviation для определения длины линий ошибок. В любом другом случае будет возвращать NaN. Запись **float**. |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | Представляет возможные способы определения длины линий ошибок. В случае пользовательского типа значения для указания значения используйте свойство [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) конкретной точки данных в коллекции DataPoints серии. В случае типа Fixed, Percentage или StandardDeviation используйте свойство Value для указания значения.  

 Запись [ErrorBarValueType](../errorbarvaluetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Устанавливает n-ый аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [DomObject](../../aspose.slides/domobject/)
* Класс [IErrorBarsFormat](../ierrorbarsformat/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)