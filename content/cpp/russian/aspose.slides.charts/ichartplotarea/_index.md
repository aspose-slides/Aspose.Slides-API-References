---
title: IChartPlotArea
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства заголовка диаграммы.
type: docs
weight: 794
url: /ru/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea класс

Представляет свойства заголовка диаграммы.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Указывает фактическую высоту элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ранее, чтобы получить реальные значения. Читает **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Указывает фактическую ширину элемента диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ранее, чтобы получить реальные значения. Читает **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Указывает фактическое положение по оси x (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ранее, чтобы получить реальные значения. Читает **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ранее, чтобы получить реальные значения. Читает **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Возвращает верхнюю позицию элемента диаграммы как долю от высоты диаграммы. Только для чтения **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Возвращает формат области построения. Только для чтения [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Указывает высоту элемента диаграммы как долю от высоты диаграммы. Читает **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | Если расположение области построения задано вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). Читает [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Возвращает правую позицию элемента диаграммы как долю от ширины диаграммы. Только для чтения **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Указывает ширину элемента диаграммы как долю от ширины диаграммы. Читает **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Указывает положение по оси x (слева) элемента диаграммы как долю от ширины диаграммы. Читает **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Указывает верхнюю позицию элемента диаграммы как долю от высоты диаграммы. Читает **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеши пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Указывает высоту элемента диаграммы как долю от высоты диаграммы. Записывает **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | Если расположение области построения задано вручную, это свойство указывает, следует ли размещать область построения по её внутренней части (не включая оси и подписи осей) или по внешней части (включая оси и подписи осей). Записывает [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Указывает ширину элемента диаграммы как долю от ширины диаграммы. Записывает **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Указывает положение по оси x (слева) элемента диаграммы как долю от ширины диаграммы. Записывает **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Указывает верхнюю позицию элемента диаграммы как долю от высоты диаграммы. Записывает **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент в виде слабого указателя (а не общего). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [ILayoutable](../ilayoutable/)
* Класс [IActualLayout](../iactuallayout/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)