---
title: ITrendline
second_title: Справочник API Aspose.Slides для C++
description: Класс представляет линию тренда серии диаграммы
type: docs
weight: 1223
url: /ru/aspose.slides.charts/itrendline/
---
## ITrendline класс

Класс представляет линию тренда серии диаграммы

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Методы

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Инициализирует TextFrameForOverriding текстом из параметра \"text\". Если TextFrameForOverriding уже инициализирован, то просто изменяет его текст. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **double** [get_Backward](./get_backward/)() | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда простирается до данных серии, для которой построен тренд. На диаграммах рассеяния и нерассеяния значение должно быть неотрицательным. Чтение **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и значение R-квадрат). Чтение **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же метке, что и уравнение). Чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Представляет формат линии тренда. Чтение [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда простирается после данных серии, для которой построен тренд. На диаграммах рассеяния и нерассеяния значение должно быть неотрицательным. Чтение **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Указывает значение, где линия тренда пересекает ось Y. Это свойство поддерживается только для типов тренда exp, linear или poly. Чтение **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Указывает порядок полиномиальной линии тренда. Игнорируется для других типов линий тренда. Значение должно быть от 2 до 6. Чтение **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Указывает период линии тренда для скользящего среднего. Игнорируется для других вариантов линии тренда. Значение должно быть от 2 до 255. Чтение **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Представляет элемент легенды, связанный с этой линией тренда. Только для чтения [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Возвращает формат текста диаграммы. Только для чтения [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Может содержать форматированный текст. Если это свойство не равно null, то значение форматированного текста переопределяет автоматически сгенерированный текст. Автосгенерированный текст является неявным свойством подписи данных, подписи единиц отображения оси значений, названия оси, названия диаграммы, подписи линии тренда. Автосгенерированный текст форматируется с помощью свойства [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Только для чтения [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Получает имя линии тренда. Чтение [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Получает тип линии тренда. Чтение [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со ссылкой (nullptr). |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [set_Backward](./set_backward/)(**double**) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда простирается до данных серии, для которой построен тренд. На диаграммах рассеяния и нерассеяния значение должно быть неотрицательным. Запись **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и значение R-квадрат). Запись **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же метке, что и уравнение). Запись **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Представляет формат линии тренда. Запись [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда простирается после данных серии, для которой построен тренд. На диаграммах рассеяния и нерассеяния значение должно быть неотрицательным. Запись **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Указывает значение, где линия тренда пересекает ось Y. Это свойство поддерживается только для типов тренда exp, linear или poly. Запись **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Указывает порядок полиномиальной линии тренда. Игнорируется для других типов линий тренда. Значение должно быть от 2 до 6. Запись **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Указывает период линии тренда для скользящего среднего. Игнорируется для других вариантов линии тренда. Значение должно быть от 2 до 255. Запись **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Устанавливает имя линии тренда. Запись [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Устанавливает тип линии тренда. Запись [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не общий). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IOverridableText](../ioverridabletext/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)