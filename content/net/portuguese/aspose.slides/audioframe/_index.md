---
title: AudioFrame
second_title: Aspose.Sildes para .NET Referência da API
description: Representa um clipe de áudio em um slide.
type: docs
weight: 850
url: /pt/aspose.slides/audioframe/
---
## AudioFrame classe

Representa um clipe de áudio em um slide.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retorna uma coleção de valores de ajuste da forma. Somente leitura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retorna ou define o texto alternativo associado a uma forma. Leitura/Gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retorna ou define o título do texto alternativo associado a uma forma. Leitura/Gravação String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Retorna ou define o índice da última faixa. Leitura/Gravação Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Retorna ou define o tempo da última faixa. Leitura/Gravação Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Retorna ou define o índice da faixa inicial. Leitura/Gravação Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Retorna ou define o tempo da faixa inicial. Leitura/Gravação Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura/Gravação [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Obtém a coleção de legendas fechadas associadas ao quadro de áudio. Esta propriedade é somente leitura e retorna um [`ICaptionsCollection`](../icaptionscollection) contendo todas as faixas de legenda. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retorna o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retorna os dados personalizados da forma. Somente leitura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar nulo para determinados tipos de formas que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Determina se um som está incorporado a uma apresentação. Somente leitura Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Retorna ou define o objeto de áudio incorporado. Leitura/Gravação [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Especifica a duração em milissegundos da transição de fade-in inicial da mídia. Leitura/Gravação Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Especifica a duração em milissegundos da transição de fade-out final da mídia. Leitura/Gravação Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retorna o objeto FillFormat que contém propriedades de preenchimento para uma forma. Observação: pode retornar nulo para determinados tipos de formas que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retorna ou define as propriedades da moldura da forma. Leitura/Gravação [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/Gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/Gravação Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Determina se um AudioFrame está oculto. Leitura/Gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retorna ou define o hiperlink definido para clique do mouse. Leitura/Gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retorna o gerenciador de hiperlink. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retorna ou define o hiperlink definido para passagem do mouse. Leitura/Gravação [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Determina se o PictureFrame é um objeto Cameo ou não. Somente leitura Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção 'Marcar como decorativo'. Leitura/Gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se a forma é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Observação: pode retornar nulo para determinados tipos de formas que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. Leitura/Gravação String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retorna ou define o nome de uma forma. Não pode ser nulo. Use uma string vazia se necessário. Leitura/Gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retorna um identificador exclusivo no escopo do slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável de qualquer lugar no documento. Somente leitura UInt32. Veja também [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna nulo. Somente leitura [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Retorna o objeto PictureFillFormat para um quadro de imagem. Somente leitura [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retorna o espaço reservado para uma forma. Retorna nulo se a forma não possuir espaço reservado. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Determina se o áudio está sendo reproduzido ao longo dos slides. Leitura/Gravação Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Determina se um áudio está em loop. Leitura/Gravação Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Retorna ou define o modo de reprodução de áudio. Leitura/Gravação [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retorna a apresentação pai de um slide. Somente leitura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retorna ou define as propriedades brutas da moldura da forma. Leitura/Gravação [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Retorna ou define a escala da altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/Gravação Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Retorna ou define a escala da largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/Gravação Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Determina se o áudio é automaticamente rebobinado para o início após a reprodução. Leitura/Gravação Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retorna ou define o número de graus que a forma especificada é rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/Gravação Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IPictureFrameLock`](../ipictureframelock). (2 propriedades) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retorna o objeto de estilo da forma. Somente leitura [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Retorna ou define o tipo AutoShape para um PictureFrame. Existem todos os itens permitidos do conjunto [`ShapeType`](../shapetype), exceto todos os tipos de linhas: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retorna o slide pai de uma forma. Somente leitura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma. Observação: pode retornar nulo para determinados tipos de formas que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Especifica a duração em milissegundos a ser removida do final da mídia durante a reprodução. Leitura/Gravação Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Especifica a duração em milissegundos a ser removida do início da mídia durante a reprodução. Leitura/Gravação Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retorna um identificador interno, no escopo da apresentação, destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Retorna ou define o volume do áudio. Leitura/Gravação [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Retorna ou define o volume do áudio em percentuais. Leitura/Gravação Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/Gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/Gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/Gravação Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retorna a posição de uma forma na ordem z. Shapes[0] retorna a forma na parte posterior da ordem z, e Shapes[Shapes.Count - 1] retorna a forma na parte frontal da ordem z. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adiciona um novo espaço reservado se não houver e define as propriedades do espaço reservado para um especificado. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Cria e retorna um array dos elementos da forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retorna uma forma de espaço reservado básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). Retorna nulo se a forma atual não for herdada. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retorna a miniatura da forma. O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retorna a miniatura da forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma não é um espaço reservado. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([`ShapeType`](../geometryshape/shapetype)) para Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([`ShapeType`](../geometryshape/shapetype)) para Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva o conteúdo da Forma como um arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva o conteúdo da Forma como um arquivo SVG. |

### Exemplos

Os exemplos a seguir mostram como alterar as Opções de Reprodução de Áudio.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Obtém a forma AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Define o modo de reprodução para reproduzir ao clicar
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Define o volume como Baixo
    audioFrame.Volume = AudioVolumeMode.Low;
    // Define o áudio para reproduzir em todos os slides
    audioFrame.PlayAcrossSlides = true;
    // Desativa o loop do áudio
    audioFrame.PlayLoopMode = false;
    // Oculta o AudioFrame durante a apresentação
    audioFrame.HideAtShowing = true;
    // Rebobina o áudio para o início após a reprodução
    audioFrame.RewindAudio = true;
    // Salva o arquivo PowerPoint no disco
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Ver Também

* classe [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->