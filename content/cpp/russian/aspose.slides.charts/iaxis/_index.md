---
title: IAxis
second_title: Справочник API Aspose.Slides для C++
description: Инкапсулирует объект, представляющий ось диаграммы.
type: docs
weight: 534
url: /ru/aspose.slides.charts/iaxis/
---
## IAxis класс

Encapsulates the object that represents a chart's axis.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Указывает фактическую основную единицу оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить фактическое значение. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Указывает фактический масштаб основной единицы оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить фактическое значение. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Указывает фактическое максимальное значение на оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить фактическое значение. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Указывает фактическую вспомогательную единицу оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить фактическое значение. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Указывает фактический масштаб вспомогательной единицы оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить фактическое значение. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Указывает фактическое минимальное значение на оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить фактическое значение. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Представляет тип агрегации оси категорий (группировка). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Читается как **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Указывает наименьшую единицу времени, представляемую на оси даты. Читается как [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Указывает ширину блока, когда значение свойства AggregationType установлено в [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Указывает тип оси категорий. Читается как [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Представляет точку на оси, где перпендикулярная ось её пересекает. Читается как **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Представляет CrossType на указанной оси, где другая ось её пересекает. Читается как [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Указывает масштабирующее значение единиц отображения для оси значений. Читается как [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Представляет формат оси. Только для чтения [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Определяет, имеет ли ось видимый заголовок. Читается как **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Указывает, присваивается ли основная единица оси автоматически. Читается как **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Указывает, присваивается ли максимальное значение автоматически. Читается как **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Указывает, присваивается ли вспомогательная единица оси автоматически. Читается как **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Указывает, присваивается ли минимальное значение автоматически. Читается как **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Указывает автоматическое значение переполнения блока. Если false: используйте свойство OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Указывает автоматическое значение интервала меток делений. Если false: используйте свойство TickLabelSpacing. Читается как **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Указывает автоматическое значение интервала делений. Если false: используйте свойство TickMarksSpacing. Читается как **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Указывает автоматическое значение недо заполнения блока. Если false: используйте свойство UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Указывает, является ли тип масштабирования оси значений логарифмическим. Читается как **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Указывает, связаны ли формат и исходные данные. Читается как **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Указывает, применён ли блок переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для корректировки значения блока переполнения. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Указывает, отображает ли MS PowerPoint точки данных от последней к первой. Читается как **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Указывает, применён ли блок недо заполнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для корректировки значения блока недо заполнения. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Указывает, видна ли ось. Читается как **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Указывает расстояние меток от оси. Применяется к оси категорий или даты. Значение должно быть от 0% до 1000%. Читается как **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Представляет логарифмическую основу. Значение по умолчанию — 10. Читается как **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Представляет формат основных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Представляет тип основных делений для указанной оси. Читается как [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Представляет основные единицы для оси даты или значений. Читается как **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Представляет масштаб основной единицы для оси даты. Читается как [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Представляет максимальное значение на оси значений. Читается как **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Представляет формат вспомогательных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Представляет тип вспомогательных делений для указанной оси. Читается как [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Представляет вспомогательные единицы для оси даты или значений. Читается как **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Представляет масштаб основной единицы для оси даты. Читается как [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Представляет минимальное значение на оси значений. Читается как **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Представляет строку формата для меток [Axis](../axis/). Читается как [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Указывает количество блоков, когда значение свойства AggregationType установлено в [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Указывает пользовательское значение блока переполнения. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и IsOverflowBin равно true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Представляет позицию оси. Читается как [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Указывает, отображаются ли основные линии сетки. Только для чтения **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Указывает, отображаются ли вспомогательные линии сетки. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Возвращает текстовый формат диаграммы. Только для чтения [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Представляет позицию меток делений на указанной оси. Читается как [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Представляет угол поворота меток делений. Читается как **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Указывает, сколько меток делений пропускать между отрисовываемыми метками. Читается как **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Указывает, сколько делений пропускать перед отрисовкой следующего. Применяется к оси категорий или серий. Читается как **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Получает заголовок оси. Только для чтения [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Указывает пользовательское значение блока недо заполнения. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и IsUnderflowBin равно true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хэшировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызовите напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать построение подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать построение подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает значение типа со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Представляет тип агрегации оси категорий (группировка). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Записать **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Указывает наименьшую единицу времени, представляемую на оси даты. Записать [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Указывает ширину блока, когда значение свойства AggregationType установлено в [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Указывает тип оси категорий. Записать [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Представляет точку на оси, где перпендикулярная ось её пересекает. Записать **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Представляет CrossType на указанной оси, где другая ось её пересекает. Записать [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Указывает масштабирующее значение единиц отображения для оси значений. Записать [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Определяет, имеет ли ось видимый заголовок. Записать **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Указывает, присваивается ли основная единица оси автоматически. Записать **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Указывает, присваивается ли максимальное значение автоматически. Записать **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Указывает, присваивается ли вспомогательная единица оси автоматически. Записать **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Указывает, присваивается ли минимальное значение автоматически. Записать **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Указывает автоматическое значение переполнения блока. Если false: используйте свойство OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Указывает автоматическое значение интервала меток делений. Если false: используйте свойство TickLabelSpacing. Записать **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Указывает автоматическое значение интервала делений. Если false: используйте свойство TickMarksSpacing. Записать **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Указывает автоматическое значение блока недо заполнения. Если false: используйте свойство UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Указывает, является ли тип масштабирования оси значений логарифмическим. Записать **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Указывает, связаны ли формат и исходные данные. Записать **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Указывает, применён ли блок переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для корректировки значения блока переполнения. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Указывает, отображает ли MS PowerPoint точки данных от последней к первой. Записать **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Указывает, применён ли блок недо заполнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для корректировки значения блока недо заполнения. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Указывает, видна ли ось. Записать **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Указывает расстояние меток от оси. Применяется к оси категорий или даты. Значение должно быть от 0% до 1000%. Записать **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Представляет логарифмическую основу. Значение по умолчанию — 10. Записать **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Представляет тип основных делений для указанной оси. Записать [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Представляет основные единицы для оси даты или значений. Записать **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Представляет масштаб основной единицы для оси даты. Записать [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Представляет максимальное значение на оси значений. Записать **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Представляет тип вспомогательных делений для указанной оси. Записать [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Представляет вспомогательные единицы для оси даты или значений. Записать **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Представляет масштаб основной единицы для оси даты. Записать [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Представляет минимальное значение на оси значений. Записать **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Представляет строку формата для меток [Axis](../axis/). Записать [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Указывает количество блоков, когда значение свойства AggregationType установлено в [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Указывает пользовательское значение блока переполнения. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и IsOverflowBin равно true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Представляет позицию оси. Записать [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Представляет позицию меток делений на указанной оси. Записать [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Представляет угол поворота меток делений. Записать **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Указывает, сколько меток делений пропускать между отрисовываемыми метками. Записать **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Указывает, сколько делений пропускать перед отрисовкой следующего. Применяется к оси категорий или серий. Записать **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Указывает пользовательское значение блока недо заполнения. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и IsUnderflowBin равно true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Устанавливает свойство IAxis::get(set)_CategoryAxisType значением, автоматически определяемым на основе данных оси. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызовите напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IFormattedTextContainer](../iformattedtextcontainer/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)