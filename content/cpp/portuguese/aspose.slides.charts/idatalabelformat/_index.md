---
title: IDataLabelFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa opções de formatação para DataLabel.
type: docs
weight: 963
url: /pt/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat classe

Representa opções de formatação para [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Representa o formato do rótulo de dados. Somente leitura [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Leitura **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Representa a string de formato para o objeto DataLabels. Leitura [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Representa a posição do rótulo de dados. Leitura [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. Leitura [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Representa o comportamento de exibição do valor de tamanho da bolha do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor do tamanho da bolha. Falso oculta. Leitura **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. Verdadeiro exibe o nome da categoria para os rótulos de dados em um gráfico. Falso oculta. Leitura **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor da célula. Falso oculta. Leitura **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Representa o comportamento de exibição das linhas de condução do rótulo de dados de um gráfico especificado. Verdadeiro exibe as linhas de condução. Falso oculta. Leitura **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Representa o comportamento de exibição da chave de legenda do rótulo de dados de um gráfico especificado. Verdadeiro se a chave de legenda do rótulo de dados estiver visível. Leitura **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Retorna um Boolean indicando o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. Verdadeiro para mostrar o nome da série. Falso para ocultar. Leitura **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retorna o formato de texto do gráfico. Somente leitura [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Grava **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Representa a string de formato para o objeto DataLabels. Grava [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Representa a posição do rótulo de dados. Grava [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. Grava [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Representa o comportamento de exibição do valor de tamanho da bolha do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor do tamanho da bolha. Falso oculta. Grava **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. Verdadeiro exibe o nome da categoria para os rótulos de dados em um gráfico. Falso oculta. Grava **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor da célula. Falso oculta. Grava **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Representa o comportamento de exibição das linhas de condução do rótulo de dados de um gráfico especificado. Verdadeiro exibe as linhas de condução. Falso oculta. Grava **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Representa o comportamento de exibição da chave de legenda do rótulo de dados de um gráfico especificado. Verdadeiro se a chave de legenda do rótulo de dados estiver visível. Grava **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Grava **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Define um Boolean indicando o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. Verdadeiro para mostrar o nome da série. Falso para ocultar. Grava **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Grava **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa a liberação da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)