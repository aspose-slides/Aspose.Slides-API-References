---
title: DataLabelFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa opções de formatação para DataLabel.
type: docs
weight: 391
url: /pt/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat classe

Representa opções de formatação para [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspoke::Slides::Charts::IDataLabelFormat
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara com o objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica do C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não é igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não é igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Para fins internos apenas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Representa o formato do rótulo de dados. Somente leitura [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Lê **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Representa a string de formato para o objeto DataLabels. Leitura [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Retorna o objeto Parent_Immediate. Somente leitura [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Retorna o [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) pai. Somente leitura [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Representa a posição do rótulo de dados. Leitura [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Define ou retorna um Variant representando o separador usado para os rótulos de dados em um gráfico. Leitura [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Representa o comportamento de exibição do valor do tamanho da bolha do rótulo de dados de um gráfico especificado. True exibe o valor do tamanho da bolha. False para ocultar. Leitura **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. True exibe o nome da categoria para os rótulos de dados em um gráfico. False para ocultar. Leitura **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. True exibe o valor da célula. False para ocultar. Leitura **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Representa o comportamento de exibição das linhas guias do rótulo de dados de um gráfico especificado. True exibe as linhas guias. False para ocultar. Leitura **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Representa o comportamento de exibição da chave da legenda do rótulo de dados de um gráfico especificado. True se a chave da legenda do rótulo de dados estiver visível. Leitura **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. True exibe o valor percentual. False para ocultar. Leitura **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Retorna um Boolean indicando o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. True para mostrar o nome da série. False para ocultar. Leitura **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. True exibe o valor percentual. False para ocultar. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Retorna o formato de texto do gráfico. Somente leitura [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Retorna o código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Escreve **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Representa a string de formato para o objeto DataLabels. Escreve [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Representa a posição do rótulo de dados. Escreve [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Define ou retorna um Variant representando o separador usado para os rótulos de dados em um gráfico. Escreve [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Representa o comportamento de exibição do valor do tamanho da bolha do rótulo de dados de um gráfico especificado. True exibe o valor do tamanho da bolha. False para ocultar. Escreve **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. True exibe o nome da categoria para os rótulos de dados em um gráfico. False para ocultar. Escreve **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. True exibe o valor da célula. False para ocultar. Escreve **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Representa o comportamento de exibição das linhas guias do rótulo de dados de um gráfico especificado. True exibe as linhas guias. False para ocultar. Escreve **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Representa o comportamento de exibição da chave da legenda do rótulo de dados de um gráfico especificado. True se a chave da legenda do rótulo de dados estiver visível. Escreve **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. True exibe o valor percentual. False para ocultar. Escreve **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Define um Boolean indicando o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. True para mostrar o nome da série. False para ocultar. Escreve **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. True exibe o valor percentual. False para ocultar. Escreve **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Veja também

* Classe [PVIObject](../../aspose.slides/pviobject/)
* Classe [IDataLabelFormat](../idatalabelformat/)
* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)