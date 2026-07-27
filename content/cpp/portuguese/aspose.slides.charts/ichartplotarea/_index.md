---
title: IChartPlotArea
second_title: Referência da API Aspose.Slides para C++
description: Representa as propriedades do título do gráfico.
type: docs
weight: 794
url: /pt/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea classe

Representa as propriedades do título do gráfico.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, ainda que segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Especifica a altura real do elemento do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Especifica a largura real do elemento do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Leia **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Obtém a parte superior do elemento do gráfico como uma fração da altura do gráfico. Somente leitura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Retorna o formato de uma área de plotagem. Somente leitura [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Especifica a altura do elemento do gráfico como uma fração da altura do gráfico. Leia **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem será por dentro (excluindo eixos e rótulos de eixo) ou por fora (incluindo eixos e rótulos de eixo). Leia [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Obtém a direita do elemento do gráfico como uma fração da largura do gráfico. Somente leitura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Especifica a largura do elemento do gráfico como uma fração da largura do gráfico. Leia **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Especifica a localização x (esquerda) do elemento do gráfico como uma fração da largura do gráfico. Leia **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Especifica a parte superior do elemento do gráfico como uma fração da altura do gráfico. Leia **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógio do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógio da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógio do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógio do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Especifica a altura do elemento do gráfico como uma fração da altura do gráfico. Grava **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem será por dentro (excluindo eixos e rótulos de eixo) ou por fora (incluindo eixos e rótulos de eixo). Grava [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Especifica a largura do elemento do gráfico como uma fração da largura do gráfico. Grava **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Especifica a localização x (esquerda) do elemento do gráfico como uma fração da largura do gráfico. Grava **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Especifica a parte superior do elemento do gráfico como uma fração da altura do gráfico. Grava **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógio do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [ILayoutable](../ilayoutable/)
* Classe [IActualLayout](../iactuallayout/)
* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)