---
title: Axis
second_title: Справочник API Aspose.Slides для C++
description: Инкапсулирует объект, представляющий ось диаграммы.
type: docs
weight: 14
url: /ru/aspose.slides.charts/axis/
---
## Axis class

Инкапсулирует объект, представляющий ось диаграммы.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Указывает фактическую основную единицу оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить реальное значение. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Указывает фактический масштаб основной единицы оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить реальное значение. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Указывает фактическое максимальное значение оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить реальное значение. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Указывает фактическую вспомогательную единицу оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить реальное значение. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Указывает фактический масштаб вспомогательной единицы оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить реальное значение. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Указывает фактическое минимальное значение оси. Сначала вызовите метод [IChart::ValidateChartLayout](../ichart/validatechartlayout/), чтобы получить реальное значение. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Представляет тип агрегации категориальной оси (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Определяет, пересекает ли ось значений ось категории между категориями. Это свойство применяется только к категориальным осям и не действует для 3-D диаграмм. Читается как **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Указывает наименьшую единицу времени, представленную на оси дат. Читает [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Указывает ширину бина, когда свойство AggregationType имеет значение [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Указывает тип категориальной оси. Читает [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Возвращает родительскую диаграмму. Только для чтения [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Представляет точку на оси, где пересекает её перпендикулярная ось. Читается как **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Представляет тип пересечения (CrossType) на указанной оси, где она пересекается с другой осью. Читает [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Указывает коэффициент масштабирования отображаемых единиц для оси значений. Читает [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Представляет формат оси. Только для чтения [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Определяет, имеет ли ось видимый заголовок. Читает **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Указывает, назначается ли основная единица оси автоматически. Читает **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Указывает, назначается ли максимальное значение автоматически. Читает **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Указывает, назначается ли вспомогательная единица оси автоматически. Читает **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Указывает, назначается ли минимальное значение автоматически. Читает **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Указывает автоматическое значение переполнения бина. Если false: используйте свойство OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Указывает автоматическое значение интервала меток делений. Если false: используйте свойство TickLabelSpacing. Читает **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Указывает автоматическое значение интервала делений. Если false: используйте свойство TickMarksSpacing. Читает **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Указывает автоматическое значение недоучетного бина. Если false: используйте свойство UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Определяет, является ли тип масштабирования оси значений логарифмическим. Читает **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Указывает, связан ли формат с исходными данными. Читает **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Указывает, применён ли переполненный бин. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполнения бина. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Определяет, выводит ли MS PowerPoint точки данных от последней к первой. Читает **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Указывает, применён ли недоучетный бин. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недоучетного бина. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Определяет, видна ли ось. Читает **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Указывает расстояние меток от оси. Применяется к категориальной или датовой оси. Значение должно быть от 0 % до 1000 %. Читает **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Представляет логарифмическую основу. Значение по умолчанию — 10. Читает **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Представляет формат основных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Представляет тип основной метки деления для указанной оси. Читает [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Представляет основные единицы для датовой или оси значений. Читает **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Представляет масштаб основной единицы для датовой оси. Читает [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Представляет максимальное значение на оси значений. Читает **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Представляет формат вспомогательных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Представляет тип вспомогательной метки деления для указанной оси. Читает [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Представляет вспомогательные единицы для датовой или оси значений. Читает **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Представляет масштаб основной единицы для датовой оси. Читает [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Представляет минимальное значение на оси значений. Читает **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Представляет строку формата для меток [Axis](./). Читает [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Указывает количество бинов, когда свойство AggregationType имеет значение [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Указывает пользовательское значение переполненного бина. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Представляет положение оси. Читает [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Чтобы скрыть основную линию сетки, установите [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() в [FillType::NoFill](../../aspose.slides/filltype/). Только для чтения **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Чтобы скрыть вспомогательную линию сетки, установите [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() в [FillType::NoFill](../../aspose.slides/filltype/). Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Представляет формат текста. Только для чтения [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Представляет положение меток отметок делений на указанной оси. Читает [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Представляет угол вращения меток делений. Читает **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Указывает, сколько меток делений пропускать между отрисованными метками. Применяется к категориальной или серии оси. Читает **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Указывает, сколько делений пропускать перед отрисовкой следующего. Применяется к категориальной или серии оси. Читает **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Получает заголовок оси. Только для чтения [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Указывает пользовательское значение недоучетного бина. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает общий счётчик ссылок на указанное значение. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Представляет тип агрегации категориальной оси (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Определяет, пересекает ли ось значений ось категории между категориями. Это свойство применяется только к категориальным осям и не действует для 3-D диаграмм. Записывается как **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Указывает наименьшую единицу времени, представленную на оси дат. Записывается [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Указывает ширину бина, когда свойство AggregationType имеет значение [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Указывает тип категориальной оси. Записывается [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Представляет точку на оси, где её пересекает перпендикулярная ось. Записывается **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Представляет тип пересечения (CrossType) на указанной оси, где она пересекает другую ось. Записывается [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Указывает коэффициент масштабирования отображаемых единиц для оси значений. Записывается [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Определяет, имеет ли ось видимый заголовок. Записывается **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Указывает, назначается ли основная единица оси автоматически. Записывается **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Указывает, назначается ли максимальное значение автоматически. Записывается **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Указывает, назначается ли вспомогательная единица оси автоматически. Записывается **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Указывает, назначается ли минимальное значение автоматически. Записывается **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Указывает автоматическое значение переполнения бина. Если false: используйте свойство OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Указывает автоматическое значение интервала меток делений. Если false: используйте свойство TickLabelSpacing. Записывается **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Указывает автоматическое значение интервала делений. Если false: используйте свойство TickMarksSpacing. Записывается **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Указывает автоматическое значение недоучетного бина. Если false: используйте свойство UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Определяет, является ли тип масштабирования оси значений логарифмическим. Записывается **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Указывает, связан ли формат с исходными данными. Записывается **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Указывает, применён ли переполненный бин. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполнения бина. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Определяет, выводит ли MS PowerPoint точки данных от последней к первой. Записывается **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Указывает, применён ли недоучетный бин. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недоучетного бина. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Определяет, видна ли ось. Записывается **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Указывает расстояние меток от оси. Применяется к категориальной или датовой оси. Значение должно быть от 0 % до 1000 %. Записывается **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Представляет логарифмическую основу. Значение по умолчанию — 10. Записывается **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Представляет тип основной метки деления для указанной оси. Записывается [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Представляет основные единицы для датовой или оси значений. Записывается **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Представляет масштаб основной единицы для датовой оси. Записывается [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Представляет максимальное значение на оси значений. Записывается **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Представляет тип вспомогательной метки деления для указанной оси. Записывается [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Представляет вспомогательные единицы для датовой или оси значений. Записывается **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Представляет масштаб основной единицы для датовой оси. Записывается [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Представляет минимальное значение на оси значений. Записывается **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Представляет строку формата для меток [Axis](./). Записывается [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Указывает количество бинов, когда свойство AggregationType имеет значение [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Указывает пользовательское значение переполненного бина. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Представляет положение оси. Записывается [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Представляет положение меток отметок делений на указанной оси. Записывается [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Представляет угол вращения меток делений. Записывается **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Указывает, сколько меток делений пропускать между отрисованными метками. Применяется к категориальной или серии оси. Записывается **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Указывает, сколько делений пропускать перед отрисовкой следующего. Применяется к категориальной или серии оси. Записывается **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Указывает пользовательское значение недоучетного бина. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Устанавливает свойство IAxis::get(set)_CategoryAxisType значением, автоматически определяемым на основе данных оси. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение общего счётчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Очищает все внутренние структуры данных. |

## Смотрите также

* Класс [DomObject](../../aspose.slides/domobject/)
* Класс [IAxis](../iaxis/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)