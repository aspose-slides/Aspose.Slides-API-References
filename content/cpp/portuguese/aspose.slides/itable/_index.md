---
title: ITable
second_title: Referência da API Aspose.Slides para C++
description: Representa uma tabela em um slide.
type: docs
weight: 4018
url: /pt/aspose.slides/itable/
---
## ITable classe


Representa uma tabela em um slide.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para fins internos. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Retorna o texto alternativo associado a uma forma. Leia [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Retorna o título do texto alternativo associado a uma forma. Leia [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leia [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | Retorna uma coluna no índice especificado. Somente leitura [Aspose::Slides::IColumn](../icolumn/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | Retorna a coleção de colunas. Somente leitura [IColumnCollection](../icolumncollection/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Retorna o número de pontos de conexão na forma. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Retorna os dados personalizados da forma. Somente leitura [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Retorna o objeto [EffectFormat](../effectformat/) que contém efeitos de pixel aplicados a uma forma. Somente leitura [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Retorna o objeto [FillFormat](../fillformat/) que contém propriedades de formatação de preenchimento para uma forma. Somente leitura [IFillFormat](../ifillformat/). |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | Determina se a primeira coluna de uma tabela deve ser desenhada com formatação especial. Leia **bool**. |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | Determina se a primeira linha de uma tabela deve ser desenhada com formatação especial. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Retorna as propriedades da moldura da forma. Leia [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Retorna os bloqueios da forma. Somente leitura [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Obtém a altura da forma, medida em pontos. Leia **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Determina se a forma está oculta. Leia **bool**. |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | Determina se as linhas pares devem ser desenhadas com formatação diferente. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Retorna o hyperlink definido para clique do mouse. Leia [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Gerenciador de hyperlinks. Somente leitura [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Retorna o hyperlink definido para passagem do mouse. Leia [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Obtém a opção 'Marcar como decorativo' Leitura/escrita **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Determina se a forma está agrupada. Somente leitura **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Determina se a forma é TextHolder. Somente leitura **bool**. |
| virtual **bool** [get_LastCol](./get_lastcol/)() | Determina se a última coluna de uma tabela deve ser desenhada com formatação especial. Leia **bool**. |
| virtual **bool** [get_LastRow](./get_lastrow/)() | Determina se a última linha de uma tabela deve ser desenhada com formatação especial. Leia **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Retorna o objeto [LineFormat](../lineformat/) que contém propriedades de formatação de linha para uma forma. Somente leitura [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Retorna o nome de uma forma. Leia [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Retorna um identificador exclusivo de escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código de interop faça referência confiável à forma a partir de qualquer ponto do documento. Somente leitura **uint32_t**. Veja também [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Retorna o objeto [GroupShape](../groupshape/) pai se a forma estiver agrupada. Caso contrário, retorna nulo. Somente leitura [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Retorna o placeholder para uma forma. Somente leitura [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Retorna as propriedades brutas da moldura da forma. Leia [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Determina se a tabela tem ordem de leitura da direita para a esquerda. Leia **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Retorna o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leia **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | Retorna uma linha no índice especificado. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | Retorna a coleção de linhas. Somente leitura [IRowCollection](../irowcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Retorna os bloqueios da forma. Somente leitura [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../ibaseslide/). |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | Obtém ou define o estilo de tabela interno. Leia [TableStylePreset](../tablestylepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | Retorna o objeto [TableFormat](../tableformat/) que contém propriedades de formatação para esta tabela. Somente leitura [ITableFormat](../itableformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Retorna o objeto [ThreeDFormat](../threedformat/) que contém propriedades de formatação de linha para uma forma. Somente leitura [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura **uint32_t**. Veja também [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | Determina se as colunas pares devem ser desenhadas com formatação diferente. Leia **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Obtém a largura da forma, medida em pontos. Leia **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Obtém a coordenada x do canto superior esquerdo da forma, medida em pontos. Leia **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Obtém a coordenada y do canto superior esquerdo da forma, medida em pontos. Leia **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Retorna a posição de uma forma na ordem Z. Shapes[0] retorna a forma no fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem Z. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Retorna a miniatura da forma. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) o tipo de limites de miniatura da forma é usado por padrão. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Retorna a miniatura da forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Retorna a célula nos índices de coluna e linha especificados. Somente leitura [ICell](../icell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | Mescla células vizinhas. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Define que esta forma não é um placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Define o texto alternativo associado a uma forma. Escreva [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Define o título do texto alternativo associado a uma forma. Escreva [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Escreva [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | Determina se a primeira coluna de uma tabela deve ser desenhada com formatação especial. Escreva **bool**. |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | Determina se a primeira linha de uma tabela deve ser desenhada com formatação especial. Escreva **bool**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Define as propriedades da moldura da forma. Escreva [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Define a altura da forma, medida em pontos. Escreva **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Determina se a forma está oculta. Escreva **bool**. |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | Determina se as linhas pares devem ser desenhadas com formatação diferente. Escreva **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Define o hyperlink definido para clique do mouse. Escreva [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Define o hyperlink definido para passagem do mouse. Escreva [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Define a opção 'Marcar como decorativo' Leitura/escrita **bool**. |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | Determina se a última coluna de uma tabela deve ser desenhada com formatação especial. Escreva **bool**. |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | Determina se a última linha de uma tabela deve ser desenhada com formatação especial. Escreva **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Define o nome de uma forma. Escreva [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Define as propriedades brutas da moldura da forma. Escreva [IShapeFrame](../ishapeframe/). |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | Determina se a tabela tem ordem de leitura da direita para a esquerda. Escreva **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Escreva **float**. |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | Obtém ou define o estilo de tabela interno. Escreva [TableStylePreset](../tablestylepreset/). |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | Determina se as colunas pares devem ser desenhadas com formatação diferente. Escreva **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Define a largura da forma, medida em pontos. Escreva **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Define a coordenada x do canto superior esquerdo da forma, medida em pontos. Escreva **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Define a coordenada y do canto superior esquerdo da forma, medida em pontos. Escreva **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n'th argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | Define propriedades de formato de porção definidas para todas as porções do elemento. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | Define propriedades de formato de parágrafo definidas para todos os parágrafos do elemento. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | Define propriedades de formato de quadro de texto definidas para todos os quadros de texto do elemento. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [IGraphicalObject](../igraphicalobject/)
* Classe [IBulkTextFormattable](../ibulktextformattable/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)