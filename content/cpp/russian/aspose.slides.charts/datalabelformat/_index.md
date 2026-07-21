---
title: DataLabelFormat
second_title: Aspose.Slides для C++ справка API
description: Представляет параметры форматирования для DataLabel.
type: docs
weight: 391
url: /ru/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat класс

Представляет параметры форматирования для [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Представляет формат подписи данных. Только для чтения [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Чтение **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Представляет строку формата для объекта DataLabels. Чтение [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родителя [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Только для чтения [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Представляет положение подписи данных. Чтение [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. Чтение [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. True отображает значение размера пузыря. False скрывает. Чтение **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Представляет поведение отображения имени категории подписи данных указанной диаграммы. True отображает имя категории для подписей данных на диаграмме. False скрывает. Чтение **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Определяет, будет ли подпись данных указанной диаграммы отображаться как выноска данных или как подпись данных. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. True отображает значение ячейки. False скрывает. Чтение **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Представляет поведение отображения линий-указателей подписи данных указанной диаграммы. True отображает линии-указатели. False скрывает. Чтение **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. True, если ключ легенды подписи данных виден. Чтение **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. True отображает процентное значение. False скрывает. Чтение **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Возвращает Boolean, указывающий поведение отображения имени серии для подписей данных на диаграмме. True показывает имя серии. False скрывает. Чтение **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. True отображает процентное значение. False скрывает. Чтение **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Возвращает формат текста диаграммы. Только для чтения [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Возвращает хэш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператором C# lock(). Вызывать напрямую или использовать объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строка и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Запись **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Представляет строку формата для объекта DataLabels. Запись [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Представляет положение подписи данных. Запись [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. Запись [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Представляет поведение отображения значения размера пузыря подписи данных указанной диаграммы. True отображает значение размера пузыря. False скрывает. Запись **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Представляет поведение отображения имени категории подписи данных указанной диаграммы. True отображает имя категории для подписей данных на диаграмме. False скрывает. Запись **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Определяет, будет ли подпись данных указанной диаграммы отображаться как выноска данных или как подпись данных. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. True отображает значение ячейки. False скрывает. Запись **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Представляет поведение отображения линий-указателей подписи данных указанной диаграммы. True отображает линии-указатели. False скрывает. Запись **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Представляет поведение отображения ключа легенды подписи данных указанной диаграммы. True, если ключ легенды подписи данных виден. Запись **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. True отображает процентное значение. False скрывает. Запись **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Устанавливает Boolean, указывающий поведение отображения имени серии для подписей данных на диаграмме. True показывает имя серии. False скрывает. Запись **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Представляет поведение отображения процентного значения подписи данных указанной диаграммы. True отображает процентное значение. False скрывает. Запись **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператором C# lock(). Вызывать напрямую или использовать объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [PVIObject](../../aspose.slides/pviobject/)
* Класс [IDataLabelFormat](../idatalabelformat/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)