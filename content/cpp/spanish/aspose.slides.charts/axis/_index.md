---
title: Axis
second_title: Referencia de API de Aspose.Slides para C++
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
weight: 14
url: /es/aspose.slides.charts/axis/
---
## Axis clase

Encapsula el objeto que representa el eje de un gráfico.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaNs se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaNs se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Especifica la unidad mayor actual del eje. Llame previamente al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) para obtener el valor real. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Especifica la escala de la unidad mayor actual del eje. Llame previamente al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) para obtener el valor real. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Especifica el valor máximo actual del eje. Llame previamente al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) para obtener el valor real. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Especifica la unidad menor actual del eje. Llame previamente al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) para obtener el valor real. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Especifica la escala de la unidad menor actual del eje. Llame previamente al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) para obtener el valor real. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Especifica el valor mínimo actual del eje. Llame previamente al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) para obtener el valor real. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Representa el tipo de agregación del eje de categoría (agrupación). Aplicado a categorías. Solo se usa con series Histogram o HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad solo se aplica a ejes de categoría y no a gráficos 3D. Lectura **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Especifica la unidad de tiempo más pequeña que se representa en el eje de fechas. Lectura [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType se establece en [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a ejes de categoría. Solo se usa con series Histogram o HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Especifica el tipo del eje de categoría. Lectura [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Devuelve el gráfico padre. Solo lectura [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Representa el punto del eje donde el eje perpendicular lo cruza. Lectura **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Representa el CrossType en el eje especificado donde el otro eje lo cruza. Lectura [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Especifica el valor de escala de las unidades de visualización para el eje de valores. Lectura [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Representa el formato del eje. Solo lectura [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Determina si el eje tiene un título visible. Lectura **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Indica si la unidad mayor del eje se asigna automáticamente. Lectura **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Indica si el valor máximo se asigna automáticamente. Lectura **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Indica si la unidad menor del eje se asigna automáticamente. Lectura **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Indica si el valor mínimo se asigna automáticamente. Lectura **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Especifica el valor automático del contenedor de desbordamiento. Si es false: use la propiedad OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Especifica el valor automático del espacio entre etiquetas de marcas. Si es false: use la propiedad TickLabelSpacing. Lectura **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Especifica el valor automático del espacio entre marcas de graduación. Si es false: use la propiedad TickMarksSpacing. Lectura **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Especifica el valor automático del contenedor de subdesbordamiento. Si es false: use la propiedad UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Indica si el formato está vinculado a los datos de origen. Lectura **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Especifica si se aplica el contenedor de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Representa si MS PowerPoint traza los puntos de datos de último a primero. Lectura **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Especifica si se aplica el contenedor de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subdesbordamiento. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Representa si el eje es visible. Lectura **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Especifica la distancia de las etiquetas al eje. Aplicado a ejes de categoría o de fecha. El valor debe estar entre 0% y 1000%. Lectura **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Representa la base logarítmica. El valor predeterminado es 10. Lectura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Representa el formato de las líneas de cuadrícula mayores en un eje de gráfico. Solo lectura [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Representa el tipo de marca de graduación mayor para el eje especificado. Lectura [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Representa las unidades mayores para el eje de fecha o de valor. Lectura **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Representa la escala de la unidad mayor para el eje de fecha. Lectura [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Representa el valor máximo en el eje de valor. Lectura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Representa el formato de las líneas de cuadrícula menores en un eje de gráfico. Solo lectura [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Representa el tipo de marca de graduación menor para el eje especificado. Lectura [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Representa las unidades menores para el eje de fecha o de valor. Lectura **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Representa la escala de la unidad mayor para el eje de fecha. Lectura [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Representa el valor mínimo en el eje de valor. Lectura **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Representa la cadena de formato para las etiquetas [Axis](./). Lectura [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Especifica el número de contenedores cuando el valor de la propiedad AggregationType se establece en [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a ejes de categoría. Solo se usa con series Histogram o HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Especifica el valor personalizado del contenedor de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin se establece en false y la propiedad IsOverflowBin es true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Representa la posición del eje. Lectura [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Para ocultar la línea de cuadrícula mayor, establezca [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() a [FillType::NoFill](../../aspose.slides/filltype/). Solo lectura **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Para ocultar la línea de cuadrícula menor, establezca [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() a [FillType::NoFill](../../aspose.slides/filltype/). Solo lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Representa el formato del texto. Solo lectura [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Lectura [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Representa el ángulo de rotación de las etiquetas de marcas. Lectura **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Especifica cuántas etiquetas de marcas se deben omitir entre las etiquetas que se dibujan. Aplicado a ejes de categoría o de serie. Lectura **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Especifica cuántas marcas de graduación se deben omitir antes de dibujar la siguiente. Aplicado a ejes de categoría o de serie. Lectura **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Obtiene el título del eje. Solo lectura [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Especifica el valor personalizado del contenedor de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin se establece en false y la propiedad IsUnderflowBin es true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Representa el tipo de agregación del eje de categoría (agrupación). Aplicado a categorías. Solo se usa con series Histogram o HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Representa si el eje de valores cruza el eje de categorías entre categorías. Esta propiedad solo se aplica a ejes de categoría y no a gráficos 3D. Escritura **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Especifica la unidad de tiempo más pequeña que se representa en el eje de fechas. Escritura [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Especifica el ancho del contenedor cuando el valor de la propiedad AggregationType se establece en [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a ejes de categoría. Solo se usa con series Histogram o HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Especifica el tipo del eje de categoría. Escritura [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Representa el punto del eje donde el eje perpendicular lo cruza. Escritura **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Representa el CrossType en el eje especificado donde el otro eje lo cruza. Escritura [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Especifica el valor de escala de las unidades de visualización para el eje de valores. Escritura [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Determina si un eje tiene un título visible. Escritura **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Indica si la unidad mayor del eje se asigna automáticamente. Escritura **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Indica si el valor máximo se asigna automáticamente. Escritura **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Indica si la unidad menor del eje se asigna automáticamente. Escritura **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Indica si el valor mínimo se asigna automáticamente. Escritura **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Especifica el valor automático del contenedor de desbordamiento. Si es false: use la propiedad OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Especifica el valor automático del espacio entre etiquetas de marcas. Si es false: use la propiedad TickLabelSpacing. Escritura **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Especifica el valor automático del espacio entre marcas de graduación. Si es false: use la propiedad TickMarksSpacing. Escritura **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Especifica el valor automático del contenedor de subdesbordamiento. Si es false: use la propiedad UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Representa si el tipo de escala del eje de valores es logarítmico o no. Escritura **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Indica si el formato está vinculado a datos de origen. Escritura **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Especifica si se aplica el contenedor de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del contenedor de desbordamiento. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Representa si MS PowerPoint traza los puntos de datos de último a primero. Escritura **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Especifica si se aplica el contenedor de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del contenedor de subdesbordamiento. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Representa si el eje es visible. Escritura **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Especifica la distancia de las etiquetas al eje. Aplicado a ejes de categoría o de fecha. El valor debe estar entre 0% y 1000%. Escritura **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Representa la base logarítmica. El valor predeterminado es 10. Escritura **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Representa el tipo de marca de graduación mayor para el eje especificado. Escritura [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Representa las unidades mayores para el eje de fecha o de valor. Escritura **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Representa la escala de la unidad mayor para el eje de fecha. Escritura [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Representa el valor máximo en el eje de valor. Escritura **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Representa el tipo de marca de graduación menor para el eje especificado. Escritura [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Representa las unidades menores para el eje de fecha o de valor. Escritura **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Representa la escala de la unidad mayor para el eje de fecha. Escritura [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Representa el valor mínimo en el eje de valor. Escritura **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Representa la cadena de formato para las etiquetas [Axis](./). Escritura [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Especifica el número de contenedores cuando el valor de la propiedad AggregationType se establece en [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a ejes de categoría. Solo se usa con series Histogram o HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Especifica el valor personalizado del contenedor de desbordamiento. Se aplica cuando la propiedad IsAutomaticOverflowBin se establece en false y la propiedad IsOverflowBin es true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Representa la posición del eje. Escritura [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Escritura [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Representa el ángulo de rotación de las etiquetas de marcas. Escritura **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Especifica cuántas etiquetas de marcas se deben omitir entre las etiquetas que se dibujan. Aplicado a ejes de categoría o de serie. Escritura **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Especifica cuántas marcas de graduación se deben omitir antes de dibujar la siguiente. Aplicado a ejes de categoría o de serie. Escritura **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Especifica el valor personalizado del contenedor de subdesbordamiento. Se aplica cuando la propiedad IsAutomaticUnderflowBin se establece en false y la propiedad IsUnderflowBin es true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Establece la propiedad IAxis::get(set)_CategoryAxisType con un valor determinado automáticamente en función de los datos del eje. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [DomObject](../../aspose.slides/domobject/)
* Clase [IAxis](../iaxis/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)