---
title: IPictureFrame
second_title: Referência da API Aspose.Slides para C++
description: Representa um quadro com uma imagem dentro.
type: docs
weight: 3251
url: /pt/aspose.slides/ipictureframe/
---
## IPictureFrame classe

Representa um quadro com uma imagem dentro.

```cpp
class IPictureFrame : public virtual Aspose::Slides::IGeometryShape
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Adiciona um novo placeholder se não houver nenhum e define as propriedades do placeholder para um especificado. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Cria e retorna um array dos elementos da shape. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Retorna o valor de ajuste da shape no índice especificado. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Retorna uma coleção de valores de ajuste da shape. Somente leitura [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Retorna o texto alternativo associado a uma shape. Leitura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Retorna o título do texto alternativo associado a uma shape. Leitura [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | A propriedade especifica como uma shape será renderizada no modo de exibição preto e branco. Leitura [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Retorna o número de pontos de conexão na shape. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Retorna os dados customizados da shape. Somente leitura [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Retorna o objeto [EffectFormat](../effectformat/) que contém os efeitos de pixel aplicados a uma shape. Somente leitura [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Retorna o objeto [FillFormat](../fillformat/) que contém as propriedades de formatação de preenchimento para uma shape. Somente leitura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Retorna as propriedades do quadro da shape. Leitura [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Obtém a altura da shape, medida em pontos. Leitura **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Determina se a shape está oculta. Leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Retorna o hyperlink definido para clique do mouse. Leitura [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Gerenciador de hyperlinks Somente leitura [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Retorna o hyperlink definido para passagem do mouse. Leitura [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Obtém a opção 'Marcar como decorativo' Leitura/Escrita **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Determina se a shape está agrupada. Somente leitura **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Determina se a shape é TextHolder. Somente leitura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Retorna o objeto [LineFormat](../lineformat/) que contém as propriedades de formatação de linha para uma shape. Somente leitura [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Retorna o nome de uma shape. Leitura [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Retorna um identificador único de escopo de slide que permanece constante durante a vida da shape e permite que o PowerPoint ou código interop referencie a shape de forma confiável a partir de qualquer parte do documento. Somente leitura **uint32_t**. Veja também [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Retorna o objeto pai [GroupShape](../groupshape/) se a shape estiver agrupada. Caso contrário, retorna nulo. Somente leitura [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() | Retorna o objeto [PictureFillFormat](../picturefillformat/) para um quadro de imagem. Somente leitura [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() | Retorna os bloqueios de [PictureFrame](../pictureframe/). Somente leitura [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Retorna o placeholder para uma shape. Somente leitura [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Retorna a apresentação. Somente leitura [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Retorna as propriedades brutas do quadro da shape. Leitura [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() | Retorna a escala da altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura **float**. |
| virtual **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() | Retorna a escala da largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura **float**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Retorna o número de graus que a shape especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Retorna os bloqueios da shape. Somente leitura [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Retorna o objeto de estilo da shape. Somente leitura [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Retorna o tipo de preset de geometria. Nota: ao mudar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão. Leitura [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Retorna o slide base. Somente leitura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Retorna o objeto [ThreeDFormat](../threedformat/) que contém as propriedades de formatação de linha para uma shape. Somente leitura [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Retorna um identificador interno de escopo de apresentação destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura **uint32_t**. Veja também [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Obtém a largura da shape, medida em pontos. Leitura **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Obtém a coordenada x do canto superior esquerdo da shape, medida em pontos. Leitura **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Obtém a coordenada y do canto superior esquerdo da shape, medida em pontos. Leitura **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Retorna a posição de uma shape na ordem z. Shapes[0] retorna a shape na parte de trás da ordem z, e Shapes[Shapes.Count - 1] retorna a shape na frente da ordem z. Somente leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Retorna uma shape placeholder básica (shape do layout e/ou slide mestre da qual a shape atual herda). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Retorna a cópia do caminho da shape de geometria. As coordenadas são relativas ao canto superior esquerdo da shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Retorna a miniatura da shape. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) tipo de limites da miniatura da shape é usado por padrão. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Retorna a miniatura da shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, realmente, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, realmente, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Define que esta shape não é um placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Define o texto alternativo associado a uma shape. Escreve [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Define o título do texto alternativo associado a uma shape. Escreve [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | A propriedade especifica como uma shape será renderizada no modo preto e branco. Escreve [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Define as propriedades do quadro da shape. Escreve [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Define a altura da shape, medida em pontos. Escreve **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Determina se a shape está oculta. Escreve **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Define o hyperlink definido para clique do mouse. Escreve [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Define o hyperlink definido para passagem do mouse. Escreve [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Define a opção 'Marcar como decorativo' Leitura/Escrita **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Define o nome de uma shape. Escreve [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Define as propriedades brutas do quadro da shape. Escreve [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) | Define a escala da altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Escreve **float**. |
| virtual void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) | Define a escala da largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Escreve **float**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Define o número de graus que a shape especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Escreve **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Define o tipo de preset de geometria. Nota: ao mudar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão. Escreve [Slides::ShapeType](../shapetype/). |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Define a largura da shape, medida em pontos. Escreve **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Define a coordenada x do canto superior esquerdo da shape, medida em pontos. Escreve **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Define a coordenada y do canto superior esquerdo da shape, medida em pontos. Escreve **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Atualiza a geometria da shape a partir do objeto [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da shape. Altera o tipo da shape ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Atualiza a geometria da shape a partir de um array de [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da shape. Altera o tipo da shape ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IGeometryShape](../igeometryshape/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)