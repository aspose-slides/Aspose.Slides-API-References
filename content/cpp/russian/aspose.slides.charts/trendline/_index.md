---
title: Trendline
second_title: Aspose.Slides для C++ справка API
description: Класс представляет линию тренда серии диаграммы
type: docs
weight: 1366
url: /ru/aspose.slides.charts/trendline/
---
## Класс Trendline

Класс представляет линию тренда серии диаграммы

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Инициализирует TextFrameForOverriding текстом из параметра \"text\". Если TextFrameForOverriding уже инициализирован, то просто изменяет его текст. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **double** [get_Backward](./get_backward/)() override | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается до данных серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть любым неотрицательным. Читается **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Возвращает родительскую диаграмму. Только для чтения [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и Rsquaredvalue). Читается **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же метке, что и уравнение). Читается **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Представляет формат линии тренда. Читается [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается после данных серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть любым неотрицательным. Читается **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Указывает значение, где линия тренда пересекает ось y. Это свойство поддерживается только для типов тренда exp, linear или poly. Читается **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Указывает порядок полиномиальной линии тренда. Игнорируется для других типов линий тренда. Значение должно быть от 2 до 6. Читается **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Указывает период линии тренда для скользящего среднего. Игнорируется для других вариантов линий тренда. Значение должно быть от 2 до 255. Читается **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Представляет запись легенды, связанную с этой линией тренда. Только для чтения [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Возвращает текстовый формат. Только для чтения [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Может содержать текст с расширенным форматированием. Если это свойство не равно null, то значение отформатированного текста переопределяет автоматически сгенерированный текст метки данных. Авто-сгенерированный текст метки данных — это текст, управляемый свойствами ShowSeriesName, ShowValue, … и форматируемый свойством TextFormatManager.TextFormat. Только для чтения [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Получает имя линии тренда. Читается [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Получает тип линии тренда. Читается [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| void [set_Backward](./set_backward/)(**double**) override | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается до данных серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть любым неотрицательным. Записывается **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и Rsquaredvalue). Записывается **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же метке, что и уравнение). Записывается **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Представляет формат линии тренда. Записывается [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается после данных серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть любым неотрицательным. Записывается **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Указывает значение, где линия тренда пересекает ось y. Это свойство поддерживается только для типов тренда exp, linear или poly. Записывается **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Указывает порядок полиномиальной линии тренда. Игнорируется для других типов линий тренда. Значение должно быть от 2 до 6. Записывается **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Указывает период линии тренда для скользящего среднего. Игнорируется для других вариантов линий тренда. Значение должно быть от 2 до 255. Записывается **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Устанавливает имя линии тренда. Записывается [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Устанавливает тип линии тренда. Записывается [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [DomObject](../../aspose.slides/domobject/)
* Класс [ITrendline](../itrendline/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)