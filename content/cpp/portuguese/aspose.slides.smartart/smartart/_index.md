---
title: SmartArt
second_title: Referência da API Aspose.Slides para C++
description: Representa um diagrama SmartArt
type: docs
weight: 66
url: /pt/aspose.slides.smartart/smartart/
---
## SmartArt classe

Representa um diagrama [SmartArt](./)

```cpp
class SmartArt : public Aspose::Slides::GraphicalObject,
                 public Aspose::Slides::SmartArt::ISmartArt
```

## Métodos

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() override | Retorna coleções de todos os nós no objeto [SmartArt](./). Somente leitura [ISmartArtNodeCollection](../ismartartnodecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Retorna o texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Retorna o título do texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() override | Retorna o estilo de cor do objeto [SmartArt](./). Leitura [SmartArtColorType](../smartartcolortype/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Retorna o número de pontos de conexão na forma. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Retorna os dados personalizados da forma. Somente leitura [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Retorna o objeto [EffectFormat](../../aspose.slides/effectformat/) que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Retorna o objeto [FillFormat](../../aspose.slides/fillformat/) que contém propriedades de formatação de preenchimento para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Retorna as propriedades da moldura da forma. Leitura [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Retorna os bloqueios da forma. Somente leitura [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Obtém a altura da forma, medida em pontos. Leitura **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Determina se a forma está oculta. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Retorna o hyperlink definido para clique do mouse. Leitura [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Retorna o gerenciador de hyperlink. Somente leitura [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Retorna o hyperlink definido para passar o mouse. Leitura [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Obtém a opção 'Mark as decorative' Leitura/Gravação **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Determina se a forma está agrupada. Somente leitura **bool**. |
| **bool** [get_IsReversed](./get_isreversed/)() override | Retorna ou define o estado do diagrama [SmartArt](./) em relação a (da esquerda para a direita) LTR ou (da direita para a esquerda) RTL, se o diagrama suportar reversão. Leitura **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Determina se a forma é TextHolder_PPT. Somente leitura **bool**. |
| [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() override | Retorna o layout do objeto [SmartArt](./). Leitura [SmartArtLayoutType](../smartartlayouttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Retorna o objeto [LineFormat](../../aspose.slides/lineformat/) que contém propriedades de formatação de linha para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de linha. Somente leitura [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Retorna o nome de uma forma. Não deve ser nulo. Use string vazia se necessário. Leitura [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) override | Retorna um nó da coleção de nós raiz no objeto [SmartArt](./) no índice especificado. Somente leitura [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) override | Retorna um nó da coleção com todos os nós no objeto [SmartArt](./) no índice especificado. Somente leitura [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() override | Retorna coleções de nós raiz no objeto [SmartArt](./). Somente leitura [ISmartArtNodeCollection](../ismartartnodecollection/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Retorna um identificador único de escopo de slide que permanece constante durante a vida da forma e permite que PowerPoint ou código de interop referenciem a forma de forma confiável a partir de qualquer ponto no documento. Somente leitura **uint32_t**. Veja também [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Retorna o objeto [GroupShape](../../aspose.slides/groupshape/) pai se a forma for agrupada. Caso contrário, retorna null. Somente leitura [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Retorna o placeholder de uma forma. Retorna null se a forma não tiver placeholder. Somente leitura [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Retorna a apresentação pai de um slide. Somente leitura [IPresentation](../../aspose.slides/ipresentation/). |
| [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() override | Retorna o estilo rápido do objeto [SmartArt](./). Leitura [SmartArtQuickStyleType](../smartartquickstyletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Retorna as propriedades brutas da moldura da forma. Leitura [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Retorna o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Retorna os bloqueios da forma. Somente leitura [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Retorna o slide pai de uma forma. Somente leitura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Retorna o objeto [ThreeDFormat](../../aspose.slides/threedformat/) que contém propriedades de efeito 3D para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades 3D. Somente leitura [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por add-ins ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura **uint32_t**. Veja também [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Obtém a largura da forma, medida em pontos. Leitura **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Obtém a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Obtém a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Retorna a posição de uma forma na ordem z. Shapes[0] retorna a forma na parte traseira da ordem z, e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem z. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Retorna uma forma de placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Retorna a miniatura da forma. O tipo de limites da miniatura da forma [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) é usado por padrão. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Retorna a miniatura da forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias nas subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias nas subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Define que esta forma não é um placeholder. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Define o texto alternativo associado a uma forma. Escrita [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Define o título do texto alternativo associado a uma forma. Escrita [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | A propriedade especifica como uma forma será renderizada no modo preto e branco. Escrita [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) override | Define o estilo de cor do objeto [SmartArt](./). Escrita [SmartArtColorType](../smartartcolortype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Define as propriedades da moldura da forma. Escrita [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Define a altura da forma, medida em pontos. Escrita **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Define se a forma está oculta. Escrita **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Define o hyperlink definido para clique do mouse. Escrita [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Define o hyperlink definido para passar o mouse. Escrita [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Define a opção 'Mark as decorative' Leitura/Gravação **bool**. |
| void [set_IsReversed](./set_isreversed/)(**bool**) override | Retorna ou define o estado do diagrama [SmartArt](./) em relação a (da esquerda para a direita) LTR ou (da direita para a esquerda) RTL, se o diagrama suportar reversão. Escrita **bool**. |
| void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) override | Define o layout do objeto [SmartArt](./). Escrita [SmartArtLayoutType](../smartartlayouttype/). |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Define o nome de uma forma. Não deve ser nulo. Use string vazia se necessário. Escrita [System::String](../../system/string/). |
| void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) override | Define o estilo rápido do objeto [SmartArt](./). Escrita [SmartArtQuickStyleType](../smartartquickstyletype/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Define as propriedades brutas da moldura da forma. Escrita [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Escrita **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Define a largura da forma, medida em pontos. Escrita **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Define a coordenada x do canto superior esquerdo da forma, medida em pontos. Escrita **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Define a coordenada y do canto superior esquerdo da forma, medida em pontos. Escrita **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva o conteúdo de [Shape](../../aspose.slides/shape/) como arquivo SVG. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva o conteúdo de [Shape](../../aspose.slides/shape/) como arquivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [GraphicalObject](../../aspose.slides/graphicalobject/)
* Classe [ISmartArt](../ismartart/)
* Namespace [Aspose::Slides::SmartArt](../)
* Biblioteca [Aspose.Slides](../../)