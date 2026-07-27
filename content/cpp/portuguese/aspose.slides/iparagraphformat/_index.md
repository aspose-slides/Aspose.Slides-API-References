---
title: IParagraphFormat
second_title: Aspose.Slides para C++ Referência de API
description: Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de IParagraphFormatEffectiveData, todas as propriedades desta classe são graváveis.
type: docs
weight: 3147
url: /pt/aspose.slides/iparagraphformat/
---
## IParagraphFormat classe


Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), todas as propriedades desta classe são graváveis.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Retorna o alinhamento de texto em um parágrafo sem herança. Leia [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Retorna o formato de marcadores do parágrafo. Somente leitura [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Retorna o formato padrão de parte de um parágrafo. Nenhuma herança aplicada. Somente leitura [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Retorna o tamanho padrão de tabulação sem herança. Leia **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Retorna a profundidade do parágrafo. Valor 0 significa valor indefinido. Leia **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Determina se a quebra de linha asiática oriental é usada em um parágrafo. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Retorna o alinhamento de fonte em um parágrafo sem herança. Leia [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Determina se a pontuação pendente é usada em um parágrafo. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Retorna o recuo da primeira linha/recúo pendente do parágrafo sem herança. O recúo pendente pode ser definido com valores negativos. Leia **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Retorna a margem esquerda em um parágrafo sem herança. Leia **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Retorna a margem direita em um parágrafo sem herança. Leia **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Leia [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Retorna a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leia **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Retorna a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leia **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Retorna a quantidade de espaço entre linhas base em um parágrafo. Valor positivo significa porcentagem, negativo – tamanho em pontos. Nenhuma herança aplicada. Leia **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Retorna a tabulação de um parágrafo no índice especificado. Nenhuma herança aplicada. Somente leitura [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Retorna tabulações de um parágrafo. Nenhuma herança aplicada. Somente leitura [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtém os dados de formatação de parágrafo efetivos com a herança aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Define o alinhamento de texto em um parágrafo sem herança. Escreva [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Define o tamanho padrão de tabulação sem herança. Escreva **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Define a profundidade do parágrafo. Valor 0 significa valor indefinido. Escreva **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Determina se a quebra de linha asiática oriental é usada em um parágrafo. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Define o alinhamento de fonte em um parágrafo sem herança. Escreva [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Determina se a pontuação pendente é usada em um parágrafo. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Define o recuo da primeira linha/recúo pendente do parágrafo sem herança. O recúo pendente pode ser definido com valores negativos. Escreva **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Define a margem esquerda em um parágrafo sem herança. Escreva **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Define a margem direita em um parágrafo sem herança. Escreva **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Escreva [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Define a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Escreva **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ter. Um valor negativo especifica o tamanho do espaço em branco em pontos. Escreva **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Define a quantidade de espaço entre linhas base em um parágrafo. Valor positivo significa porcentagem, negativo – tamanho em pontos. Nenhuma herança aplicada. Escreva **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento do template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; ao invés, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; ao invés, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; ao invés, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; ao invés, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

Esta classe é usada para devolver e manipular propriedades de formatação de parágrafo definidas para o parágrafo específico. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam "indefinido".

Para obter os valores de parâmetro de formatação efetivos, incluindo os herdados, você precisa usar o método [IParagraphFormat::GetEffective](./geteffective/) que retorna uma instância [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Ver Também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)