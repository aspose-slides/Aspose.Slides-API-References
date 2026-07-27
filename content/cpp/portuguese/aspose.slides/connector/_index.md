---
title: Connector
second_title: Referência da API Aspose.Slides para C++
description: Representa um conector.
type: docs
weight: 482
url: /pt/aspose.slides/connector/
---
## Classe Connector

Representa um conector.

```cpp
class Connector : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IConnector
```

## Métodos

| Método | Descrição |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Cria e devolve um array dos elementos da forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Retorna o valor de ajuste da forma no índice especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Retorna uma coleção dos valores de ajuste da forma. Somente leitura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retorna o texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retorna o título do texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | A propriedade especifica como a forma será renderizada no modo de exibição preto-e-branco. Leitura [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retorna o número de pontos de conexão na forma. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() override | Retorna os travamentos do conector. Somente leitura [IConnectorLock](../iconnectorlock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retorna os dados personalizados da forma. Somente leitura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retorna o [EffectFormat](../effectformat/) objeto que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() override | Retorna a forma à qual anexar a extremidade do conector. Leitura [IShape](../ishape/). |
| **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() override | Retorna o índice do ponto de conexão para a forma final. Leitura **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retorna o [FillFormat](../fillformat/) objeto que contém propriedades de formatação de preenchimento para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retorna as propriedades da moldura da forma. Leitura [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Obtém a altura da forma, medida em pontos. Leitura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina se a forma está oculta. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retorna o hyperlink definido para clique do mouse. Leitura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retorna o gerenciador de hyperlink. Somente leitura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retorna o hyperlink definido para passagem do mouse. Leitura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtém a opção 'Marcar como decorativo' Leitura/gravação **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina se a forma está agrupada. Somente leitura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina se a forma é TextHolder_PPT. Somente leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retorna o [LineFormat](../lineformat/) objeto que contém propriedades de formatação de linha para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de linha. Somente leitura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retorna o nome de uma forma. Não pode ser null. Use string vazia se necessário. Leitura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retorna um identificador único de escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer ponto do documento. Somente leitura **uint32_t**. Veja também [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retorna o objeto pai [GroupShape](../groupshape/) se a forma estiver agrupada. Caso contrário, retorna null. Somente leitura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retorna o placeholder de uma forma. Retorna null se a forma não tiver placeholder. Somente leitura [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retorna a apresentação pai de um slide. Somente leitura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retorna as propriedades brutas da moldura da forma. Leitura [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retorna o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retorna os travamentos da forma. Somente leitura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Retorna o objeto de estilo da forma. Somente leitura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | Retorna o tipo [AutoShape](../autoshape/). Leitura [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retorna o slide pai de uma forma. Somente leitura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() override | Retorna a forma à qual anexar o início do conector. Leitura [IShape](../ishape/). |
| **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() override | Retorna o índice do ponto de conexão para a forma inicial. Leitura **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retorna o [ThreeDFormat](../threedformat/) objeto que contém propriedades de efeito 3D para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades 3D. Somente leitura [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura **uint32_t**. Veja também [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Obtém a largura da forma, medida em pontos. Leitura **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtém a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtém a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retorna a posição de uma forma na ordem z. Shapes[0] retorna a forma na parte traseira da ordem z, e Shapes[Shapes.Count - 1] retorna a forma na parte frontal da ordem z. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Retorna a cópia do caminho da forma de geometria. As coordenadas são relativas ao canto superior esquerdo da forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Retorna a miniatura da forma. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) tipo de limites da miniatura da forma é usado por padrão. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Retorna a miniatura da forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Define que esta forma não é um placeholder. |
| void [Reroute](./reroute/)() override | Redireciona o conector para que ele siga o caminho mais curto possível entre as formas que conecta. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Define o texto alternativo associado a uma forma. Gravação [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Define o título do texto alternativo associado a uma forma. Gravação [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | A propriedade especifica como a forma será renderizada no modo preto-e-branco. Gravação [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | Define a forma à qual anexar a extremidade do conector. Gravação [IShape](../ishape/). |
| void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) override | Define o índice do ponto de conexão para a forma final. Gravação **uint32_t**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Define as propriedades da moldura da forma. Gravação [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Define a altura da forma, medida em pontos. Gravação **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Define se a forma está oculta. Gravação **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Define o hyperlink definido para clique do mouse. Gravação [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Define o hyperlink definido para passagem do mouse. Gravação [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Define a opção 'Marcar como decorativo' Leitura/gravação **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Define o nome de uma forma. Não pode ser null. Use string vazia se necessário. Gravação [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Define as propriedades brutas da moldura da forma. Gravação [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Gravação **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | Define o tipo [AutoShape](../autoshape/). Gravação [Slides::ShapeType](../shapetype/). |
| void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | Define a forma à qual anexar o início do conector. Gravação [IShape](../ishape/). |
| void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) override | Define o índice do ponto de conexão para a forma inicial. Gravação **uint32_t**. |
| void [set_Width](../shape/set_width/)(**float**) override | Define a largura da forma, medida em pontos. Gravação **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Define a coordenada x do canto superior esquerdo da forma, medida em pontos. Gravação **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Define a coordenada y do canto superior esquerdo da forma, medida em pontos. Gravação **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Atualiza a geometria da forma a partir do objeto [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Atualiza a geometria da forma a partir de um array de [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [GeometryShape](../geometryshape/)
* Classe [IConnector](../iconnector/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)