---
title: ChartSeriesGroup
second_title: Referência da API Aspose.Slides para C++
description: Representa um grupo de séries.
type: docs
weight: 300
url: /pt/aspose.slides.charts/chartseriesgroup/
---
## classe ChartSeriesGroup

Representa um grupo de séries.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Leia [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Especifica o fator de escala para o gráfico de bolhas (pode estar entre 0 e 300 por cento do tamanho padrão). Leia **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retorna o gráfico pai. Somente leitura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Retorna a série de gráfico no grupo no índice especificado. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 0 e 90 por cento do tamanho da área de plotagem). Leia **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Obtém o ângulo da primeira fatia de gráfico de pizza ou rosca, em graus (horário a partir do topo, de 0 a 360 graus). Leia **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Retorna a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Leia **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Especifica o espaço entre clusters de barras ou colunas, como porcentagem da largura da barra ou coluna. Leia **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Leia **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Especifica o formato HiLowLines. HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Especifica que cada marcador de dados na série tem uma cor diferente. Leia **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Leia [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | As informações de divisão personalizada para um gráfico pie-of-pie ou bar-of-pie com uma divisão personalizada. Retorna o ponto de dados que deve ser desenhado na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie por índice. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | As informações de divisão personalizada para um gráfico pie-of-pie ou bar-of-pie com uma divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Somente leitura [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Especifica um valor que deve ser usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. É usado junto com a propriedade PieSplitBy. Leia **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Indica se as séries deste grupo são plotadas em eixo secundário. Somente leitura **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Especifica o tamanho da segunda pizza ou barra de um gráfico pie-of-pie ou bar-of-pie, como porcentagem do tamanho da primeira pizza (pode estar entre 5 e 200 por cento). Leia **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Retorna uma coleção de séries. Somente leitura [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Retorna um tipo deste grupo de séries. Somente leitura [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Fornece acesso às barras de alta/baixa de gráfico de Linha ou Ações. Somente leitura [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Obtém o elemento no índice especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia construindo subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia construindo subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Grave [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Especifica o fator de escala para o gráfico de bolhas (pode estar entre 0 e 300 por cento do tamanho padrão). Grave **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 0 e 90 por cento do tamanho da área de plotagem). Grave **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Define o ângulo da primeira fatia de gráfico de pizza ou rosca, em graus (horário a partir do topo, de 0 a 360 graus). Grave **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Grave **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Especifica o espaço entre clusters de barras ou colunas, como porcentagem da largura da barra ou coluna. Grave **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Grave **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Especifica que cada marcador de dados na série tem uma cor diferente. Grave **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Grave [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Especifica um valor que deve ser usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. É usado junto com a propriedade PieSplitBy. Grave **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Especifica o tamanho da segunda pizza ou barra de um gráfico pie-of-pie ou bar-of-pie, como porcentagem do tamanho da primeira pizza (pode estar entre 5 e 200 por cento). Grave **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi objeto. Libera todas as estruturas de dados internas. |

## Observações

1) Veja o resumo e as observações da classe ChartSeriesGroupCollection e do enum CombinableSeriesTypesGroup. 2) Grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo ("propriedades de grupo de séries"). "Propriedades de grupo de séries" na classe [ChartSeriesGroup](./) é leitura/gravação. Cada uma das "propriedades de grupo de séries" pode ter uma projeção somente leitura na classe [ChartSeries](../chartseries/).

## Veja Também

* Classe [IChartSeriesGroup](../ichartseriesgroup/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)