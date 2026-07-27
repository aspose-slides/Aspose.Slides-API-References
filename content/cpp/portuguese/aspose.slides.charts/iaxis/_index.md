---
title: IAxis
second_title: Referência da API Aspose.Slides para C++
description: Encapsula o objeto que representa o eixo de um gráfico.
type: docs
weight: 534
url: /pt/aspose.slides.charts/iaxis/
---
## IAxis class

Encapsula o objeto que representa o eixo de um gráfico.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, ainda que de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, ainda que de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Especifica a unidade principal real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) anteriormente para obter o valor real. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Especifica a escala da unidade principal real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) anteriormente para obter o valor real. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Especifica o valor máximo real no eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) anteriormente para obter o valor real. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Especifica a unidade secundária real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) anteriormente para obter o valor real. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Especifica a escala da unidade secundária real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) anteriormente para obter o valor real. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Especifica o valor mínimo real no eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) anteriormente para obter o valor real. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado a categorias. Utilizado somente com séries Histogram ou HistogramPareto. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Representa se o eixo de valores cruza o eixo de categoria entre categorias. Esta propriedade se aplica apenas a eixos de categoria e não se aplica a gráficos 3-D. Leitura **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Especifica a menor unidade de tempo representada no eixo de data. Leitura [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a eixos de categoria. Utilizado somente com séries Histogram ou HistogramPareto. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Especifica o tipo do eixo de categoria. Leitura [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Apenas leitura [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Representa o ponto no eixo onde o eixo perpendicular o cruza. Leitura **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Representa o CrossType no eixo especificado onde o outro eixo o cruza. Leitura [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Especifica o valor de escala das unidades de exibição para o eixo de valor. Leitura [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Representa o formato do eixo. Apenas leitura [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Determina se um eixo tem um título visível. Leitura **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Indica se a unidade principal do eixo é atribuída automaticamente. Leitura **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Indica se o valor máximo é atribuído automaticamente. Leitura **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Indica se a unidade secundária do eixo é atribuída automaticamente. Leitura **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Indica se o valor mínimo é atribuído automaticamente. Leitura **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Especifica o valor automático do bin de overflow. Se falso: use a propriedade OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Especifica o valor automático de espaçamento de rótulos de marcação. Se falso: use a propriedade TickLabelSpacing. Leitura **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Especifica o valor automático de espaçamento de marcas de escala. Se falso: use a propriedade TickMarksSpacing. Leitura **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Especifica o valor automático do bin de underflow. Se falso: use a propriedade UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Representa se o tipo de escala do eixo de valor é logarítmico ou não. Leitura **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Indica se o formato está ligado aos dados de origem. Leitura **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Especifica se o bin de overflow é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de overflow. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Representa se o MS PowerPoint plota pontos de dados do último para o primeiro. Leitura **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Especifica se o bin de underflow é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de underflow. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Representa se o eixo está visível. Leitura **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Especifica a distância dos rótulos ao eixo. Aplicado a eixos de categoria ou data. O valor deve estar entre 0% e 1000%. Leitura **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Representa a base logarítmica. O valor padrão é 10. Leitura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Representa o formato das linhas de grade principais em um eixo de gráfico. Apenas leitura [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Representa o tipo da marca de escala principal para o eixo especificado. Leitura [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Representa as unidades principais para o eixo de data ou valor. Leitura **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Representa a escala da unidade principal para o eixo de data. Leitura [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Representa o valor máximo no eixo de valor. Leitura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Representa o formato das linhas de grade secundárias em um eixo de gráfico. Apenas leitura [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Representa o tipo da marca de escala secundária para o eixo especificado. Leitura [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Representa as unidades secundárias para o eixo de data ou valor. Leitura **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Representa a escala da unidade principal para o eixo de data. Leitura [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Representa o valor mínimo no eixo de valor. Leitura **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Representa a string de formato para os rótulos [Axis](../axis/). Leitura [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Especifica o número de bins quando o valor da propriedade AggregationType está definido como [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a eixos de categoria. Utilizado somente com séries Histogram ou HistogramPareto. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Especifica o valor personalizado do bin de overflow. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como falso e a propriedade IsOverflowBin é verdadeira. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Representa a posição do eixo. Leitura [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Apenas leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Representa se as linhas de grade principais são exibidas. Apenas leitura **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Representa se as linhas de grade secundárias são exibidas. Apenas leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Apenas leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retorna o formato de texto do gráfico. Apenas leitura [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Representa a posição dos rótulos de marcação no eixo especificado. Leitura [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Representa o ângulo de rotação dos rótulos das marcas. Leitura **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. Leitura **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado a eixos de categoria ou série. Leitura **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Obtém o título do eixo. Apenas leitura [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Especifica o valor personalizado do bin de underflow. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como falso e a propriedade IsUnderflowBin é verdadeira. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite a criação de hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analítico à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado a categorias. Utilizado somente com séries Histogram ou HistogramPareto. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Representa se o eixo de valores cruza o eixo de categoria entre categorias. Esta propriedade aplica-se apenas a eixos de categoria e não se aplica a gráficos 3-D. Escrita **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Especifica a menor unidade de tempo representada no eixo de data. Escrita [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a eixos de categoria. Utilizado somente com séries Histogram ou HistogramPareto. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Especifica o tipo do eixo de categoria. Escrita [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Representa o ponto no eixo onde o eixo perpendicular o cruza. Escrita **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Representa o CrossType no eixo especificado onde o outro eixo o cruza. Escrita [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Especifica o valor de escala das unidades de exibição para o eixo de valor. Escrita [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Determina se um eixo tem um título visível. Escrita **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Indica se a unidade principal do eixo é atribuída automaticamente. Escrita **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Indica se o valor máximo é atribuído automaticamente. Escrita **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Indica se a unidade secundária do eixo é atribuída automaticamente. Escrita **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Indica se o valor mínimo é atribuído automaticamente. Escrita **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Especifica o valor automático do bin de overflow. Se falso: use a propriedade OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Especifica o valor automático de espaçamento de rótulos de marcação. Se falso: use a propriedade TickLabelSpacing. Escrita **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Especifica o valor automático de espaçamento de marcas de escala. Se falso: use a propriedade TickMarksSpacing. Escrita **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Especifica o valor automático do bin de underflow. Se falso: use a propriedade UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Representa se o tipo de escala do eixo de valor é logarítmico ou não. Escrita **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Indica se o formato está ligado aos dados de origem. Escrita **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Especifica se o bin de overflow é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de overflow. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Representa se o MS PowerPoint plota pontos de dados do último para o primeiro. Escrita **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Especifica se o bin de underflow é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de underflow. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Representa se o eixo está visível. Escrita **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Especifica a distância dos rótulos ao eixo. Aplicado a eixos de categoria ou data. O valor deve estar entre 0% e 1000%. Escrita **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Representa a base logarítmica. O valor padrão é 10. Escrita **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Representa o tipo da marca de escala principal para o eixo especificado. Escrita [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Representa as unidades principais para o eixo de data ou valor. Escrita **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Representa a escala da unidade principal para o eixo de data. Escrita [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Representa o valor máximo no eixo de valor. Escrita **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Representa o tipo da marca de escala secundária para o eixo especificado. Escrita [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Representa as unidades secundárias para o eixo de data ou valor. Escrita **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Representa a escala da unidade principal para o eixo de data. Escrita [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Representa o valor mínimo no eixo de valor. Escrita **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Representa a string de formato para os rótulos [Axis](../axis/). Escrita [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Especifica o número de bins quando o valor da propriedade AggregationType está definido como [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a eixos de categoria. Utilizado somente com séries Histogram ou HistogramPareto. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Especifica o valor personalizado do bin de overflow. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como falso e a propriedade IsOverflowBin é verdadeira. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Representa a posição do eixo. Escrita [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Representa a posição dos rótulos de marcação no eixo especificado. Escrita [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Representa o ângulo de rotação dos rótulos das marcas Escrita **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. Escrita **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado a eixos de categoria ou série. Escrita **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Especifica o valor personalizado do bin de underflow. Se falso: use a propriedade UnderflowBin. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Define a propriedade IAxis::get(set)_CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver Também

* Classe [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)