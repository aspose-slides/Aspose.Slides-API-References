---
title: ShapeCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de formas.
type: docs
url: /pt/com.aspose.slides/shapecollection/
---
**Herança:**  
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Representa uma coleção de formas.

## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Cria um diagrama SmartArt e o adiciona ao final da coleção de formas. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o insere na coleção de formas no índice especificado. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Cria um novo quadro de Zoom de Seção e o adiciona ao final da coleção de formas. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o adiciona ao final da coleção de formas. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Cria um novo quadro de Zoom de Seção e o insere na coleção de formas no índice especificado. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Cria um novo quadro de Zoom de Resumo e o adiciona ao final da coleção de formas. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Cria um novo quadro de Zoom de Resumo e o insere na coleção de formas no índice especificado. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o adiciona ao final da coleção de formas. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o insere na coleção de formas no índice especificado. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o adiciona ao final da coleção de formas. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas no índice especificado. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Retorna o índice baseado em zero da primeira ocorrência da forma especificada na coleção. |
| [toArray()](#toArray--) | Cria e devolve um array que contém todas as formas. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e devolve um array que contém todas as formas no intervalo especificado. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Move a forma especificada para uma nova posição dentro da coleção de formas. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação padrão de modelo. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Cria uma nova forma automática retangular para hospedar conteúdo matemático e a adiciona ao final da coleção de formas. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação padrão de modelo. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com a estilização padrão de modelo. |
| [addGroupShape()](#addGroupShape--) | Cria um novo grupo de formas vazio e o adiciona ao final da coleção de formas. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Cria um novo grupo de formas, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Cria um novo grupo de formas vazio e o insere na coleção de formas no índice especificado. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Cria uma nova forma conectora com estilização padrão de modelo e a adiciona ao final da coleção de formas. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Cria uma nova forma conectora e a adiciona ao final da coleção de formas, opcionalmente aplicando a estilização padrão de modelo. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Cria uma nova forma conectora e a insere na coleção de formas no índice especificado, aplicando a estilização padrão de modelo. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Cria uma nova forma conectora e a insere na coleção de formas no índice especificado, opcionalmente aplicando a estilização padrão de modelo. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de formas no índice especificado. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Cria uma nova tabela e a adiciona ao final da coleção de formas. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Cria uma nova tabela e a insere na coleção de formas no índice especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove a forma no índice especificado da coleção de formas. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Remove a primeira ocorrência da forma especificada da coleção de formas. |
| [clear()](#clear--) | Remove todas as formas da coleção de formas. |
| [iterator()](#iterator--) | Devolve um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Devolve um iterador Java para toda a coleção. |
| [getParentGroup()](#getParentGroup--) | Obtém o objeto de forma de grupo pai para a coleção de formas. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Devolve um valor que indica se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devolve a raiz de sincronização. |
### size() {#size--}
```
public final int size()
```

Obtém o número de elementos realmente contidos na coleção. **Somente leitura**  int .

**Retorna:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Obtém o elemento no índice especificado. **Somente leitura** [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**  
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instancia a classe Presentation que representa um arquivo PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Acessa o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adiciona um gráfico com seus dados padrão
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Define o título do gráfico
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Define a primeira série para exibir valores
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Define o índice para a planilha de dados do gráfico
>      int defaultWorksheetIndex = 0;
>      // Obtém a planilha de dados do gráfico
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Exclui as séries e categorias geradas por padrão
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Adiciona novas séries
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Adiciona novas categorias
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Obtém a primeira série do gráfico
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Popula os dados da série
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Define a cor de preenchimento da série
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Obtém a segunda série do gráfico
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Popula os dados da série
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Define a cor de preenchimento da série
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Define o primeiro rótulo para exibir o nome da categoria
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Define a série para exibir o valor no terceiro rótulo
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Salva o arquivo PPTX no disco
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tipo de gráfico a ser adicionado. |
| x | float | A coordenada x do novo gráfico, em pontos. |
| y | float | A coordenada y do novo gráfico, em pontos. |
| width | float | A largura do gráfico, em pontos. |
| height | float | A altura do gráfico, em pontos. |

**Retorna:**  
[IChart](../../com.aspose.slides/ichart) - O [IChart](../../com.aspose.slides/ichart) recém-criado.
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
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
| initWithSample | boolean | Verdadeiro para inicializar o novo gráfico com dados de série de exemplo e configurações; falso para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

**Retorna:**  
[IChart](../../com.aspose.slides/ichart) - O [IChart](../../com.aspose.slides/ichart) recém-criado.
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Cria um diagrama SmartArt e o adiciona ao final da coleção de formas.

--------------------

> ```
> O exemplo a seguir mostra como adicionar uma forma inteligente em uma Apresentação PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
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
| layoutType | int | O tipo de layout do SmartArt. |

**Retorna:**  
[ISmartArt](../../com.aspose.slides/ismartart) - O [ISmartArt](../../com.aspose.slides/ismartart) recém-criado.
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
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
| index | int | O índice baseado em zero no qual inserir o novo gráfico na coleção de formas. |

**Retorna:**  
[IChart](../../com.aspose.slides/ichart) - O [IChart](../../com.aspose.slides/ichart) recém-criado.
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
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
| index | int | O índice baseado em zero no qual inserir o novo gráfico na coleção de formas. |
| initWithSample | boolean | Verdadeiro para inicializar o novo gráfico com dados de série de exemplo e configurações; falso para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

**Retorna:**  
[IChart](../../com.aspose.slides/ichart) - O [IChart](../../com.aspose.slides/ichart) recém-criado.
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

--------------------

> ```
> Este exemplo demonstra a adição de um objeto Zoom ao final de uma coleção
>  (suponha que existam pelo menos dois slides na apresentação "Presentation.pptx"):
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
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

--------------------

> ```
> Este exemplo demonstra a adição de um objeto Zoom ao final de uma coleção
>  (suponha que existam pelo menos dois slides na apresentação "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
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
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Zoom no índice especificado de uma coleção
>  (suponha que existam pelo menos dois slides na apresentação "Presentation.pptx"):
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
| index | int | O índice baseado em zero no qual inserir o quadro de Zoom. |
| x | float | A coordenada x do novo quadro de Zoom, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom, em pontos. |
| width | float | A largura do novo quadro de Zoom, em pontos. |
| height | float | A altura do novo quadro de Zoom, em pontos. |
| slide | [ISlide](../../com.aspose.slides/islide) | O [ISlide](../../com.aspose.slides/islide) referenciado pelo quadro de Zoom. |

**Retorna:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - O [IZoomFrame](../../com.aspose.slides/izoomframe) recém-criado.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Cria um novo quadro de Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Zoom no índice especificado de uma coleção
>  (suponha que existam pelo menos dois slides na apresentação "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de Zoom. |
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
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Cria um novo quadro de Zoom de Seção e o adiciona ao final da coleção de formas.

--------------------

> ```
> Este exemplo demonstra a adição de um objeto Section Zoom ao final de uma coleção
>  (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):
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
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o adiciona ao final da coleção de formas.

--------------------

> ```
> Este exemplo demonstra a adição de um objeto Section Zoom ao final de uma coleção
>  (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
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
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Cria um novo quadro de Zoom de Seção e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Section Zoom no índice especificado de uma coleção
>  (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):
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
| index | int | O índice baseado em zero no qual inserir o quadro de Zoom de Seção. |
| x | float | A coordenada x do novo quadro de Zoom de Seção, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom de Seção, em pontos. |
| width | float | A largura do novo quadro de Zoom de Seção, em pontos. |
| height | float | A altura do novo quadro de Zoom de Seção, em pontos. |
| section | [ISection](../../com.aspose.slides/isection) | O [ISection](../../com.aspose.slides/isection) referenciado pelo quadro de Zoom de Seção; deve pertencer a esta apresentação e conter ao menos um slide. |

**Retorna:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - O [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) recém-criado.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Section Zoom no índice especificado de uma coleção
>  (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de Zoom de Seção. |
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
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Cria um novo quadro de Zoom de Resumo e o adiciona ao final da coleção de formas.

--------------------

> ```
> Este exemplo demonstra a adição de um objeto Summary Zoom ao final de uma coleção
>  (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):
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
| x | float | A coordenada x do novo quadro de Resumo, em pontos. |
| y | float | A coordenada y do novo quadro de Resumo, em pontos. |
| width | float | A largura do novo quadro de Resumo, em pontos. |
| height | float | A altura do novo quadro de Resumo, em pontos. |

--------------------

Este método cria um novo Resumo de Zoom e coloca uma coleção de objetos nele para todas as seções desta apresentação.  

**Retorna:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - O [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) recém-criado.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Cria um novo quadro de Zoom de Resumo e o insere na coleção de formas no índice especificado.

--------------------

> ```
> Este exemplo demonstra a criação e inserção de um objeto Summary Zoom no índice especificado de uma coleção
>  (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):
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
| index | int | O índice baseado em zero no qual inserir o quadro de Zoom de Resumo. |
| x | float | A coordenada x do novo quadro de Zoom de Resumo, em pontos. |
| y | float | A coordenada y do novo quadro de Zoom de Resumo, em pontos. |
| width | float | A largura do novo quadro de Zoom de Resumo, em pontos. |
| height | float | A altura do novo quadro de Zoom de Resumo, em pontos. |

--------------------

Este método cria um quadro de Zoom de Resumo que agrega links de resumo para todas as seções da apresentação.  

**Retorna:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - O [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) recém-criado.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

--------------------

> ```
> O exemplo a seguir mostra como adicionar quadros de objeto OLE a slides de uma apresentação PowerPoint.
>  
>  // Instancia a classe Presentation que representa um PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Acessa o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Carrega um arquivo cel para o stream
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Cria um objeto de dados para incorporação
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Adiciona uma forma de quadro de objeto Ole
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Grava o PPTX no disco
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro OLE, em pontos. |
| y | float | A coordenada y do novo quadro OLE, em pontos. |
| width | float | A largura do novo quadro OLE, em pontos. |
| height | float | A altura do novo quadro OLE, em pontos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | As informações sobre os dados OLE incorporados ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retorna:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recém-criado.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
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

Este caminho é armazenado literalmente na apresentação. Se for especificado um caminho relativo, o arquivo ficará inacessível ao abrir a apresentação a partir de outro diretório. |

**Retorna:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recém-criado.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | float | A coordenada x do novo quadro OLE, em pontos. |
| y | float | A coordenada y do novo quadro OLE, em pontos. |
| width | float | A largura do novo quadro OLE, em pontos. |
| height | float | A altura do novo quadro OLE, em pontos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | As informações sobre os dados OLE incorporados ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Retorna:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) recém-criado.
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de objeto OLE. |
| x | float | A coordenada x do novo quadro OLE, em pontos. |
| y | float | A coordenada y do novo quadro OLE, em pontos. |
| width | float | A largura do novo quadro OLE, em pontos. |
| height | float | A altura do novo quadro OLE, em pontos. |
| className | java.lang.String | O nome da classe do objeto OLE. |
| path | java.lang.String | O caminho para o arquivo vinculado.

Este caminho é armazenado literalmente na apresentação. Se for especificado um caminho relativo, o arquivo ficará inacessível ao abrir a apresentação a partir de outro diretório. |

**Retorna:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - O quadro de objeto OLE recém-criado.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de vídeo, em pontos. |
| y | float | A coordenada y do novo quadro de vídeo, em pontos. |
| width | float | A largura do novo quadro de vídeo, em pontos. |
| height | float | A altura do novo quadro de vídeo, em pontos. |
| fname | java.lang.String | O caminho ou nome do arquivo de vídeo a ser incorporado. |

**Retorna:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - O [IVideoFrame](../../com.aspose.slides/ivideoframe) recém-criado.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
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

**Retorna:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - O [IVideoFrame](../../com.aspose.slides/ivideoframe) recém-criado.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
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
| fname | java.lang.String | O caminho ou nome do arquivo de vídeo a ser incorporado. |

**Retorna:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - O [IVideoFrame](../../com.aspose.slides/ivideoframe) recém-criado.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Cria um novo quadro de áudio vinculado a uma faixa de CD e o adiciona ao final da coleção de formas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
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

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o adiciona ao final da coleção de formas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| fname | java.lang.String | O caminho ou nome do arquivo de áudio externo a ser vinculado. |

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
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
| fname | java.lang.String | O caminho ou nome do arquivo de áudio externo a ser vinculado. |

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Instancia uma classe de apresentação que representa um arquivo de apresentação
>  Presentation pres = new Presentation();
>  try {
>      // Obtém o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Carrega o arquivo de áudio wav para o stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Adiciona o quadro de áudio
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Define o modo de reprodução e o volume do áudio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Grava o arquivo PowerPoint no disco
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x do novo quadro de áudio, em pontos. |
| y | float | A coordenada y do novo quadro de áudio, em pontos. |
| width | float | A largura do novo quadro de áudio, em pontos. |
| height | float | A altura do novo quadro de áudio, em pontos. |
| audio_stream | java.io.InputStream | Um fluxo de entrada contendo dados de áudio WAV para incorporação. |

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
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
| audio_stream | java.io.InputStream | Um fluxo de entrada contendo dados de áudio WAV para incorporação. |

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
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

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | float | A coordenada x do quadro de áudio incorporado, em pontos. |
| y | float | A coordenada y do quadro de áudio incorporado, em pontos. |
| width | float | A largura do quadro de áudio incorporado, em pontos. |
| height | float | A altura do quadro de áudio incorporado, em pontos. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Uma instância [IAudio](../../com.aspose.slides/iaudio) da coleção Presentation.Audios para incorporação. |

**Retorna:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - O [IAudioFrame](../../com.aspose.slides/iaudioframe) recém-criado.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Retorna o índice baseado em zero da primeira ocorrência da forma especificada na coleção.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A forma a ser localizada na coleção. |

**Retorna:**  
int - O índice baseado em zero da primeira ocorrência da forma na coleção de formas, se encontrada; caso contrário, \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Cria e devolve um array que contém todas as formas.

**Retorna:**  
com.aspose.slides.IShape[] - Um array de objetos [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Cria e devolve um array que contém todas as formas no intervalo especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | O índice da primeira forma a ser devolvida. |
| count | int | O número de formas a serem devolvidas. |

**Retorna:**  
com.aspose.slides.IShape[] - Um array de objetos [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Move a forma especificada para uma nova posição dentro da coleção de formas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero alvo onde a forma será colocada. |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a ser movida dentro da coleção. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero alvo onde a primeira forma especificada será colocada; as formas subsequentes seguem na ordem fornecida. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Uma ou mais instâncias [IShape](../../com.aspose.slides/ishape) a serem movidas dentro da coleção. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
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
[IAutoShape](../../com.aspose.slides/iautoshape) - O [IAutoShape](../../com.aspose.slides/iautoshape) recém-criado.
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação padrão de modelo.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma automática a ser adicionada. |
| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |
| createFromTemplate | boolean | Verdadeiro para aplicar a estilização padrão de modelo (estilo simples, texto centralizado e nome não vazio) à nova forma; falso para criar a forma com todas as propriedades definidas para seus valores padrão. |

**Retorna:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - O [IAutoShape](../../com.aspose.slides/iautoshape) recém-criado.
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Cria uma nova forma automática retangular para hospedar conteúdo matemático e a adiciona ao final da coleção de formas.

--------------------

> ```
> O exemplo a seguir mostra como adicionar Equação Matemática em uma Apresentação PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |

**Retorna:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - O [IAutoShape](../../com.aspose.slides/iautoshape) recém-criado.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação padrão de modelo.

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
[IAutoShape](../../com.aspose.slides/iautoshape) - O [IAutoShape](../../com.aspose.slides/iautoshape) recém-criado.
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com a estilização padrão de modelo.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma automática. |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma automática a ser inserida. |
| x | float | A coordenada x da moldura da forma, em pontos. |
| y | float | A coordenada y da moldura da forma, em pontos. |
| width | float | A largura da moldura da forma, em pontos. |
| height | float | A altura da moldura da forma, em pontos. |
| createFromTemplate | boolean | Verdadeiro para aplicar a estilização padrão de modelo (incluindo nome não vazio, estilo simples e texto centralizado); falso para criar a forma com todas as propriedades definidas para seus valores padrão. |

**Retorna:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - O [IAutoShape](../../com.aspose.slides/iautoshape) recém-criado.
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Cria um novo grupo de formas vazio e o adiciona ao final da coleção de formas. O quadro do grupo ajustará automaticamente para caber quaisquer formas adicionadas a ele.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instancia a classe Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Obtém o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Acessando a coleção de formas dos slides
>      IShapeCollection slideShapes = sld.getShapes();
>      // Adicionando uma forma de grupo ao slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Adicionando formas dentro do grupo de forma adicionado
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Adicionando a moldura do grupo de forma
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Grava o arquivo PPTX no disco
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - O [IGroupShape](../../com.aspose.slides/igroupshape) recém-criado.
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Cria um novo grupo de formas, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | O [ISvgImage](../../com.aspose.slides/isvgimage) contendo conteúdo vetorial a ser convertido em formas. |
| x | float | A coordenada x do quadro do grupo, em pontos. |
| y | float | A coordenada y do quadro do grupo, em pontos. |
| width | float | A largura do quadro do grupo, em pontos. |
| height | float | A altura do quadro do grupo, em pontos. |

**Retorna:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - O [IGroupShape](../../com.aspose.slides/igroupshape) recém-criado.
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Cria um novo grupo de formas vazio e o insere na coleção de formas no índice especificado. O quadro do grupo ajustará automaticamente para caber quaisquer formas adicionadas a ele.

**Parâmetro:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o grupo de formas. |

**Retorna:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - O [IGroupShape](../../com.aspose.slides/igroupshape) recém-criado.
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Cria uma nova forma conectora com estilização padrão de modelo e a adiciona ao final da coleção de formas.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instancia uma classe de apresentação que representa um arquivo PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Acessa a coleção de formas de um slide específico
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adiciona uma forma automática de elipse
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adiciona uma forma automática de retângulo
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adiciona uma forma conectora à coleção de formas do slide
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Conecta as formas usando o conector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Chama reroute que define o caminho mais curto automático entre as formas
>      connector.reroute();
>      // Salva a apresentação
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma conectora a ser adicionada. |
| x | float | A coordenada x do quadro da conectora, em pontos. |
| y | float | A coordenada y do quadro da conectora, em pontos. |
| width | float | A largura do quadro da conectora, em pontos. |
| height | float | A altura do quadro da conectora, em pontos. |

**Retorna:**  
[IConnector](../../com.aspose.slides/iconnector) - O [IConnector](../../com.aspose.slides/iconnector) recém-criado.
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma conectora e a adiciona ao final da coleção de formas, opcionalmente aplicando a estilização padrão de modelo.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma conectora a ser criada. |
| x | float | A coordenada x do quadro da conectora, em pontos. |
| y | float | A coordenada y do quadro da conectora, em pontos. |
| width | float | A largura do quadro da conectora, em pontos. |
| height | float | A altura do quadro da conectora, em pontos. |
| createFromTemplate | boolean | Verdadeiro para aplicar a estilização padrão de modelo (nome não vazio, estilo simples); falso para criar a conectora com valores de propriedade padrão. |

**Retorna:**  
[IConnector](../../com.aspose.slides/iconnector) - O [IConnector](../../com.aspose.slides/iconnector) recém-criado.
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Cria uma nova forma conectora e a insere na coleção de formas no índice especificado, aplicando a estilização padrão de modelo.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma conectora. |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma conectora a ser inserida. |
| x | float | A coordenada x do quadro da conectora, em pontos. |
| y | float | A coordenada y do quadro da conectora, em pontos. |
| width | float | A largura do quadro da conectora, em pontos. |
| height | float | A altura do quadro da conectora, em pontos. |

**Retorna:**  
[IConnector](../../com.aspose.slides/iconnector) - O [IConnector](../../com.aspose.slides/iconnector) recém-criado.
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Cria uma nova forma conectora e a insere na coleção de formas no índice especificado, opcionalmente aplicando a estilização padrão de modelo.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma conectora. |
| shapeType | int | O [ShapeType](../../com.aspose.slides/shapetype) da forma conectora a ser inserida. |
| x | float | A coordenada x do quadro da conectora, em pontos. |
| y | float | A coordenada y do quadro da conectora, em pontos. |
| width | float | A largura do quadro da conectora, em pontos. |
| height | float | A altura do quadro da conectora, em pontos. |
| createFromTemplate | boolean | Verdadeiro para aplicar a estilização padrão de modelo (nome não vazio, estilo simples); falso para criar a conectora com valores de propriedade padrão. |

**Retorna:**  
[IConnector](../../com.aspose.slides/iconnector) - O [IConnector](../../com.aspose.slides/iconnector) recém-criado.
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas.

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
| x | float | A coordenada x do quadro de imagem, em pontos. |
| y | float | A coordenada y do quadro de imagem, em pontos. |
| width | float | A largura do quadro de imagem, em pontos. |
| height | float | A altura do quadro de imagem, em pontos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | O [IPPImage](../../com.aspose.slides/ippimage) a ser exibido no quadro de imagem. |

**Retorna:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - O [IPictureFrame](../../com.aspose.slides/ipictureframe) recém-criado.
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de formas no índice especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir o quadro de imagem. |
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
| x | float | A coordenada x do quadro de imagem, em pontos. |
| y | float | A coordenada y do quadro de imagem, em pontos. |
| width | float | A largura do quadro de imagem, em pontos. |
| height | float | A altura do quadro de imagem, em pontos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | O [IPPImage](../../com.aspose.slides/ippimage) a ser exibido no quadro de imagem. |

**Retorna:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - O [IPictureFrame](../../com.aspose.slides/ipictureframe) recém-criado.
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Cria uma nova tabela e a adiciona ao final da coleção de formas.

--------------------

> ```
> Este exemplo mostra como adicionar uma tabela em uma apresentação PowerPoint.
>  
>  // Instancia a classe Presentation que representa um arquivo PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Acessa o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Define colunas com larguras e linhas com alturas
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Adiciona a forma de tabela ao slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Define o formato da borda para cada célula
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Mescla as células 1 e 2 da linha 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Adiciona texto à célula mesclada
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Salva o PPTX no disco
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | A coordenada x da tabela, em pontos. |
| y | float | A coordenada y da tabela, em pontos. |
| columnWidths | double[] | Um array de doubles representando as larguras das colunas da tabela, em pontos. |
| rowHeights | double[] | Um array de doubles representando as alturas das linhas da tabela, em pontos. |

**Retorna:**  
[ITable](../../com.aspose.slides/itable) - A [ITable](../../com.aspose.slides/itable) recém-criada.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Cria uma nova tabela e a insere na coleção de formas no índice especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a tabela. |
| x | float | A coordenada x da tabela, em pontos. |
| y | float | A coordenada y da tabela, em pontos. |
| columnWidths | double[] | Um array de doubles representando as larguras das colunas da tabela, em pontos. |
| rowHeights | double[] | Um array de doubles representando as alturas das linhas da tabela, em pontos. |

**Retorna:**  
[ITable](../../com.aspose.slides/itable) - A [ITable](../../com.aspose.slides/itable) recém-criada.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove a forma no índice especificado da coleção de formas.

**Parâmetro:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da forma a ser removida. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Remove a primeira ocorrência da forma especificada da coleção de formas.

**Parâmetro:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a ser removida. |

### clear() {#clear--}
```
public final void clear()
```

Remove todas as formas da coleção de formas.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Devolve um enumerador que itera através da coleção.

**Retorna:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Devolve um iterador Java para toda a coleção.

**Retorna:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Um java.util.Iterator para toda a coleção.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Obtém o objeto de forma de grupo pai para a coleção de formas. **Somente leitura** [IGroupShape](../../com.aspose.slides/igroupshape).

**Retorna:**  
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A forma a ser clonada. |
| x | float | A coordenada x do quadro da nova forma, em pontos. |
| y | float | A coordenada y do quadro da nova forma, em pontos. |
| width | float | A largura do quadro da nova forma, em pontos. |
| height | float | A altura do quadro da nova forma, em pontos. |

**Retorna:**  
[IShape](../../com.aspose.slides/ishape) - O [IShape](../../com.aspose.slides/ishape) recém-criado.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A nova forma mantém a largura e a altura da sourceShape.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A forma a ser clonada. |
| x | float | A coordenada x do quadro da nova forma, em pontos. |
| y | float | A coordenada y do quadro da nova forma, em pontos. |

**Retorna:**  
[IShape](../../com.aspose.slides/ishape) - O [IShape](../../com.aspose.slides/ishape) recém-criado.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A forma clonada mantém a posição e o tamanho originais.

**Parâmetro:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | O [IShape](../../com.aspose.slides/ishape) a ser clonada. |

**Retorna:**  
[IShape](../../com.aspose.slides/ishape) - O [IShape](../../com.aspose.slides/ishape) recém-criado.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a ser clonada. |
| x | float | A coordenada x do quadro da forma clonada, em pontos. |
| y | float | A coordenada y do quadro da forma clonada, em pontos. |
| width | float | A largura do quadro da forma clonada, em pontos. |
| height | float | A altura do quadro da forma clonada, em pontos. |

**Retorna:**  
[IShape](../../com.aspose.slides/ishape) - O [IShape](../../com.aspose.slides/ishape) recém-criado.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A nova forma mantém a largura e a altura da sourceShape.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | A [IShape](../../com.aspose.slides/ishape) a ser clonada. |
| x | float | A coordenada x do quadro da forma clonada, em pontos. |
| y | float | A coordenada y do quadro da forma clonada, em pontos. |

**Retorna:**  
[IShape](../../com.aspose.slides/ishape) - O [IShape](../../com.aspose.slides/ishape) recém-criado.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A forma clonada mantém a posição e o tamanho originais.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual inserir a forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | O [IShape](../../com.aspose.slides/ishape) a ser clonada. |

**Retorna:**  
[IShape](../../com.aspose.slides/ishape) - O [IShape](../../com.aspose.slides/ishape) recém-criado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devolve um valor que indica se o acesso à coleção é sincronizado (thread-safe). **Somente leitura**  boolean .

**Retorna:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devolve a raiz de sincronização. **Somente leitura**  Object .

**Retorna:**  
java.lang.Object