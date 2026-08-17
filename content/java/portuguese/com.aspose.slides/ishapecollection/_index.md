---
title: IShapeCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de formas.
type: docs
url: /pt/com.aspose.slides/ishapecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Representa uma coleção de formas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getParentGroup()](#getParentGroup--) | Obtém o objeto de forma de grupo pai para a coleção de formas. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Cria um diagrama SmartArt e o adiciona ao final da coleção de formas. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Cria um novo quadro de Zoom de seção e o adiciona ao final da coleção de formas. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom de seção com uma imagem predefinida e o adiciona ao final da coleção de formas. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Cria um novo quadro de Zoom de seção e o insere na coleção de formas no índice especificado. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom de seção com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Cria um novo quadro de Zoom de resumo e o adiciona ao final da coleção de formas. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Cria um novo quadro de Zoom de resumo e o insere na coleção de formas no índice especificado. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o adiciona ao final da coleção de formas. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o insere na coleção de formas no índice especificado. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o adiciona ao final da coleção de formas. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas no índice especificado. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Retorna o índice baseado em zero da primeira ocorrência da forma especificada na coleção. |
| [toArray()](#toArray--) | Cria e retorna um array que contém todas as formas. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e retorna um array que contém todas as formas no intervalo especificado. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Move a forma especificada para uma nova posição dentro da coleção de formas. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação de modelo padrão. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Cria uma nova forma automática retangular para hospedar conteúdo matemático e a adiciona ao final da coleção de formas. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação de modelo padrão. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com o estilo de modelo padrão. |
| [addGroupShape()](#addGroupShape--) | Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Cria uma nova forma de grupo, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Cria uma nova forma de grupo vazia e a insere na coleção de formas no índice especificado. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Cria uma nova forma de conector e a adiciona ao final da coleção de formas, opcionalmente aplicando o estilo de modelo padrão. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, aplicando o estilo de modelo padrão. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, opcionalmente aplicando o estilo de modelo padrão. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de formas no índice especificado. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Cria uma nova tabela e a adiciona ao final da coleção de formas. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Cria uma nova tabela e a insere na coleção de formas no índice especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove a forma no índice especificado da coleção de formas. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Remove a primeira ocorrência da forma especificada da coleção de formas. |
| [clear()](#clear--) | Remove todas as formas da coleção de formas. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Obtém o objeto de forma de grupo pai para a coleção de formas. Somente leitura [IGroupShape](../../com.aspose.slides/igroupshape).

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tipo de gráfico a ser adicionado. |
| x | float | A coordenada x do novo gráfico, em pontos. |
| y | float | A coordenada y do novo gráfico, em pontos. |
| width | float | A largura do gráfico, em pontos. |
| height | float | A altura do gráfico, em pontos. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O recém-criado [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tipo de gráfico a ser adicionado. |
| x | float | A coordenada x do novo gráfico, em pontos. |
| y | float | A coordenada y do novo gráfico, em pontos. |
| width | float | A largura do gráfico, em pontos. |
| height | float | A altura do gráfico, em pontos. |
| initWithSample | boolean | True para inicializar o novo gráfico com dados de série de exemplo e configurações; false para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O recém-criado [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Cria um diagrama SmartArt e o adiciona ao final da coleção de formas.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x da moldura do diagrama, em pontos. |
| y | float | A coordenada y da moldura do diagrama, em pontos. |
| width | float | A largura da moldura do diagrama, em pontos. |
| height | float | A altura da moldura do diagrama, em pontos. |
| layoutType | int | O tipo de layout SmartArt. |

**Retorna:**
[ISmartArt](../../com.aspose.slides/ismartart) - O recém-criado [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tipo de gráfico a ser criado. |
| x | float | A coordenada x do novo gráfico, em pontos. |
| y | float | A coordenada y do novo gráfico, em pontos. |
| width | float | A largura do novo gráfico, em pontos. |
| height | float | A altura do novo gráfico, em pontos. |
| index | int | O índice baseado em zero onde inserir o novo gráfico na coleção de formas. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O recém-criado [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tipo de gráfico a ser criado. |
| x | float | A coordenada x do novo gráfico, em pontos. |
| y | float | A coordenada y do novo gráfico, em pontos. |
| width | float | A largura do novo gráfico, em pontos. |
| height | float | A altura do novo gráfico, em pontos. |
| index | int | O índice baseado em zero onde inserir o novo gráfico na coleção de formas. |
| initWithSample | boolean | True para inicializar o novo gráfico com dados de série de exemplo e configurações; false para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |
| initWithSample | boolean | True para inicializar o novo gráfico com dados e configurações de séries de exemplo; false para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

**Retorna:**
[IChart](../../com.aspose.slides/ichart) - O [IChart](../../com.aspose.slides/ichart) recém-criado.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro OLE, em pontos. |
| y | float | A coordenada y do novo quadro OLE, em pontos. |
| width | float | A largura do novo quadro OLE, em pontos. |
| height | float | A altura do novo quadro OLE, em pontos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | As informações de dados OLE incorporados ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retorna:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recém-criado.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro OLE, em pontos. |
| y | float | A coordenada y do novo quadro OLE, em pontos. |
| width | float | A largura do novo quadro OLE, em pontos. |
| height | float | A altura do novo quadro OLE, em pontos. |
| className | java.lang.String | O nome da classe do objeto OLE. |
| path | java.lang.String | O caminho para o arquivo vinculado.

Este caminho é armazenado literalmente na apresentação. Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir a apresentação a partir de um diretório diferente. |

**Retorna:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recém-criado.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o quadro de objeto OLE será inserido. |
| x | float | A coordenada x do novo quadro OLE, em pontos. |
| y | float | A coordenada y do novo quadro OLE, em pontos. |
| width | float | A largura do novo quadro OLE, em pontos. |
| height | float | A altura do novo quadro OLE, em pontos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | As informações de dados OLE incorporados ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retorna:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recém-criado.
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o quadro de objeto OLE será inserido. |
| x | float | A coordenada x do novo quadro OLE, em pontos. |
| y | float | A coordenada y do novo quadro OLE, em pontos. |
| width | float | A largura do novo quadro OLE, em pontos. |
| height | float | A altura do novo quadro OLE, em pontos. |
| className | java.lang.String | O nome da classe do objeto OLE. |
| path | java.lang.String | O caminho para o arquivo vinculado.

Este caminho é armazenado literalmente na apresentação. Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir a apresentação a partir de um diretório diferente. |

**Retorna:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recém-criado.
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de Zoom, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom, em pontos. |
| width | float | A largura do novo quadro de Zoom, em pontos. |
| height | float | A altura do novo quadro de Zoom, em pontos. |
| slide | [ISlide](../../com.aspose.slides/islide) | O [ISlide](../../com.aspose.slides/islide) referenciado pelo quadro de Zoom; deve pertencer a esta apresentação. |

**Retorna:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - O [IZoomFrame](../../com.aspose.slides/izoomframe) recém-criado.
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de Zoom, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom, em pontos. |
| width | float | A largura do novo quadro de Zoom, em pontos. |
| height | float | A altura do novo quadro de Zoom, em pontos. |
| slide | [ISlide](../../com.aspose.slides/islide) | O [ISlide](../../com.aspose.slides/islide) referenciado pelo quadro de Zoom; deve pertencer a esta apresentação. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A imagem para o slide referenciado [IPPImage](../../com.aspose.slides/ippimage). |

**Retorna:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - O [IZoomFrame](../../com.aspose.slides/izoomframe) recém-criado.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o quadro de Zoom será inserido. |
| x | float | A coordenada x do novo quadro de Zoom, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom, em pontos. |
| width | float | A largura do novo quadro de Zoom, em pontos. |
| height | float | A altura do novo quadro de Zoom, em pontos. |
| slide | [ISlide](../../com.aspose.slides/islide) | O [ISlide](../../com.aspose.slides/islide) referenciado pelo quadro de Zoom. |

**Retorna:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - O [IZoomFrame](../../com.aspose.slides/izoomframe) recém-criado.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Cria um novo quadro de Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o quadro de Zoom será inserido. |
| x | float | A coordenada x do novo quadro de Zoom, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom, em pontos. |
| width | float | A largura do novo quadro de Zoom, em pontos. |
| height | float | A altura do novo quadro de Zoom, em pontos. |
| slide | [ISlide](../../com.aspose.slides/islide) | O [ISlide](../../com.aspose.slides/islide) referenciado pelo quadro de Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A imagem para o slide referenciado [IPPImage](../../com.aspose.slides/ippimage). |

**Retorna:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - O [IZoomFrame](../../com.aspose.slides/izoomframe) recém-criado.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Cria um novo quadro de Zoom de Seção e o adiciona ao final da coleção de formas.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de Zoom de Seção, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom de Seção, em pontos. |
| width | float | A largura do novo quadro de Zoom de Seção, em pontos. |
| height | float | A altura do novo quadro de Zoom de Seção, em pontos. |
| section | [ISection](../../com.aspose.slides/isection) | O [ISection](../../com.aspose.slides/isection) referenciado pelo quadro de Zoom de Seção; deve pertencer a esta apresentação e conter ao menos um slide. |

**Retorna:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - O [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recém-criado.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o adiciona ao final da coleção de formas.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de Zoom de Seção, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom de Seção, em pontos. |
| width | float | A largura do novo quadro de Zoom de Seção, em pontos. |
| height | float | A altura do novo quadro de Zoom de Seção, em pontos. |
| section | [ISection](../../com.aspose.slides/isection) | O [ISection](../../com.aspose.slides/isection) referenciado pelo quadro de Zoom de Seção; deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | O [IPPImage](../../com.aspose.slides/ippimage) a ser exibido dentro do quadro de Zoom de Seção. |

**Retorna:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - O [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recém-criado.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Cria um novo quadro de Zoom de Seção e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Section Zoom no índice especificado de uma coleção
>  (assuma que existam pelo menos duas seções na apresentação "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o quadro de Zoom de Seção será inserido. |
| x | float | A coordenada x do novo quadro de Zoom de Seção, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom de Seção, em pontos. |
| width | float | A largura do novo quadro de Zoom de Seção, em pontos. |
| height | float | A altura do novo quadro de Zoom de Seção, em pontos. |
| section | [ISection](../../com.aspose.slides/isection) | O [ISection](../../com.aspose.slides/isection) referenciado pelo quadro de Zoom de Seção; deve pertencer a esta apresentação e conter ao menos um slide. |

**Retorna:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - O [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recém-criado.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Section Zoom no índice especificado de uma coleção
>  (assuma que existam pelo menos duas seções na apresentação "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde o quadro de Zoom de Seção será inserido. |
| x | float | A coordenada x do novo quadro de Zoom de Seção, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom de Seção, em pontos. |
| width | float | A largura do novo quadro de Zoom de Seção, em pontos. |
| height | float | A altura do novo quadro de Zoom de Seção, em pontos. |
| section | [ISection](../../com.aspose.slides/isection) | O [ISection](../../com.aspose.slides/isection) referenciado pelo quadro de Zoom de Seção; deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | A imagem a ser exibida dentro do quadro de Zoom de Seção. |

**Retorna:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - O [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recém-criado.
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Cria um novo quadro de Zoom de Resumo e o adiciona ao final da coleção de formas.

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de Zoom de Resumo, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom de Resumo, em pontos. |
| width | float | A largura do novo quadro de Zoom de Resumo, em pontos. |
| height | float | A altura do novo quadro de Zoom de Resumo, em pontos. |
Este método cria um quadro Summary Zoom que agrega links de resumo para todas as seções da apresentação. |

**Retorno:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - O [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) recém-criado.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Cria um novo quadro Summary Zoom e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Summary Zoom no índice especificado de uma coleção
>  (assuma que existam pelo menos duas seções na apresentação "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro Summary Zoom. |
| x | float | A coordenada x do novo quadro Summary Zoom, em pontos. |
| y | float | A coordenada y do novo quadro Summary Zoom, em pontos. |
| width | float | A largura do novo quadro Summary Zoom, em pontos. |
| height | float | A altura do novo quadro Summary Zoom, em pontos. |

--------------------

Este método cria um quadro Summary Zoom que agrega links de resumo para todas as seções da apresentação. |

**Retorno:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - O [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) recém-criado.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de vídeo, em pontos. |
| y | float | A coordenada y do novo quadro de vídeo, em pontos. |
| width | float | A largura do novo quadro de vídeo, em pontos. |
| height | float | A altura do novo quadro de vídeo, em pontos. |
| fname | java.lang.String | O caminho ou nome do arquivo de vídeo a incorporar. |

**Retorno:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - O [IVideoFrame](../../com.aspose.slides/ivideoframe) recém-criado.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de vídeo, em pontos. |
| y | float | A coordenada y do novo quadro de vídeo, em pontos. |
| width | float | A largura do novo quadro de vídeo, em pontos. |
| height | float | A altura do novo quadro de vídeo, em pontos. |
| video | [IVideo](../../com.aspose.slides/ivideo) | O [IVideo](../../com.aspose.slides/ivideo) a ser incorporado no quadro de vídeo. |

**Retorno:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - O [IVideoFrame](../../com.aspose.slides/ivideoframe) recém-criado.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de vídeo. |
| x | float | A coordenada x do novo quadro de vídeo, em pontos. |
| y | float | A coordenada y do novo quadro de vídeo, em pontos. |
| width | float | A largura do novo quadro de vídeo, em pontos. |
| height | float | A altura do novo quadro de vídeo, em pontos. |
| fname | java.lang.String | O caminho ou nome do arquivo de vídeo a incorporar. |

**Retorno:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - O [IVideoFrame](../../com.aspose.slides/ivideoframe) recém-criado.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Cria um novo quadro de áudio vinculado a uma faixa de CD e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Cria um novo quadro de áudio vinculado a uma faixa de CD e o insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| fname | java.lang.String | O caminho ou nome do arquivo de áudio externo a vincular. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| fname | java.lang.String | O caminho ou nome do arquivo de áudio externo a vincular. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| audio_stream | java.io.InputStream | Um fluxo de entrada contendo dados de áudio WAV a incorporar. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista Presentation.Audios.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Uma instância [IAudio](../../com.aspose.slides/iaudio) da coleção Presentation.Audios. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção Presentation.Audios.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| audio_stream | java.io.InputStream | Um fluxo de entrada contendo dados de áudio WAV a incorporar. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Uma instância [IAudio](../../com.aspose.slides/iaudio) da coleção Presentation.Audios a ser incorporada. |

**Retorno:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Retorna o índice baseado em zero da primeira ocorrência da forma especificada na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A forma a localizar na coleção. |

**Retorno:**
int - O índice baseado em zero da primeira ocorrência da forma na coleção de formas, se encontrada; caso contrário, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Cria e retorna um array que contém todas as formas.

**Retorno:**
com.aspose.slides.IShape[] - Um array de objetos [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Cria e retorna um array que contém todas as formas no intervalo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | O índice da primeira forma a ser retornada. |
| count | int | O número de formas a ser retornado. |

**Retorno:**
com.aspose.slides.IShape[] - Um array de objetos [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Move a forma especificada para uma nova posição dentro da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde a forma será colocada. |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a ser movida dentro da coleção. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde a primeira forma especificada será colocada; as formas subsequentes seguem na ordem fornecida. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Uma ou mais instâncias [IShape](../../com.aspose.slides/ishape) a serem movidas dentro da coleção. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma automática a ser adicionada. |

| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - O recém-criado [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação de modelo padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma automática a ser adicionada. |
| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |
| createFromTemplate | boolean | True para aplicar o estilo de modelo padrão (estilo simples, texto centralizado e nome não vazio) à nova forma; false para criar a forma com todas as propriedades definidas com seus valores padrão. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - O recém-criado [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Cria uma nova forma automática retangular para hospedar conteúdo matemático e a adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - O recém-criado [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação de modelo padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a nova forma automática. |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma automática a ser inserida. |
| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - O recém-criado [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com o estilo de modelo padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma automática. |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma automática a ser inserida. |
| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |
| createFromTemplate | boolean | True para aplicar o estilo de modelo padrão (incluindo um nome não vazio, estilo simples e texto centralizado); false para criar a forma com todas as propriedades definidas com seus valores padrão. |

**Retorna:**
[IAutoShape](../../com.aspose.slides/iautoshape) - O recém-criado [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Cria um novo grupo de formas vazio e o adiciona ao final da coleção de formas. A moldura do grupo será ajustada automaticamente para acomodar quaisquer formas adicionadas a ele.

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape) - O recém-criado [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Cria um novo grupo de formas, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | O [ISvgImage](../../com.aspose.slides/isvgimage) contendo conteúdo vetorial a ser convertido em formas. |
| x | float | A coordenada x da moldura do grupo, em pontos. |
| y | float | A coordenada y da moldura do grupo, em pontos. |
| width | float | A largura da moldura do grupo, em pontos. |
| height | float | A altura da moldura do grupo, em pontos. |

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape) - O recém-criado [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Cria um novo grupo de formas vazio e o insere na coleção de formas no índice especificado. A moldura do grupo será ajustada automaticamente para acomodar quaisquer formas adicionadas a ele.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o grupo de formas. |

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape) - O recém-criado [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma de conector a ser adicionada. |
| x | float | A coordenada x da moldura do conector, em pontos. |
| y | float | A coordenada y da moldura do conector, em pontos. |
| width | float | A largura da moldura do conector, em pontos. |
| height | float | A altura da moldura do conector, em pontos. |

**Retorna:**
[IConnector](../../com.aspose.slides/iconnector) - O recém-criado [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma de conector e a adiciona ao final da coleção de formas, opcionalmente aplicando o estilo de modelo padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma de conector a ser criada. |
| x | float | A coordenada x da moldura do conector, em pontos. |
| y | float | A coordenada y da moldura do conector, em pontos. |
| width | float | A largura da moldura do conector, em pontos. |
| height | float | A altura da moldura do conector, em pontos. |
| createFromTemplate | boolean | True para aplicar o estilo de modelo padrão (nome não vazio, estilo simples); false para criar o conector com valores de propriedade padrão. |

**Retorna:**
[IConnector](../../com.aspose.slides/iconnector) - O recém-criado [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, aplicando o estilo de modelo padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma de conector. |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma de conector a ser inserida. |
| x | float | A coordenada x da moldura do conector, em pontos. |
| y | float | A coordenada y da moldura do conector, em pontos. |
| width | float | A largura da moldura do conector, em pontos. |
| height | float | A altura da moldura do conector, em pontos. |

**Retorna:**
[IConnector](../../com.aspose.slides/iconnector) - O recém-criado [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, opcionalmente aplicando o estilo de modelo padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma de conector. |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma de conector a ser inserida. |
| x | float | A coordenada x da moldura do conector, em pontos. |
| y | float | A coordenada y da moldura do conector, em pontos. |
| width | float | A largura da moldura do conector, em pontos. |
| height | float | A altura da moldura do conector, em pontos. |
| createFromTemplate | boolean | True para aplicar o estilo de modelo padrão (nome não vazio, estilo simples); false para criar o conector com valores de propriedade padrão. |

**Retorna:**
[IConnector](../../com.aspose.slides/iconnector) - O recém-criado [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Cria uma nova moldura de imagem contendo a imagem especificada e a adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | Especifica o tipo de forma contido em [ShapeType](../../com.aspose.slides/shapetype), exceto para todos os tipos de linhas:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | A coordenada x da moldura de imagem, em pontos. |
| y | float | A coordenada y da moldura de imagem, em pontos. |
| width | float | A largura da moldura de imagem, em pontos. |
| height | float | A altura da moldura de imagem, em pontos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | O [IPPImage](../../com.aspose.slides/ippimage) a ser exibido na moldura de imagem. |

**Retorna:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - O recém-criado [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Cria uma nova moldura de imagem contendo a imagem especificada e a insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a moldura de imagem. |
| shapeType | int | Especifica o tipo de forma contido em [ShapeType](../../com.aspose.slides/shapetype), exceto para todos os tipos de linhas:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | A coordenada x da moldura de imagem, em pontos. |
| y | float | A coordenada y da moldura de imagem, em pontos. |
| width | float | A largura da moldura de imagem, em pontos. |
| height | float | A altura da moldura de imagem, em pontos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | O [IPPImage](../../com.aspose.slides/ippimage) a ser exibido na moldura de imagem. |

**Retorna:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - O recém-criado [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Cria uma nova tabela e a adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x da tabela, em pontos. |
| y | float | A coordenada y da tabela, em pontos. |
| columnWidths | double[] | Um array de doubles representando as larguras das colunas da tabela, em pontos. |
| rowHeights | double[] | Um array de doubles representando as alturas das linhas da tabela, em pontos. |

**Retorna:**
[ITable](../../com.aspose.slides/itable) - O recém-criado [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Cria uma nova tabela e a insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde a tabela será inserida. |
| x | float | A coordenada x da tabela, em pontos. |
| y | float | A coordenada y da tabela, em pontos. |
| columnWidths | double[] | Um array de double representando as larguras das colunas da tabela, em pontos. |
| rowHeights | double[] | Um array de double representando as alturas das linhas da tabela, em pontos. |

**Retorna:**
[ITable](../../com.aspose.slides/itable) - O recém-criado [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove a forma no índice especificado da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da forma a ser removida. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Remove a primeira ocorrência da forma especificada da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a ser removida. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as formas da coleção de formas.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A forma a ser clonada. |
| x | float | A coordenada x da moldura da forma clonada, em pontos. |
| y | float | A coordenada y da moldura da forma clonada, em pontos. |
| width | float | A largura da moldura da forma clonada, em pontos. |
| height | float | A altura da moldura da forma clonada, em pontos. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - O recém-criado [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A nova forma mantém a largura e a altura da  sourceShape .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | O [IShape](../../com.aspose.slides/ishape) a ser clonado. |
| x | float | A coordenada x da moldura da forma clonada, em pontos. |
| y | float | A coordenada y da moldura da forma clonada, em pontos. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - O recém-criado [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A forma clonada mantém a posição e o tamanho originais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | O [IShape](../../com.aspose.slides/ishape) a ser clonado. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - O recém-criado [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde a forma clonada será inserida. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | O [IShape](../../com.aspose.slides/ishape) a ser clonado. |
| x | float | A coordenada x da moldura da forma clonada, em pontos. |
| y | float | A coordenada y da moldura da forma clonada, em pontos. |
| width | float | A largura da moldura da forma clonada, em pontos. |
| height | float | A altura da moldura da forma clonada, em pontos. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - O recém-criado [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A nova forma mantém a largura e a altura da  sourceShape .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde a forma clonada será inserida. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | O [IShape](../../com.aspose.slides/ishape) a ser clonado. |
| x | float | A coordenada x da moldura da forma clonada, em pontos. |
| y | float | A coordenada y da moldura da forma clonada, em pontos. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - O recém-criado [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A forma clonada mantém a posição e o tamanho originais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero onde a forma clonada será inserida. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | O [IShape](../../com.aspose.slides/ishape) a ser clonado. |

**Retorna:**
[IShape](../../com.aspose.slides/ishape) - O recém-criado [IShape](../../com.aspose.slides/ishape).