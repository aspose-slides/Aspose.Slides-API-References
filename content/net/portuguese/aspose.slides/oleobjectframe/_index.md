---
title: OleObjectFrame
second_title: Aspose.Sildes para a Referência de API .NET
description: Representa um objeto OLE em um slide.
type: docs
weight: 9210
url: /pt/aspose.slides/oleobjectframe/
---
## Classe OleObjectFrame

Representa um objeto OLE em um slide.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retorna ou define o texto alternativo associado a uma forma. Leitura/gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retorna ou define o título do texto alternativo associado a uma forma. Leitura/gravação String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Permite obter a interface base IGraphicalObject. Somente leitura [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura/gravação [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retorna o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retorna os dados personalizados da forma. Somente leitura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Obtém ou define informações sobre dados incorporados OLE. Leitura/gravação [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Retorna o nome do arquivo do objeto OLE incorporado |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Retorna o caminho do objeto OLE incorporado |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retorna ou define as propriedades da moldura da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retorna ou define o hiperlink definido para clique do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retorna o gerenciador de hiperlinks. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retorna ou define o hiperlink definido para passagem do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção 'Marcar como decorativo'. Leitura/gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Determina se um objeto é visível como ícone. Leitura/gravação Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Determina se um objeto está vinculado a um arquivo externo. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se a forma é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Retorna o caminho completo para um arquivo vinculado. O nome curto do arquivo será usado. Somente leitura String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Retorna o caminho completo para um arquivo vinculado. O nome longo do arquivo será usado. Leitura/gravação String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Retorna o caminho relativo para um arquivo vinculado, se presente; caso contrário, retorna uma string vazia. Somente leitura String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retorna ou define o nome de uma forma. Não pode ser nulo. Use uma string vazia se necessário. Leitura/gravação String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Retorna ou define o nome de um objeto. Leitura/gravação String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Retorna o ProgID de um objeto. Somente leitura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retorna um identificador exclusivo no escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer lugar no documento. Somente leitura UInt32. Veja também [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna null. Somente leitura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retorna o placeholder de uma forma. Retorna null se a forma não possui placeholder. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retorna a apresentação pai de um slide. Somente leitura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retorna ou define as propriedades brutas da moldura da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retorna ou define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriedades) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retorna o slide pai de uma forma. Somente leitura [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Retorna o objeto de propriedades de preenchimento de imagem OleObject. Somente leitura [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Retorna ou define o título para o ícone OleObject. Leitura/gravação String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retorna um identificador interno, no escopo da apresentação, destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Determina se o objeto incorporado vinculado é atualizado automaticamente quando a apresentação é aberta ou impressa. Leitura/gravação Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retorna a posição de uma forma na ordem Z. Shapes[0] retorna a forma na parte traseira da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem Z. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). Retorna null se a forma atual não for herdada. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retorna a miniatura da forma. O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retorna a miniatura da forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma não é um placeholder. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Define informações sobre dados incorporados OLE. Este método altera as propriedades do objeto para refletir os novos dados e define o sinalizador IsObjectLink como false, indicando que o objeto OLE está incorporado. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva o conteúdo da Shape como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva o conteúdo da Shape como arquivo SVG. |

### Exemplos

O exemplo a seguir mostra como acessar quadros de objeto OLE.

```csharp
[C#]
// Carrega o PPTX em um objeto de apresentação
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Acessa o primeiro slide
    ISlide sld = pres.Slides[0];
    // Faz cast da forma para OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Lê o objeto OLE e grava no disco
    if (oleObjectFrame != null)
    {
        // Obtém os dados do arquivo incorporado
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Obtém a extensão do arquivo incorporado
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Cria um caminho para salvar o arquivo extraído
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Salva os dados extraídos
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Veja Também

* classe [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->