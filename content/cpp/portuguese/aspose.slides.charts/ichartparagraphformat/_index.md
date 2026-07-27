---
title: IChartParagraphFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa as propriedades de formatação de parágrafo de um gráfico.
type: docs
weight: 781
url: /pt/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat classe


Representa propriedades de formatação de parágrafo de um gráfico.

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para fins internos. |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | Retorna o alinhamento de texto em um parágrafo. Leia [TextAlignment](../../aspose.slides/textalignment/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Retorna o tamanho padrão de tabulação. Leia **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Determina se a quebra de linha Leste Asiático é usada em um parágrafo. Leia [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Retorna o alinhamento da fonte em um parágrafo. Leia [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Determina se a pontuação suspensa é usada em um parágrafo. Leia [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Retorna o recuo da primeira linha/recúo suspenso do parágrafo. O recuo suspenso pode ser definido com valores negativos. Leia **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Determina se a quebra de linha Latina é usada em um parágrafo. Leia [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Retorna a margem esquerda em um parágrafo. Leia **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Retorna a margem direita em um parágrafo. Leia **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Leia [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Retorna a quantidade de espaço após a última linha em um parágrafo. Leia **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Retorna a quantidade de espaço antes da primeira linha em um parágrafo. Leia **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Retorna a quantidade de espaço entre linhas de base em um parágrafo. Leia **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Retorna a tabulação de um parágrafo no índice especificado. Somente leitura [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | Retorna as tabulações de um parágrafo. Somente leitura [ITabCollection](../../aspose.slides/itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | Define o alinhamento de texto em um parágrafo. Grave [TextAlignment](../../aspose.slides/textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Define o tamanho padrão de tabulação. Grave **float**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Determina se a quebra de linha Leste Asiático é usada em um parágrafo. Grave [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | Define o alinhamento da fonte em um parágrafo. Grave [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | Determina se a pontuação suspensa é usada em um parágrafo. Grave [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Define o recuo da primeira linha/recúo suspenso do parágrafo. O recuo suspenso pode ser definido com valores negativos. Grave **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Determina se a quebra de linha Latina é usada em um parágrafo. Grave [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Define a margem esquerda em um parágrafo. Grave **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Define a margem direita em um parágrafo. Grave **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. Grave [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Define a quantidade de espaço após a última linha em um parágrafo. Grave **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Define a quantidade de espaço antes da primeira linha em um parágrafo. Grave **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Define a quantidade de espaço entre linhas de base em um parágrafo. Grave **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o enésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)