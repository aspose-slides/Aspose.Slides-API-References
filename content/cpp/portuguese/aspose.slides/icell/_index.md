---
title: ICell
second_title: Referência da API Aspose.Slides para C++
description: Representa uma célula em uma tabela.
type: docs
weight: 1639
url: /pt/aspose.slides/icell/
---
## ICell classe

Representa uma célula em uma tabela.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Determina se a caixa de texto está ou não centralizada dentro de uma célula. Leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Retorna o objeto [CellFormat](../cellformat/) que contém propriedades de formatação para esta célula. Somente leitura [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Retorna o número de colunas da grade da tabela pai que deverão ser abrangidas pela célula atual. Esta propriedade permite que as células tenham a aparência de mescladas, pois abrangem limites verticais de outras células na tabela. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Obtém a primeira coluna da célula. Somente leitura [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Retorna o índice da primeira coluna coberta pela célula. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Obtém a primeira linha da célula. Somente leitura [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Retorna o índice da primeira linha coberta pela célula. Somente leitura **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Retorna a altura da célula. Somente leitura **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Retorna verdadeiro se a célula estiver mesclada com qualquer célula ajustada, falso caso contrário. Somente leitura **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Retorna a margem inferior em um [TextFrame](../textframe/). Leitura **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Retorna a margem esquerda em um [TextFrame](../textframe/). Leitura **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Retorna a margem direita em um [TextFrame](../textframe/). Leitura **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Retorna a margem superior em um [TextFrame](../textframe/). Leitura **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Retorna a altura mínima de uma célula. Esta é a soma das alturas mínimas de todas as linhas cobertas pela célula. Somente leitura **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Retorna a distância do lado esquerdo de uma tabela ao lado esquerdo de uma célula. Somente leitura **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Retorna a distância do lado superior de uma tabela ao lado superior de uma célula. Somente leitura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Retorna o número de linhas que uma célula mesclada abrange. Isto é usado em combinação com o atributo vMerge em outras células para especificar a célula inicial de uma mesclagem horizontal. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Retorna o objeto [Table](../table/) pai de uma célula. Somente leitura [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Retorna o tipo de âncora de texto. Leitura [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Retorna a moldura de texto de uma célula. Somente leitura [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Retorna o tipo de texto vertical. Leitura [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Retorna a largura da célula. Somente leitura **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite a hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Determina se a caixa de texto está ou não centralizada dentro de uma célula. Grava **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Define a margem inferior em um [TextFrame](../textframe/). Grava **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Define a margem esquerda em um [TextFrame](../textframe/). Grava **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Define a margem direita em um [TextFrame](../textframe/). Grava **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Define a margem superior em um [TextFrame](../textframe/). Grava **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Define o tipo de âncora de texto. Grava [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Define o tipo de texto vertical. Grava [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Divide a célula em duas células pelo índice da coluna. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Divide a célula pela altura. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Divide a célula em duas células pelo índice da linha. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Divide a célula pela largura. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [ISlideComponent](../islidecomponent/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)