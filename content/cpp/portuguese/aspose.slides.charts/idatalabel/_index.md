---
title: IDataLabel
second_title: Referência da API Aspose.Slides para C++
description: Representa rótulos de série.
type: docs
weight: 937
url: /pt/aspose.slides.charts/idatalabel/
---
## IDataLabel classe

Representa rótulos de série.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializa TextFrameForOverriding com o texto no parâmetro \"text\". Se TextFrameForOverriding já estiver inicializado, altera simplesmente seu texto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Especifica a altura real do elemento do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Lê **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Especifica a largura real do elemento do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Lê **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Especifica a localização real em x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Lê **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Especifica a posição superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obter valores reais. Lê **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Obtém o topo do elemento do gráfico como fração da altura do gráfico. Somente leitura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retorna o gráfico. Somente leitura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Retorna o formato do rótulo de dados. Somente leitura [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Especifica a altura do elemento do gráfico como fração da altura do gráfico. Lê **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Falso indica que o rótulo de dados não está visível (e, portanto, todas as flags Show*- (ShowValue, ...) são falsas). Somente leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Obtém a borda direita do elemento do gráfico como fração da largura do gráfico. Somente leitura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retorna o formato de texto do gráfico. Somente leitura [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Pode conter um texto formatado rico. Se essa propriedade não for nula, então esse valor de texto formatado substitui o texto gerado automaticamente. Texto gerado automaticamente é uma propriedade implícita do rótulo de dados, do rótulo de unidade de exibição do eixo de valores, do título do eixo, do título do gráfico, do rótulo da linha de tendência. Texto gerado automaticamente é formatado com a propriedade [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Somente leitura [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Obtém a célula de dados da planilha. Aplicado se a propriedade IDataLabelFormat::get(set)_ShowLabelValueFromCell for verdadeira. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Especifica a largura do elemento do gráfico como fração da largura do gráfico. Lê **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Especifica a localização em x (esquerda) do elemento do gráfico como fração da largura do gráfico. Lê **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Especifica o topo do elemento do gráfico como fração da altura do gráfico. Lê **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Retorna o texto real do rótulo com base nas configurações [DataLabelFormat](../datalabelformat/) ou no valor TextFrameForOverriding.Text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a geração de hash para objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | Torna o rótulo de dados oculto definindo todas as flags Show*- (ShowValue, ...) como falsas. IsVisible será falso após isso. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência o objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Especifica a altura do elemento do gráfico como fração da altura do gráfico. Grava **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Define a célula de dados da planilha. Aplicado se a propriedade IDataLabelFormat::get(set)_ShowLabelValueFromCell for verdadeira. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Especifica a largura do elemento do gráfico como fração da largura do gráfico. Grava **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Especifica a localização em x (esquerda) do elemento do gráfico como fração da largura do gráfico. Grava **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Especifica o topo do elemento do gráfico como fração da altura do gráfico. Grava **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analítico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja também

* Classe [ILayoutable](../ilayoutable/)
* Classe [IOverridableText](../ioverridabletext/)
* Classe [IActualLayout](../iactuallayout/)
* Namespace [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)