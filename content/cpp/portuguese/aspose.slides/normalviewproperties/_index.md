---
title: NormalViewProperties
second_title: Referência da API Aspose.Slides para C++
description: "Representa as propriedades da visualização normal. A visualização normal consiste em três regiões de conteúdo: o próprio slide, uma região de conteúdo lateral e uma região de conteúdo inferior."
type: docs
weight: 4525
url: /pt/aspose.slides/normalviewproperties/
---
## NormalViewProperties classe

Representa as propriedades da visualização normal. A visualização normal consiste em três regiões de conteúdo: o próprio slide, uma região de conteúdo lateral e uma região de conteúdo inferior.

```cpp
class NormalViewProperties : public Aspose::Slides::INormalViewProperties
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() override | Especifica o estado em que a barra de divisão horizontal deve ser mostrada. Uma barra de divisão horizontal separa o slide da região de conteúdo abaixo do slide. |
| **bool** [get_PreferSingleView](./get_prefersingleview/)() override | Especifica se o usuário prefere ver uma região de conteúdo única em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. Se habilitado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() override | Este elemento especifica o dimensionamento da região de conteúdo lateral da visualização normal, quando a região tem um tamanho restaurado variável (nem minimizado nem maximizado). Somente leitura [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() override | Este elemento especifica o dimensionamento da região superior do slide na visualização normal, quando a região tem um tamanho restaurado variável (nem minimizado nem maximizado). Somente leitura [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() override | Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. Leitura **bool**. |
| **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() override | Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral for suficientemente pequena. Leitura **bool**. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() override | Especifica o estado em que a barra de divisão vertical deve ser mostrada. Uma barra de divisão vertical separa o slide da região de conteúdo lateral. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Especifica o estado em que a barra de divisão horizontal deve ser mostrada. Uma barra de divisão horizontal separa o slide da região de conteúdo abaixo do slide. |
| void [set_PreferSingleView](./set_prefersingleview/)(**bool**) override | Especifica se o usuário prefere ver uma região de conteúdo única em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. Se habilitado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Grava **bool**. |
| void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) override | Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. Grava **bool**. |
| void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) override | Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral for suficientemente pequena. Grava **bool**. |
| void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Especifica o estado em que a barra de divisão vertical deve ser mostrada. Uma barra de divisão vertical separa o slide da região de conteúdo lateral. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

O exemplo a seguir mostra como configurar as propriedades [ViewProperties::get_NormalViewProperties](../viewproperties/get_normalviewproperties/) de um [Presentation](../presentation/) do PowerPoint. 
```cpp
// Instanciar um objeto de apresentação que representa um arquivo de apresentação
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto normalViewProperties = pres->get_ViewProperties()->get_NormalViewProperties();

normalViewProperties->set_HorizontalBarState(SplitterBarStateType::Restored);
normalViewProperties->set_VerticalBarState(SplitterBarStateType::Maximized);
normalViewProperties->get_RestoredTop()->set_AutoAdjust(true);
normalViewProperties->get_RestoredTop()->set_DimensionSize(80.0f);
normalViewProperties->set_ShowOutlineIcons(true);
pres->Save(u"presentation_normal_view_state.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [INormalViewProperties](../inormalviewproperties/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)