---
title: VideoFrame
second_title: Aspose.Slides para Referência da API C++
description: Representa um clipe de vídeo em um slide.
type: docs
weight: 5552
url: /pt/aspose.slides/videoframe/
---
## VideoFrame classe

Representa um clipe de vídeo em um slide.

```cpp
class VideoFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IVideoFrame
```

## Métodos

| Método | Descrição |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Adiciona um novo placeholder se não houver nenhum e define as propriedades do placeholder para um especificado. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Cria e devolve um array dos elementos da forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Retorna o valor de ajuste da forma no índice especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Retorna uma coleção dos valores de ajuste da forma. Somente leitura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retorna o texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retorna o título do texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | A propriedade especifica como a forma será renderizada no modo de exibição preto e branco. Leitura [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Obtém a coleção de legendas fechadas associadas ao quadro de vídeo. Esta propriedade é somente leitura e devolve um [ICaptionsCollection](../icaptionscollection/) contendo todas as faixas de legendas. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retorna o número de pontos de conexão na forma. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retorna os dados personalizados da forma. Somente leitura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retorna o objeto [EffectFormat](../effectformat/) que contém os efeitos de pixel aplicados a uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() override | Retorna o objeto de vídeo incorporado. Leitura [IVideo](../ivideo/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retorna o objeto [FillFormat](../fillformat/) que contém as propriedades de formatação de preenchimento para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retorna as propriedades da moldura da forma. Leitura [IShapeFrame](../ishapeframe/). |
| **bool** [get_FullScreenMode](./get_fullscreenmode/)() override | Determina se um vídeo é exibido em modo tela cheia. Leitura **bool**. |
| **float** [get_Height](../shape/get_height/)() override | Obtém a altura da forma, medida em pontos. Leitura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina se a forma está oculta. Leitura **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Determina se um [VideoFrame](./) está oculto. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retorna o hyperlink definido para clique do mouse. Leitura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retorna o gerenciador de hyperlink. Somente leitura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retorna o hyperlink definido para mouse over. Leitura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Determina se o [PictureFrame](../pictureframe/) é um objeto Cameo ou não. Somente leitura **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtém a opção 'Marcar como decorativo' Leitura/gravação **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina se a forma está agrupada. Somente leitura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina se a forma é TextHolder_PPT. Somente leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retorna o objeto [LineFormat](../lineformat/) que contém as propriedades de formatação de linha para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de linha. Somente leitura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Retorna o nome de um arquivo de vídeo que está ligado a um [VideoFrame](./). Leitura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retorna o nome de uma forma. Não deve ser nulo. Use uma string vazia se necessário. Leitura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retorna um identificador único limitado ao slide que permanece constante durante a vida da forma e permite que o PowerPoint ou código interop a referencie de forma confiável de qualquer lugar no documento. Somente leitura **uint32_t**. Veja também [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retorna o objeto [GroupShape](../groupshape/) pai se a forma estiver agrupada. Caso contrário, retorna nulo. Somente leitura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Retorna o objeto [PictureFillFormat](../picturefillformat/) para um quadro de imagem. Somente leitura [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Retorna os bloqueios da forma. Somente leitura [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retorna o placeholder para uma forma. Retorna nulo se a forma não tiver placeholder. Somente leitura [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Determina se um vídeo está em loop. Leitura **bool**. |
| [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Retorna o modo de reprodução do vídeo. Leitura [VideoPlayModePreset](../videoplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retorna a apresentação pai de um slide. Somente leitura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retorna as propriedades brutas da moldura da forma. Leitura [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Retorna a escala da altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Retorna a escala da largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura **float**. |
| **bool** [get_RewindVideo](./get_rewindvideo/)() override | Determina se um vídeo é automaticamente rebobinado para o início assim que o filme terminar de ser reproduzido. Leitura **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retorna o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retorna os bloqueios da forma. Somente leitura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Retorna o objeto de estilo da forma. Somente leitura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retorna o slide pai de uma forma. Somente leitura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retorna o objeto [ThreeDFormat](../threedformat/) que contém as propriedades de efeito 3D para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades 3D. Somente leitura [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Cortar fim [ms] |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Cortar início [ms] |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retorna um identificador interno, limitado à apresentação, destinado ao uso por suplementos ou outro código. Como esse valor pode ser reasignado pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura **uint32_t**. Veja também [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Retorna o volume de áudio. Leitura [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_Width](../shape/get_width/)() override | Obtém a largura da forma, medida em pontos. Leitura **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtém a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtém a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retorna a posição de uma forma na ordem z. Shapes[0] devolve a forma mais à trás na ordem z, e Shapes[Shapes.Count - 1] devolve a forma mais à frente na ordem z. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Retorna a miniatura da forma. O tipo de limites da miniatura [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) é usado por padrão. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Retorna a miniatura da forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite construção por cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite construção por cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Define que esta forma não é um placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Define o texto alternativo associado a uma forma. Grava [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Define o título do texto alternativo associado a uma forma. Grava [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | A propriedade especifica como a forma será renderizada no modo preto e branco. Grava [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | Define o objeto de vídeo incorporado. Grava [IVideo](../ivideo/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Define as propriedades da moldura da forma. Grava [IShapeFrame](../ishapeframe/). |
| void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) override | Determina se um vídeo é exibido em modo tela cheia. Grava **bool**. |
| void [set_Height](../shape/set_height/)(**float**) override | Define a altura da forma, medida em pontos. Grava **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina se a forma está oculta. Grava **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Determina se um [VideoFrame](./) está oculto. Grava **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Define o hyperlink definido para clique do mouse. Grava [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Define o hyperlink definido para mouse over. Grava [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Define a opção 'Marcar como decorativo' Leitura/gravação **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Define o nome de um arquivo de vídeo que está ligado a um [VideoFrame](./). Grava [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Define o nome de uma forma. Não deve ser nulo. Use string vazia se necessário. Grava [System::String](../../system/string/). |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Determina se um vídeo está em loop. Grava **bool**. |
| void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) override | Define o modo de reprodução do vídeo. Grava [VideoPlayModePreset](../videoplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Define as propriedades brutas da moldura da forma. Grava [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Define a escala da altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Grava **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Define a escala da largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Grava **float**. |
| void [set_RewindVideo](./set_rewindvideo/)(**bool**) override | Determina se um vídeo é automaticamente rebobinado para o início assim que o filme termina. Grava **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Grava **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Cortar fim [ms] |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Cortar início [ms] |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Define o volume de áudio. Grava [AudioVolumeMode](../audiovolumemode/). |
| void [set_Width](../shape/set_width/)(**float**) override | Define a largura da forma, medida em pontos. Grava **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Define a coordenada x do canto superior esquerdo da forma, medida em pontos. Grava **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Define a coordenada y do canto superior esquerdo da forma, medida em pontos. Grava **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Atualiza a geometria da forma a partir do objeto [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Atualiza a geometria da forma a partir de um array de [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em containers para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use smart pointers ou ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Ver também

* Classe [PictureFrame](../pictureframe/)
* Classe [IVideoFrame](../ivideoframe/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)