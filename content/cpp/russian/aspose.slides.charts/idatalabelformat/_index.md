---
title: IDataLabelFormat
second_title: Aspose.Slides для C++ справка по API
description: Представляет параметры форматирования для DataLabel.
type: docs
weight: 963
url: /ru/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat класс

Представляет параметры форматирования для [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Представляет формат подписи данных. Только для чтения [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Читает **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Представляет строку формата для объекта DataLabels. Читает [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Представляет положение подписи данных. Читает [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Устанавливает или возвращает объект Variant, представляющий разделитель, используемый для подписей данных на диаграмме. Читает [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. Истина отображает значение размера пузыря. Ложь скрывает. Читает **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Представляет поведение отображения названия категории подписи данных указанной диаграммы. Истина отображает название категории для подписей данных на диаграмме. Ложь скрывает. Читает **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Определяет, будет ли подпись данных указанной диаграммы отображаться как выноска данных или как подпись данных. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. Истина отображает значение ячейки. Ложь скрывает. Читает **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Представляет поведение отображения направляющих линий подписи данных указанной диаграммы. Истина отображает направляющие линии. Ложь скрывает. Читает **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. Истина, если ключ легенды подписи данных видим. Читает **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. Истина отображает процентное значение. Ложь скрывает. Читает **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Возвращает логическое значение, указывающее поведение отображения названия серии подписи данных на диаграмме. Истина отображает название серии. Ложь скрывает. Читает **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. Истина отображает процентное значение. Ложь скрывает. Читает **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Возвращает формат текста диаграммы. Только для чтения [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
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
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Записывает **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Представляет строку формата для объекта DataLabels. Записывает [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Представляет положение подписи данных. Записывает [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Устанавливает или возвращает объект Variant, представляющий разделитель, используемый для подписей данных на диаграмме. Записывает [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. Истина отображает значение размера пузыря. Ложь скрывает. Записывает **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Представляет поведение отображения названия категории подписи данных указанной диаграммы. Истина отображает название категории для подписей данных на диаграмме. Ложь скрывает. Записывает **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Определяет, будет ли подпись данных указанной диаграммы отображаться как выноска данных или как подпись данных. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. Истина отображает значение ячейки. Ложь скрывает. Записывает **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Представляет поведение отображения направляющих линий подписи данных указанной диаграммы. Истина отображает направляющие линии. Ложь скрывает. Записывает **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. Истина, если ключ легенды подписи данных видим. Записывает **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. Истина отображает процентное значение. Ложь скрывает. Записывает **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Устанавливает логическое значение, указывающее поведение отображения названия серии подписи данных на диаграмме. Истина отображает название серии. Ложь скрывает. Записывает **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. Истина отображает процентное значение. Ложь скрывает. Записывает **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в режим слабых указателей. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счётчика разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IFormattedTextContainer](../iformattedtextcontainer/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)