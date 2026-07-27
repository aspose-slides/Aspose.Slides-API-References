---
title: ChartPlotArea
second_title: Referência da API Aspose.Slides para C++
description: Representa o retângulo onde o gráfico deve ser plotado.
type: docs
weight: 248
url: /pt/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea classe

Representa o retângulo onde o gráfico deve ser plotado.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Especifica a altura real do elemento de gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Especifica a largura real do elemento de gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Especifica a localização x real (esquerda) do elemento de gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Especifica o topo real do elemento de gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Base. Somente leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Somente leitura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Retorna o formato de uma área de plotagem. Somente leitura [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Retorna a altura da caixa delimitadora da área de plotagem como fração da altura do gráfico (de 0 a 1). Leia **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Define como a localização deve ser calculada: true \u2013 calculado automaticamente; definido pelas propriedades X, Y, Width, Height. Somente leitura **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem será pelo interior (excluindo eixo e rótulos de eixo) ou pelo exterior (incluindo eixo e rótulos de eixo). Leia [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Direita. Somente leitura **float**. |
| **float** [get_Width](./get_width/)() override | Retorna a largura da caixa delimitadora da área de plotagem como fração da largura do gráfico (de 0 a 1). Leia **float**. |
| **float** [get_X](./get_x/)() override | Retorna a coordenada x do canto superior esquerdo da caixa delimitadora da área de plotagem como fração da largura do gráfico (de 0 a 1). Leia **float**. |
| **float** [get_Y](./get_y/)() override | Retorna a coordenada y do canto superior esquerdo da caixa delimitadora da área de plotagem como fração da altura do gráfico (de 0 a 1). Leia **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita o hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na prática não copia nada, apenas inicializa um novo objeto e habilita a cópia de construtor de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na prática não copia nada, apenas inicializa um novo objeto e habilita a cópia de construtor de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Height](./set_height/)(**float**) override | Define a altura da caixa delimitadora da área de plotagem como fração da altura do gráfico (de 0 a 1). Grave **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem será pelo interior (excluindo eixo e rótulos de eixo) ou pelo exterior (incluindo eixo e rótulos de eixo). Grave [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Define a largura da caixa delimitadora da área de plotagem como fração da largura do gráfico (de 0 a 1). Grave **float**. |
| void [set_X](./set_x/)(**float**) override | Define a coordenada x do canto superior esquerdo da caixa delimitadora da área de plotagem como fração da largura do gráfico (de 0 a 1). Grave **float**. |
| void [set_Y](./set_y/)(**float**) override | Define a coordenada y do canto superior esquerdo da caixa delimitadora da área de plotagem como fração da altura do gráfico (de 0 a 1). Grave **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alterar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [IChartPlotArea](../ichartplotarea/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)