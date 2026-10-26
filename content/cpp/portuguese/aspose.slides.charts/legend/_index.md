---
title: Legend
second_title: Referência da API Aspose.Slides para C++
description: Representa as propriedades da legenda do gráfico.
type: docs
weight: 1262
url: /pt/aspose.slides.charts/legend/
---
## Legend classe

Representa as propriedades da legenda do gráfico.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que de acordo com IEC 60559:1989 NaN não é igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que de acordo com IEC 60559:1989 NaN não é igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Especifica a altura real do elemento do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter os valores reais. Leitura **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Especifica a largura real do elemento do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter os valores reais. Leitura **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Especifica a posição x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter os valores reais. Leitura **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter os valores reais. Leitura **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Base. Somente leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Obtém as entradas da legenda. Somente leitura [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Obtém as propriedades da entrada da legenda correspondente ao ponto de dados no gráfico no índice especificado. No caso dos tipos de gráfico: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, o ponto de dados é tomado da primeira série. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Retorna o formato de uma legenda. Somente leitura [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Retorna a altura da legenda como uma fração da altura do gráfico. Leitura **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Determina se outros elementos do gráfico podem sobrepor a legenda. Leitura **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Especifica a posição da legenda em um gráfico. Valores não-NaN das propriedades X, Y, Width, Heigt substituem o efeito desta propriedade. Leitura [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Direita. Somente leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Formato de texto. Somente leitura [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Retorna a largura da legenda como uma fração da largura do gráfico. Leitura **float**. |
| **float** [get_X](./get_x/)() override | Retorna a coordenada x da legenda como uma fração da largura do gráfico. Leitura **float**. |
| **float** [get_Y](./get_y/)() override | Retorna a coordenada y da legenda como uma fração da altura do gráfico. Leitura **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia construtora de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia construtora de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Height](./set_height/)(**float**) override | Define a altura da legenda como uma fração da altura do gráfico. Grava **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Determina se outros elementos do gráfico podem sobrepor a legenda. Grava **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Especifica a posição da legenda em um gráfico... Grava [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Define a largura da legenda como uma fração da largura do gráfico. Grava **float**. |
| void [set_X](./set_x/)(**float**) override | Define a coordenada x da legenda como uma fração da largura do gráfico. Grava **float**. |
| void [set_Y](./set_y/)(**float**) override | Define a coordenada y da legenda como uma fração da altura do gráfico. Grava **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [ILegend](../ilegend/)
* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)