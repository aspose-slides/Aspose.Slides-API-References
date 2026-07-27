---
title: Axis
second_title: Referência da API Aspose.Slides para C++
description: Encapsula o objeto que representa o eixo de um gráfico.
type: docs
weight: 14
url: /pt/aspose.slides.charts/axis/
---
## Classe Axis

Encapsula o objeto que representa o eixo de um gráfico.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não é igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não é igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Especifica a unidade maior real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obter o valor real. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Especifica a escala da unidade maior real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obter o valor real. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Especifica o valor máximo real no eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obter o valor real. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Especifica a unidade menor real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obter o valor real. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Especifica a escala da unidade menor real do eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obter o valor real. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Especifica o valor mínimo real no eixo. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) previamente para obter o valor real. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Representa o tipo de agregação do eixo de categoria (agrupar). Aplicado à categoria. Usado somente com séries Histogram ou HistogramPareto. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Representa se o eixo de valores cruza o eixo de categoria entre categorias. Esta propriedade se aplica apenas a eixos de categoria e não a gráficos 3-D. Le **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Especifica a menor unidade de tempo representada no eixo de datas. Le [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Especifica a largura da classe quando a propriedade AggregationType está definida como [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Especifica o tipo do eixo de categoria. Le [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retorna o gráfico pai. Somente leitura [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Representa o ponto no eixo onde o eixo perpendicular o cruza. Le **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Representa o CrossType no eixo especificado onde o outro eixo o cruza. Le [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Especifica o valor de escala das unidades de exibição para o eixo de valores. Le [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Representa o formato do eixo. Somente leitura [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Determina se um eixo tem um título visível. Le **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Indica se a unidade maior do eixo é atribuída automaticamente. Le **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Indica se o valor máximo é atribuído automaticamente. Le **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Indica se a unidade menor do eixo é atribuída automaticamente. Le **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Indica se o valor mínimo é atribuído automaticamente. Le **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Especifica o valor automático do contêiner de estouro. Se falso: use a propriedade OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Especifica o valor automático de espaçamento dos rótulos de marcação. Se falso: use a propriedade TickLabelSpacing. Le **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Especifica o valor automático de espaçamento das marcas de escala. Se falso: use a propriedade TickMarksSpacing. Le **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Especifica o valor automático do contêiner de subfluxo. Se falso: use a propriedade UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Representa se o tipo de escala do eixo de valores é logarítmico ou não. Le **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Indica se o formato está vinculado a dados de origem. Le **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Especifica se o contêiner de estouro está aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do contêiner de estouro. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Representa se o MS PowerPoint plota pontos de dados do último para o primeiro. Le **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Especifica se o contêiner de subfluxo está aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do contêiner de subfluxo. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Representa se o eixo está visível. Le **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Especifica a distância dos rótulos do eixo. Aplicado a eixo de categoria ou data. O valor deve estar entre 0% e 1000%. Le **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Representa a base logarítmica. O valor padrão é 10. Le **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Representa o formato das linhas de grade maiores em um eixo de gráfico. Somente leitura [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Representa o tipo da marca de escala maior para o eixo especificado. Le [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Representa as unidades maiores para o eixo de data ou valor. Le **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Representa a escala da unidade maior para o eixo de data. Le [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Representa o valor máximo no eixo de valor. Le **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Representa o formato das linhas de grade menores em um eixo de gráfico. Somente leitura [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Representa o tipo da marca de escala menor para o eixo especificado. Le [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Representa as unidades menores para o eixo de data ou valor. Le **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Representa a escala da unidade maior para o eixo de data. Le [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Representa o valor mínimo no eixo de valor. Le **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Representa a cadeia de formato para os rótulos [Axis](./). Le [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Especifica o número de contêineres quando a propriedade AggregationType está definida como [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Especifica o valor customizado do contêiner de estouro. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e IsOverflowBin é true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Representa a posição do eixo. Le [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Para ocultar a linha de grade maior defina [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() para [FillType::NoFill](../../aspose.slides/filltype/). Somente leitura **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Para ocultar a linha de grade menor defina [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() para [FillType::NoFill](../../aspose.slides/filltype/). Somente leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Representa o formato do texto. Somente leitura [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Representa a posição dos rótulos de marcação no eixo especificado. Le [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Representa o ângulo de rotação dos rótulos de marcação. Le **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Especifica quantos rótulos de marcação pular entre os que são desenhados. Aplicado a eixo de categoria ou série. Le **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Especifica quantas marcas de escala deverão ser puladas antes da próxima ser desenhada. Aplicado a eixo de categoria ou série. Le **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Obtém o título do eixo. Somente leitura [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Especifica o valor customizado do contêiner de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e IsUnderflowBin é true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos customizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa a instrução C# lock() bloqueando. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos customizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e permite copiar subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e permite copiar subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Representa o tipo de agregação do eixo de categoria (agrupar). Aplicado à categoria. Usado somente com séries Histogram ou HistogramPareto. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Representa se o eixo de valores cruza o eixo de categoria entre categorias. Esta propriedade se aplica apenas a eixos de categoria e não a gráficos 3-D. Escreve **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Especifica a menor unidade de tempo representada no eixo de datas. Escreve [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Especifica a largura da classe quando a propriedade AggregationType está definida como [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Especifica o tipo do eixo de categoria. Escreve [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Representa o ponto no eixo onde o eixo perpendicular o cruza. Escreve **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Representa o CrossType no eixo especificado onde o outro eixo o cruza. Escreve [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Especifica o valor de escala das unidades de exibição para o eixo de valores. Escreve [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Determina se um eixo tem um título visível. Escreve **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Indica se a unidade maior do eixo é atribuída automaticamente. Escreve **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Indica se o valor máximo é atribuído automaticamente. Escreve **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Indica se a unidade menor do eixo é atribuída automaticamente. Escreve **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Indica se o valor mínimo é atribuído automaticamente. Escreve **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Especifica o valor automático do contêiner de estouro. Se falso: use a propriedade OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Especifica o valor automático de espaçamento dos rótulos de marcação. Se falso: use a propriedade TickLabelSpacing. Escreve **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Especifica o valor automático de espaçamento das marcas de escala. Se falso: use a propriedade TickMarksSpacing. Escreve **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Especifica o valor automático do contêiner de subfluxo. Se falso: use a propriedade UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Representa se o tipo de escala do eixo de valores é logarítmico ou não. Escreve **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Indica se o formato está vinculado a dados de origem. Escreve **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Especifica se o contêiner de estouro está aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do contêiner de estouro. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Representa se o MS PowerPoint plota pontos de dados do último para o primeiro. Escreve **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Especifica se o contêiner de subfluxo está aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do contêiner de subfluxo. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Representa se o eixo está visível. Escreve **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Especifica a distância dos rótulos do eixo. Aplicado a eixo de categoria ou data. O valor deve estar entre 0% e 1000%. Escreve **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Representa a base logarítmica. O valor padrão é 10. Escreve **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Representa o tipo da marca de escala maior para o eixo especificado. Escreve [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Representa as unidades maiores para o eixo de data ou valor. Escreve **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Representa a escala da unidade maior para o eixo de data. Escreve [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Representa o valor máximo no eixo de valor. Escreve **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Representa o tipo da marca de escala menor para o eixo especificado. Escreve [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Representa as unidades menores para o eixo de data ou valor. Escreve **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Representa a escala da unidade maior para o eixo de data. Escreve [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Representa o valor mínimo no eixo de valor. Escreve **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Representa a cadeia de formato para os rótulos [Axis](./). Escreve [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Especifica o número de contêineres quando a propriedade AggregationType está definida como [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Especifica o valor customizado do contêiner de estouro. Aplicado quando IsAutomaticOverflowBin está definido como false e IsOverflowBin é true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Representa a posição do eixo. Escreve [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Representa a posição dos rótulos de marcação no eixo especificado. Escreve [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Representa o ângulo de rotação dos rótulos de marcação. Escreve **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Especifica quantos rótulos de marcação pular entre os que são desenhados. Aplicado a eixo de categoria ou série. Escreve **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Especifica quantas marcas de escala deverão ser puladas antes da próxima ser desenhada. Aplicado a eixo de categoria ou série. Escreve **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Especifica o valor customizado do contêiner de subfluxo. Aplicado quando IsAutomaticUnderflowBin está definido como false e IsUnderflowBin é true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Define a propriedade IAxis::get(set)_CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos customizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa a instrução C# lock() desbloqueando. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [IAxis](../iaxis/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)