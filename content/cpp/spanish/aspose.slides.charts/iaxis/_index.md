---
title: IAxis
second_title: Referencia de API de Aspose.Slides para C++
description: Encapsula el objeto que representa el eje de un gráfico.
type: docs
weight: 534
url: /es/aspose.slides.charts/iaxis/
---
## IAxis clase

Encapsula el objeto que representa el eje de un gráfico.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Especifica la unidad mayor real del eje. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obtener el valor real. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Especifica la escala de la unidad mayor real del eje. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obtener el valor real. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Especifica el valor máximo real del eje. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obtener el valor real. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Especifica la unidad menor real del eje. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obtener el valor real. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Especifica la escala de la unidad menor real del eje. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obtener el valor real. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Especifica el valor mínimo real del eje. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obtener el valor real. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Representa el tipo de agregación del eje de categoría (agrupamiento). Aplicado a la categoría. Sólo se usa con series Histogram o HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Representa si el eje de valores cruza el eje de categoría entre categorías. Esta propiedad solo se aplica a ejes de categoría y no a gráficos 3-D. Lectura **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Especifica la unidad de tiempo más pequeña representada en el eje de fecha. Lectura [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Especifica el ancho del bin cuando la propiedad AggregationType está establecida en [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a ejes de categoría. Sólo se usa con series Histogram o HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Especifica el tipo del eje de categoría. Lectura [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Devuelve el gráfico. Solo lectura [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Representa el punto del eje donde el eje perpendicular lo cruza. Lectura **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Representa el CrossType en el eje especificado donde el otro eje lo cruza. Lectura [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Especifica el valor de escala de las unidades de visualización para el eje de valores. Lectura [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Representa el formato del eje. Solo lectura [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Determina si el eje tiene un título visible. Lectura **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Indica si la unidad mayor del eje se asigna automáticamente. Lectura **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Indica si el valor máximo se asigna automáticamente. Lectura **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Indica si la unidad menor del eje se asigna automáticamente. Lectura **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Indica si el valor mínimo se asigna automáticamente. Lectura **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Especifica el valor automático del bin de desbordamiento. Si es false: usar la propiedad OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Especifica el valor automático de espaciado de etiquetas de marcas. Si es false: usar la propiedad TickLabelSpacing. Lectura **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Especifica el valor automático de espaciado de marcas de graduación. Si es false: usar la propiedad TickMarksSpacing. Lectura **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Especifica el valor automático del bin de subdesbordamiento. Si es false: usar la propiedad UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Representa si el tipo de escala del eje de valores es logarítmico o no. Lectura **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Indica si el formato está vinculado a datos de origen. Lectura **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Especifica si se aplica el bin de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del bin de desbordamiento. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Representa si MS PowerPoint traza los puntos de datos de último a primero. Lectura **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Especifica si se aplica el bin de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del bin de subdesbordamiento. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Representa si el eje es visible. Lectura **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Especifica la distancia de las etiquetas respecto al eje. Aplicado a ejes de categoría o de fecha. El valor debe estar entre 0 % y 1000 %. Lectura **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Representa la base logarítmica. El valor predeterminado es 10. Lectura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Representa el formato de líneas de cuadrícula principales en un eje de gráfico. Solo lectura [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Representa el tipo de marca de graduación principal para el eje especificado. Lectura [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Representa las unidades principales para el eje de fecha o de valor. Lectura **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Representa la escala de la unidad mayor para el eje de fecha. Lectura [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Representa el valor máximo en el eje de valor. Lectura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Representa el formato de líneas de cuadrícula menores en un eje de gráfico. Solo lectura [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Representa el tipo de marca de graduación menor para el eje especificado. Lectura [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Representa las unidades menores para el eje de fecha o de valor. Lectura **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Representa la escala de la unidad mayor para el eje de fecha. Lectura [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Representa el valor mínimo en el eje de valor. Lectura **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Representa la cadena de formato para las etiquetas [Axis](../axis/). Lectura [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Especifica el número de bins cuando la propiedad AggregationType está establecida en [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a ejes de categoría. Sólo se usa con series Histogram o HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Especifica el valor personalizado del bin de desbordamiento. Aplicado cuando la propiedad IsAutomaticOverflowBin es false y IsOverflowBin es true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Representa la posición del eje. Lectura [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Representa si se mostraron las líneas de cuadrícula principales. Solo lectura **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Representa si se mostraron las líneas de cuadrícula menores. Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Devuelve el formato de texto del gráfico. Solo lectura [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Lectura [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Representa el ángulo de rotación de las etiquetas de graduación. Lectura **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Especifica cuántas etiquetas de graduación se omiten entre la etiqueta dibujada. Lectura **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. Aplicado a ejes de categoría o de serie. Lectura **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Obtiene el título del eje. Solo lectura [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Especifica el valor personalizado del bin de subdesbordamiento. Aplicado cuando la propiedad IsAutomaticUnderflowBin es false y IsUnderflowBin es true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# `is`. |
| void [Lock](../../system/object/lock/)() | Implementa la instrucción C# lock() para bloquear. Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Representa el tipo de agregación del eje de categoría (agrupamiento). Aplicado a la categoría. Sólo se usa con series Histogram o HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Representa si el eje de valores cruza el eje de categoría entre categorías. Esta propiedad solo se aplica a ejes de categoría y no a gráficos 3-D. Escritura **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Especifica la unidad de tiempo más pequeña representada en el eje de fecha. Escritura [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Especifica el ancho del bin cuando la propiedad AggregationType está establecida en [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a ejes de categoría. Sólo se usa con series Histogram o HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Especifica el tipo del eje de categoría. Escritura [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Representa el punto del eje donde el eje perpendicular lo cruza. Escritura **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Representa el CrossType en el eje especificado donde el otro eje lo cruza. Escritura [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Especifica el valor de escala de las unidades de visualización para el eje de valores. Escritura [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Determina si el eje tiene un título visible. Escritura **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Indica si la unidad mayor del eje se asigna automáticamente. Escritura **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Indica si el valor máximo se asigna automáticamente. Escritura **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Indica si la unidad menor del eje se asigna automáticamente. Escritura **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Indica si el valor mínimo se asigna automáticamente. Escritura **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Especifica el valor automático del bin de desbordamiento. Si es false: usar la propiedad OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Especifica el valor automático de espaciado de etiquetas de marcas. Si es false: usar la propiedad TickLabelSpacing. Escritura **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Especifica el valor automático de espaciado de marcas de graduación. Si es false: usar la propiedad TickMarksSpacing. Escritura **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Especifica el valor automático del bin de subdesbordamiento. Si es false: usar la propiedad UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Representa si el tipo de escala del eje de valores es logarítmico o no. Escritura **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Indica si el formato está vinculado a datos de origen. Escritura **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Especifica si se aplica el bin de desbordamiento. Use IsAutomaticOverflowBin y OverflowBin para ajustar el valor del bin de desbordamiento. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Representa si MS PowerPoint traza los puntos de datos de último a primero. Escritura **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Especifica si se aplica el bin de subdesbordamiento. Use IsAutomaticUnderflowBin y UnderflowBin para ajustar el valor del bin de subdesbordamiento. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Representa si el eje es visible. Escritura **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Especifica la distancia de las etiquetas respecto al eje. Aplicado a ejes de categoría o de fecha. El valor debe estar entre 0 % y 1000 %. Escritura **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Representa la base logarítmica. El valor predeterminado es 10. Escritura **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Representa el tipo de marca de graduación principal para el eje especificado. Escritura [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Representa las unidades principales para el eje de fecha o de valor. Escritura **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Representa la escala de la unidad mayor para el eje de fecha. Escritura [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Representa el valor máximo en el eje de valor. Escritura **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Representa el tipo de marca de graduación menor para el eje especificado. Escritura [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Representa las unidades menores para el eje de fecha o de valor. Escritura **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Representa la escala de la unidad mayor para el eje de fecha. Escritura [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Representa el valor mínimo en el eje de valor. Escritura **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Representa la cadena de formato para las etiquetas [Axis](../axis/). Escritura [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Especifica el número de bins cuando la propiedad AggregationType está establecida en [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a ejes de categoría. Sólo se usa con series Histogram o HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Especifica el valor personalizado del bin de desbordamiento. Aplicado cuando la propiedad IsAutomaticOverflowBin es false y IsOverflowBin es true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Representa la posición del eje. Escritura [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Representa la posición de las etiquetas de marcas de graduación en el eje especificado. Escritura [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Representa el ángulo de rotación de las etiquetas de graduación. Escritura **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Especifica cuántas etiquetas de graduación se omiten entre la etiqueta dibujada. Escritura **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Especifica cuántas marcas de graduación se omiten antes de dibujar la siguiente. Aplicado a ejes de categoría o de serie. Escritura **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Especifica el valor personalizado del bin de subdesbordamiento. Aplicado cuando la propiedad IsAutomaticUnderflowBin es false y IsUnderflowBin es true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Establece la propiedad IAxis::get(set)_CategoryAxisType con un valor determinado automáticamente según los datos del eje. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Asigna el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la instrucción C# lock() para desbloquear. Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Class [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)