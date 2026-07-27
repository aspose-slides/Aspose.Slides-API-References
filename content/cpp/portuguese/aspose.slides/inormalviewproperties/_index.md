---
title: INormalViewProperties
second_title: Referência da API Aspose.Slides para C++
description: "Representa as propriedades da visualização normal. A visualização normal consiste em três regiões de conteúdo: o próprio slide, uma região de conteúdo lateral e uma região de conteúdo inferior."
type: docs
weight: 2978
url: /pt/aspose.slides/inormalviewproperties/
---
## INormalViewProperties classe

Representa as propriedades da visualização normal. A visualização normal consiste em três regiões de conteúdo: o slide em si, uma região de conteúdo lateral e uma região de conteúdo inferior.

```cpp
class INormalViewProperties : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() | Especifica o estado em que a barra separadora horizontal deve ser exibida. Uma barra separadora horizontal separa o slide da região de conteúdo abaixo do slide. |
| virtual **bool** [get_PreferSingleView](./get_prefersingleview/)() | Especifica se o usuário prefere ver uma região de conteúdo único em janela inteira em vez da visualização normal padrão com três regiões de conteúdo. Se habilitado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() | Este elemento especifica o dimensionamento da região lateral do conteúdo da visualização normal, quando a região tem um tamanho restaurado variável (nem minimizada nem maximizada). Somente leitura [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() | Este elemento especifica o dimensionamento da região superior do slide da visualização normal, quando a região tem um tamanho restaurado variável (nem minimizada nem maximizada). Somente leitura [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() | Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. Leia **bool**. |
| virtual **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() | Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral é suficientemente pequena. Leia **bool**. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() | Especifica o estado em que a barra separadora vertical deve ser exibida. Uma barra separadora vertical separa o slide da região de conteúdo lateral. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | Especifica o estado em que a barra separadora horizontal deve ser exibida. Uma barra separadora horizontal separa o slide da região de conteúdo abaixo do slide. |
| virtual void [set_PreferSingleView](./set_prefersingleview/)(**bool**) | Especifica se o usuário prefere ver uma região de conteúdo único em janela inteira em vez da visualização normal padrão com três regiões de conteúdo. Se habilitado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Escreva **bool**. |
| virtual void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) | Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. Escreva **bool**. |
| virtual void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) | Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral é suficientemente pequena. Escreva **bool**. |
| virtual void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | Especifica o estado em que a barra separadora vertical deve ser exibida. Uma barra separadora vertical separa o slide da região de conteúdo lateral. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Defina o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver Também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)