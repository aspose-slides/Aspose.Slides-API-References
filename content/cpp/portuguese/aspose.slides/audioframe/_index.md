---
title: AudioFrame
second_title: Referência da API Aspose.Slides para C++
description: Representa um clipe de áudio em um slide.
type: docs
weight: 53
url: /pt/aspose.slides/audioframe/
---
## AudioFrame classe

Representa um clipe de áudio em um slide.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Métodos

| Método | Descrição |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Cria e retorna um array dos elementos da forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não é igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Retorna o valor de ajuste de uma forma no índice especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Retorna uma coleção dos valores de ajuste da forma. Somente leitura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retorna o texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retorna o título do texto alternativo associado a uma forma. Leitura [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Retorna o índice da última faixa. Leitura **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Retorna o tempo da última faixa. Leitura **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Retorna o índice da faixa inicial. Leitura **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Retorna o tempo da faixa inicial. Leitura **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Obtém a coleção de legendas fechadas associadas ao quadro de áudio. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../icaptionscollection/) contendo todas as faixas de legenda. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retorna o número de pontos de conexão na forma. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retorna os dados personalizados da forma. Somente leitura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retorna o objeto [EffectFormat](../effectformat/) que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Determina se um som está incorporado à apresentação. Somente leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Retorna o objeto de áudio incorporado. Leitura [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Especifica a duração em milissegundos do fade-in inicial da mídia. Leitura **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Especifica a duração em milissegundos do fade-out final da mídia. Leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retorna o objeto [FillFormat](../fillformat/) que contém propriedades de formatação de preenchimento para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retorna as propriedades do quadro da forma. Leitura [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Obtém a altura da forma, medida em pontos. Leitura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina se a forma está oculta. Leitura **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Determina se um [AudioFrame](./) está oculto. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retorna o hyperlink definido para clique do mouse. Leitura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retorna o gerenciador de hyperlinks. Somente leitura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retorna o hyperlink definido para mouse over. Leitura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Determina se o [PictureFrame](../pictureframe/) é objeto Cameo ou não. Somente leitura **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtém a opção “Marcar como decorativo”. Leitura/gravação **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina se a forma está agrupada. Somente leitura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina se a forma é TextHolder_PPT. Somente leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retorna o objeto [LineFormat](../lineformat/) que contém propriedades de formatação de linha para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de linha. Somente leitura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Retorna o nome de um arquivo de áudio vinculado a um [AudioFrame](./). Leitura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retorna o nome de uma forma. Não pode ser nulo. Use string vazia se necessário. Leitura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retorna um identificador exclusivo em escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável. Somente leitura **uint32_t**. Veja também [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retorna o objeto pai [GroupShape](../groupshape/) se a forma estiver agrupada. Caso contrário, retorna nulo. Somente leitura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Retorna o objeto [PictureFillFormat](../picturefillformat/) para um quadro de imagem. Somente leitura [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Retorna os bloqueios da forma. Somente leitura [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retorna o placeholder de uma forma. Retorna nulo se a forma não possuir placeholder. Somente leitura [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Determina se o áudio está sendo reproduzido nas slides. Leitura **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Determina se um áudio está em loop. Leitura **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Retorna o modo de reproduçãodo áudio. Leitura [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retorna a apresentação pai de um slide. Somente leitura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retorna as propriedades brutas do quadro da forma. Leitura [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Retorna a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1,0 corresponde a 100 %. Leitura **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Retorna a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1,0 corresponde a 100 %. Leitura **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Determina se o áudio é reenrolado automaticamente para o início após a reprodução. Leitura **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retorna o número de graus que a forma especificada está rotacionada ao redor do eixo Z. Valor positivo indica rotação no sentido horário; valor negativo indica rotação no sentido anti-horário. Leitura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retorna os bloqueios da forma. Somente leitura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Retorna o objeto de estilo da forma. Somente leitura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retorna o slide pai de uma forma. Somente leitura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retorna o objeto [ThreeDFormat](../threedformat/) que contém propriedades de efeito 3D para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades 3D. Somente leitura [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Especifica a duração em milissegundos a ser removida do final da mídia durante a reprodução. Leitura **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Especifica a duração em milissegundos a ser removida do início da mídia durante a reprodução. Leitura **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retorna um identificador interno em escopo de apresentação destinado ao uso por complementos ou outro código. Como este valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como chave única persistente. Somente leitura **uint32_t**. Veja também [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Retorna o volume do áudio. Leitura [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Retorna o volume do áudio em porcentagem. Leitura **float**. |
| **float** [get_Width](../shape/get_width/)() override | Obtém a largura da forma, medida em pontos. Leitura **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtém a coordenada X do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtém a coordenada Y do canto superior esquerdo da forma, medida em pontos. Leitura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retorna a posição de uma forma na ordem Z. Shapes[0] retorna a forma mais ao fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma mais ao frente. Somente leitura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual herdou). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de contagem de referências associada ao objeto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Retorna a miniatura da forma. O tipo padrão usado é [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatura de forma. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Retorna a miniatura da forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# “is”. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e habilita a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e habilita a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui a contagem de referência compartilhada pelo valor especificado. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Define que esta forma não é um placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Define o texto alternativo associado a uma forma. Grava [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Define o título do texto alternativo associado a uma forma. Grava [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Define o índice da última faixa. Grava **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Define o tempo da última faixa. Grava **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Define o índice da faixa inicial. Grava **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Define o tempo da faixa inicial. Grava **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Grava [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Define o objeto de áudio incorporado. Grava [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Especifica a duração em milissegundos do fade-in inicial da mídia. Grava **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Especifica a duração em milissegundos do fade-out final da mídia. Grava **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Define as propriedades do quadro da forma. Grava [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Define a altura da forma, medida em pontos. Grava **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina se a forma está oculta. Grava **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Determina se um [AudioFrame](./) está oculto. Grava **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Define o hyperlink para clique do mouse. Grava [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Define o hyperlink para mouse over. Grava [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Define a opção “Marcar como decorativo”. Grava/grava **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Define o nome de um arquivo de áudio vinculado a um [AudioFrame](./). Grava [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Define o nome de uma forma. Não pode ser nulo. Use string vazia se necessário. Grava [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Determina se o áudio está sendo reproduzido nas slides. Grava **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Determina se um áudio está em loop. Grava **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Define o modo de reprodução do áudio. Grava [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Define as propriedades brutas do quadro da forma. Grava [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1,0 corresponde a 100 %. Grava **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1,0 corresponde a 100 %. Grava **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Determina se o áudio é reenrolado automaticamente para o início após a reprodução. Grava **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Define o número de graus que a forma especificada está rotacionada ao redor do eixo Z. Valor positivo indica rotação horário; valor negativo indica rotação anti-horário. Grava **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Especifica a duração em milissegundos a ser removida do final da mídia durante a reprodução. Grava **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Especifica a duração em milissegundos a ser removida do início da mídia durante a reprodução. Grava **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Define o volume do áudio. Grava [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Define o volume do áudio em porcentagem. Grava **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Define a largura da forma, medida em pontos. Grava **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Define a coordenada X do canto superior esquerdo da forma, medida em pontos. Grava **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Define a coordenada Y do canto superior esquerdo da forma, medida em pontos. Grava **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Atualiza a geometria da forma a partir do objeto [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Atualiza a geometria da forma a partir de um array de [IGeometryPath](../igeometrypath/). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([ShapeType](../shapetype/)) para [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva o conteúdo de [Shape](../shape/) como arquivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

O exemplo a seguir mostra como alterar as Opções de Reprodução [Audio](../audio/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Ver também

* Classe [PictureFrame](../pictureframe/)
* Classe [IAudioFrame](../iaudioframe/)
* Espaço de nomes [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)