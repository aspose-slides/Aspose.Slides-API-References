---
title: Cell
second_title: Referência da API Aspose.Slides para C++
description: Representa uma célula de uma tabela.
type: docs
weight: 300
url: /pt/aspose.slides/cell/
---
## Cell classe

Representa uma célula de uma tabela.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais mesmo que, segundo IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Determina se a caixa de texto está centralizada dentro de uma célula. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Retorna o objeto [CellFormat](../cellformat/) que contém as propriedades de formatação para esta célula. Somente leitura [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Retorna o número de colunas da grade da tabela pai que devem ser abrangidas pela célula atual. Esta propriedade permite que as células aparentem estar mescladas, ao abranger limites verticais de outras células na tabela. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Obtém a primeira coluna da célula. Somente leitura [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Retorna o índice da primeira coluna coberta pela célula. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Obtém a primeira linha da célula. Somente leitura [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Retorna o índice da primeira linha coberta pela célula. Somente leitura **int32_t**. |
| **double** [get_Height](./get_height/)() override | Retorna a altura da célula. Somente leitura **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Retorna true se a célula estiver mesclada com alguma célula ajustada, false caso contrário. Somente leitura **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Retorna a margem inferior em um [TextFrame](../textframe/). Leitura **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Retorna a margem esquerda em um [TextFrame](../textframe/). Leitura **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Retorna a margem direita em um [TextFrame](../textframe/). Leitura **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Retorna a margem superior em um [TextFrame](../textframe/). Leitura **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Retorna a altura mínima de uma célula. Isto é a soma das alturas mínimas de todas as linhas cobertas pela célula. Somente leitura **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Retorna a distância do lado esquerdo da tabela ao lado esquerdo da célula. Somente leitura **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Retorna a distância do lado superior da tabela ao lado superior da célula. Somente leitura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Retorna a apresentação pai de uma célula. Somente leitura [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Retorna o número de linhas que uma célula mesclada abrange. Isso é usado em combinação com o atributo vMerge em outras células para especificar a célula inicial de uma mesclagem horizontal. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Retorna o slide pai de uma célula. Somente leitura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Retorna o objeto [Table](../table/) pai de uma célula. Somente leitura [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Retorna o tipo de âncora de texto. Leitura [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Retorna a moldura de texto de uma célula. Somente leitura [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Retorna o tipo de texto vertical. Leitura [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Retorna a largura da célula. Somente leitura **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógia do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógia da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógia do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógia do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Determina se a caixa de texto está centralizada dentro de uma célula. Escrita **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Define a margem inferior em um [TextFrame](../textframe/). Escrita **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Define a margem esquerda em um [TextFrame](../textframe/). Escrita **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Define a margem direita em um [TextFrame](../textframe/). Escrita **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Define a margem superior em um [TextFrame](../textframe/). Escrita **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Define o tipo de âncora de texto. Escrita [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Define o tipo de texto vertical. Escrita [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Divide a célula em duas células pelo índice da coluna. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Divide a célula pela altura. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Divide a célula em duas células pelo índice da linha. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Divide a célula pela largura. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógia do método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Veja Também

* Classe [IDOMObject](../idomobject/)
* Classe [ICell](../icell/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)