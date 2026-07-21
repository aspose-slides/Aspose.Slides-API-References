---
title: ILegend
second_title: Aspose.Slides для C++ справочник API
description: Представляет свойства легенды диаграммы.
type: docs
weight: 1080
url: /ru/aspose.slides.charts/ilegend/
---
## ILegend класс

Представляет свойства легенды диаграммы.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Указывает фактическую высоту элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед этим, чтобы получить реальные значения. Читать **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Указывает фактическую ширину элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед этим, чтобы получить реальные значения. Читать **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Указывает фактическое положение по оси X (слева) элемента диаграммы относительно верхнего левого угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед этим, чтобы получить реальные значения. Читать **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Указывает фактическую верхнюю позицию элемента диаграммы относительно верхнего левого угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) перед этим, чтобы получить реальные значения. Читать **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Получает верхнюю позицию элемента диаграммы как долю от высоты диаграммы. Только для чтения **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Получает элементы легенды. Только для чтения [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Получает свойства элемента легенды, соответствующего точке данных в диаграмме по указанному индексу. Для типов диаграмм: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, точка данных берётся из первой серии. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Возвращает формат легенды. Только для чтения [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Указывает высоту элемента диаграммы как долю от высоты диаграммы. Читать **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Определяет, допускается ли наложение других элементов диаграммы на легенду. Читать **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Указывает позицию легенды на диаграмме. Значения X, Y, Width, Heigt, не являющиеся NaN, переопределяют действие этого свойства. Чтение [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Получает правую границу элемента диаграммы как долю от ширины диаграммы. Только для чтения **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Возвращает текстовый формат диаграммы. Только для чтения [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Указывает ширину элемента диаграммы как долю от ширины диаграммы. Читать **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Указывает положение по оси X (слева) элемента диаграммы как долю от ширины диаграммы. Читать **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Указывает верхнюю позицию элемента диаграммы как долю от высоты диаграммы. Читать **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Указывает высоту элемента диаграммы как долю от высоты диаграммы. Записать **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Определяет, допускается ли наложение других элементов диаграммы на легенду. Записать **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Указывает позицию легенды на диаграмме. Значения X, Y, Width, Heigt, не являющиеся NaN, переопределяют действие этого свойства. Записать [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Указывает ширину элемента диаграммы как долю от ширины диаграммы. Записать **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Указывает положение по оси X (слева) элемента диаграммы как долю от ширины диаграммы. Записать **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Указывает верхнюю позицию элемента диаграммы как долю от высоты диаграммы. Записать **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в режим слабых ссылок. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ILayoutable](../ilayoutable/)
* Класс [IFormattedTextContainer](../iformattedtextcontainer/)
* Класс [IActualLayout](../iactuallayout/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)