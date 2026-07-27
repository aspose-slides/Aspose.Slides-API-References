---
title: IChartSeriesGroup
second_title: Referência da API Aspose.Slides para C++
description: Representa um grupo de séries.
type: docs
weight: 846
url: /pt/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup classe

Representa um grupo de séries.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Leia [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300 por cento do tamanho padrão). Leia **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Retorna a série do gráfico no grupo no índice especificado. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 10 e 90 por cento do tamanho da área de plotagem). Leia **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Obtém o ângulo do primeiro segmento de pizza ou rosca, em graus (no sentido horário a partir de cima, de 0 a 360 graus). Leia **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Retorna a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Leia **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Especifica o espaço entre agrupamentos de barras ou colunas, como porcentagem da largura da barra ou coluna. Leia **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Especifica o formato HiLowLines. HiLowLines é aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Especifica que cada marcador de dados na série tem uma cor diferente. Leia **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2D, como porcentagem (de -100% a 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Leia [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | A informação de divisão personalizada para um gráfico pie-of-pie ou bar-of-pie com divisão personalizada. Retorna o ponto de dados que deve ser desenhado na segunda pizza ou barra por índice. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | A informação de divisão personalizada para um gráfico pie-of-pie ou bar-of-pie com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra. Somente leitura [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Especifica um valor que deve ser usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. É usado junto com a propriedade PieSplitBy. Leia **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Indica se as séries deste grupo são plotadas em eixo secundário. Somente leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Especifica o tamanho da segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie, como porcentagem do tamanho da primeira pizza (pode ser entre 5 e 200 por cento). Leia **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Retorna uma coleção somente leitura de séries de gráfico. Somente leitura [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Retorna um tipo deste grupo de séries. Somente leitura [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Fornece acesso às barras up/down de gráficos de linha ou de ações. Somente leitura [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Obtém o elemento no índice especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Grave [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300 por cento do tamanho padrão). Grave **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 10 e 90 por cento do tamanho da área de plotagem). Grave **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Define o ângulo do primeiro segmento de pizza ou rosca, em graus (no sentido horário a partir de cima, de 0 a 360 graus). Grave **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Grave **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Especifica o espaço entre agrupamentos de barras ou colunas, como porcentagem da largura da barra ou coluna. Grave **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Grave **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Especifica que cada marcador de dados na série tem cor diferente. Grave **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2D, como porcentagem (de -100% a 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. Grave [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Especifica um valor que deve ser usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pie-of-pie ou bar-of-pie. É usado junto com a propriedade PieSplitBy. Grave **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Especifica o tamanho da segunda pizza ou barra de um gráfico pie-of-pie ou bar-of-pie, como porcentagem do tamanho da primeira pizza (pode ser entre 5 e 200 por cento). Grave **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Observações

1) Consulte o resumo e as observações da classe ChartSeriesGroupCollection e do enum CombinableSeriesTypesGroup. 2) O grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo ("propriedades de grupo de séries"). "Propriedades de grupo de séries" na classe [ChartSeriesGroup](../chartseriesgroup/) é leitura/gravação. Cada uma das "propriedades de grupo de séries" pode ter uma projeção somente leitura na classe [ChartSeries](../chartseries/). 

## Veja Também

* Classe [IChartComponent](../ichartcomponent/)
* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)