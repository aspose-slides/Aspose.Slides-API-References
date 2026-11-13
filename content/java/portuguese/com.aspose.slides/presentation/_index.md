---
title: Presentation
second_title: Referência da API Aspose.Slides para Java
description: Representa uma apresentação do Microsoft PowerPoint.
type: docs
url: /pt/com.aspose.slides/presentation/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Representa uma apresentação do Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation();
>  try {
>      // Obter o primeiro slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Adicionar uma autoshape do tipo linha
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Salvar o arquivo de apresentação.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Carregar qualquer arquivo suportado em Presentation, por exemplo ppt, pptx, odp etc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Salvar o arquivo de apresentação.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Presentation()](#Presentation--) | Este construtor cria uma nova apresentação do zero. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Este construtor cria uma nova apresentação do zero. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Este construtor é o mecanismo principal para ler uma apresentação existente. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Este construtor é o mecanismo principal para ler uma apresentação existente. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Este construtor obtém o caminho do arquivo fonte a partir do qual o conteúdo da apresentação é lido. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Este construtor obtém o caminho do arquivo fonte a partir do qual o conteúdo da apresentação é lido. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Retorna ou define a data e hora que substituirão o conteúdo dos campos datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Retorna ou define a data e hora que substituirão o conteúdo dos campos datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador real de HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Obtém o gerenciador das permissões para esta apresentação. |
| [getSlides()](#getSlides--) | Retorna uma lista de todos os slides definidos na apresentação. |
| [getSections()](#getSections--) | Retorna uma lista de todas as seções de slides definidas na apresentação. |
| [getSlideSize()](#getSlideSize--) | Retorna o objeto de tamanho do slide. |
| [getNotesSize()](#getNotesSize--) | Retorna o objeto de tamanho do slide de notas. |
| [getLayoutSlides()](#getLayoutSlides--) | Retorna uma lista de todos os slides de layout definidos na apresentação. |
| [getMasters()](#getMasters--) | Retorna uma lista de todos os slides mestre definidos na apresentação. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Retorna o gerenciador mestre de notas. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Retorna o gerenciador mestre de folhetos. |
| [getFontsManager()](#getFontsManager--) | Retorna o gerenciador de fontes. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Retorna o estilo de texto padrão para formas. |
| [getCommentAuthors()](#getCommentAuthors--) | Retorna a coleção de autores de comentários. |
| [getDocumentProperties()](#getDocumentProperties--) | Retorna o objeto DocumentProperties que contém propriedades de documento padrão e personalizadas. |
| [getImages()](#getImages--) | Retorna a coleção de todas as imagens na apresentação. |
| [getAudios()](#getAudios--) | Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. |
| [getVideos()](#getVideos--) | Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Retorna as configurações de apresentação de slides para a apresentação. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Retorna a coleção de assinaturas usadas para assinar a apresentação. |
| [getCustomData()](#getCustomData--) | Retorna os dados personalizados da apresentação. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Retorna todas as partes de dados personalizados na presentaion. |
| [getVbaProject()](#getVbaProject--) | Obtém ou define o projeto VBA com macros da apresentação. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Obtém ou define o projeto VBA com macros da apresentação. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornece fácil acesso a todos os hyperlinks contidos em todos os slides da apresentação (não nos mestres, layouts, slides de notas). |
| [getViewProperties()](#getViewProperties--) | Obtém as propriedades de visualização de toda a apresentação. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representa o número do primeiro slide na apresentação |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representa o número do primeiro slide na apresentação |
| [getSensitivityLabels()](#getSensitivityLabels--) | Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. |
| [getSlideById(long id)](#getSlideById-long-) | Retorna um Slide, MasterSlide ou LayoutSlide por Id. |
| [getSourceFormat()](#getSourceFormat--) | Retorna informações sobre de qual formato a apresentação foi carregada. |
| [getMasterTheme()](#getMasterTheme--) | Retorna o tema mestre. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva todos os slides de uma apresentação em um fluxo no formato especificado. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Salva todos os slides de uma apresentação em um conjunto de arquivos que representam a marcação XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Retorna objetos Image para todos os slides de uma apresentação. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Retorna objetos Image em miniatura para os slides especificados de uma apresentação. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Retorna objetos Image em miniatura para todos os slides de uma apresentação com dimensionamento personalizado. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Retorna objetos Image em miniatura para os slides especificados de uma apresentação com dimensionamento personalizado. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Retorna objetos Image em miniatura para todos os slides de uma apresentação com tamanho especificado. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Retorna objetos Image em miniatura para os slides especificados de uma apresentação com tamanho especificado. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Salva os slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Salva os slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Salva os slides especificados de uma apresentação em um fluxo no formato especificado mantendo o número da página. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Salva os slides especificados de uma apresentação em um fluxo no formato especificado mantendo o número da página. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis em todos os slides. |
| [dispose()](#dispose--) | Libera todos os recursos usados por este objeto Presentation. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um texto. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Realça todas as correspondências da expressão regular com a cor especificada. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Substitui todas as correspondências da expressão regular pela string especificada. |
| [refreshChartsData()](#refreshChartsData--) | Recarrega os dados de todos os gráficos na apresentação a partir de suas pastas de trabalho de origem. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Recarrega os dados de todos os gráficos na apresentação a partir de suas pastas de trabalho de origem. |
### Presentation() {#Presentation--}
```
public Presentation()
```


Este construtor cria uma nova apresentação do zero. A apresentação criada possui um slide vazio.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```


Este construtor cria uma nova apresentação do zero. A apresentação criada possui um slide vazio.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opções adicionais de carregamento. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```


Este construtor é o mecanismo principal para ler uma apresentação existente.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de entrada. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```


Este construtor é o mecanismo principal para ler uma apresentação existente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de entrada. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opções adicionais de carregamento. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```


Este construtor obtém um caminho de arquivo fonte a partir do qual o conteúdo da apresentação é lido.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo de entrada. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```


Este construtor obtém um caminho de arquivo fonte a partir do qual o conteúdo da apresentação é lido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo de entrada. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opções adicionais de carregamento. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```


Retorna ou define a data e hora que substituirão o conteúdo dos campos datetime. Hora da criação deste objeto Presentation por padrão. Leitura/gravação java.util.Date.

**Retorna:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```


Retorna ou define a data e hora que substituirão o conteúdo dos campos datetime. Hora da criação deste objeto Presentation por padrão. Leitura/gravação java.util.Date.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```


Retorna o gerenciador real de HeaderFooter. Somente leitura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible is used for indicating that a slide footer placeholder is not present.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility is used for making a slide footer placeholder visible.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible is used for indicating that a slide page number placeholder is not present.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility is used for making a slide page number placeholder visible.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible is used for indicating that a slide date-time placeholder is not present.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility is used for making a slide date-time placeholder visible.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText is used for setting text to slide footer placeholder.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText is used for setting text to slide date-time placeholder.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility is used for making a master slide and all child footer placeholders visible.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility is used for making a master slide and all child page number placeholders visible.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility is used for making a master slide and all child date-time placeholders visible.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText is used for setting text to master slide and all child footer placeholders.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText is used for setting text to master slide and all child date-time placeholders.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```


Obtém o gerenciador das permissões para esta apresentação. Somente leitura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Retorna:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```


Retorna uma lista de todos os slides definidos na apresentação. Somente leitura [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the first ISlide to Blue
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Set the background with Image
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Set the picture
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Add image to presentation's images collection
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Write the presentation to disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instantiate Presentation class that represents a presentation file
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Set the transition time of 3 seconds
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Set the transition time of 5 seconds
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Apply zoom type transition on slide 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Set the transition time of 7 seconds
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```


Retorna uma lista de todas as seções de slides definidas na apresentação. Somente leitura [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 will be ended at newSlide2 and after it section2 will start
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```


Retorna o objeto de tamanho do slide. Somente leitura [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Definir o tamanho do slide das apresentações geradas para o mesmo do original
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // O método SetSize é usado para definir o tamanho do slide com escala de conteúdo para garantir ajuste
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // O método SetSize é usado para definir o tamanho do slide maximizando o conteúdo
>          // Salvar a apresentação no disco
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // tamanho de papel A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```


Retorna o objeto de tamanho do slide de notas. Somente leitura [INotesSize](../../com.aspose.slides/inotessize).

**Retorna:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```


Retorna uma lista de todos os slides de layout definidos na apresentação. Somente leitura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Você pode acessar a API alternativa para adicionar/inserir/remover/clonar slides de layout usando a propriedade IMasterSlide.LayoutSlides.

**Retorna:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```


Retorna uma lista de todos os slides mestre definidos na apresentação. Somente leitura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```


Retorna o gerenciador mestre de notas. Somente leitura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Retorna:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```


Retorna o gerenciador mestre de folhetos. Somente leitura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Retorna:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```


Retorna o gerenciador de fontes. Somente leitura [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Load presentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Load source font to be replaced
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Save the presentation
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```


Retorna o estilo de texto padrão para formas. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```


Retorna a coleção de autores de comentários. Somente leitura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Retorna:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```


Retorna o objeto DocumentProperties que contém propriedades de documento padrão e personalizadas. Somente leitura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Retorna:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```


Retorna a coleção de todas as imagens na apresentação. Somente leitura [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // creates a new presentation to which the image will be added.
>  Presentation pres = new Presentation();
>  try
>  {
>      // supposed we have the large image file we want to include into the presentation
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Let's add the image to the presentation - we choose KeepLocked behavior because we do
>          // NOT intend to access the "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Adds image to presentation
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Creates picture frame on slide 1 based on previously added image
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. Somente leitura [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public   SlideShowSettings getSlide     SlideShowSettings
```

Retorna as configurações da apresentação de slides.

**Retorna:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Retorna a coleção de assinaturas usadas para assinar a apresentação. Somente leitura [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Retorna os dados personalizados da apresentação. Somente leitura [ICustomData](../../com.aspose.slides/icustomdata).

**Retorna:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Retorna todas as partes de dados personalizados na apresentação. Somente leitura ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>   Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>   try {
>       // Iterar todas as partes XML personalizadas
>       for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>       {
>           item.remove();
>       }
>       pres.save("out.pptx", SaveFormat.Pptx);
>   }
>   finally
>   {
>       if (pres != null) pres.dispose();
>   }
> ```


**Retorna:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Obtém ou define o projeto VBA com macros da apresentação. Leitura/gravação [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Obtém ou define o projeto VBA com macros da apresentação. Leitura/gravação [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Fornece acesso fácil a todos os hyperlinks contidos em todos os slides da apresentação (não nos slides mestre, de layout ou de notas). Somente leitura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retorna:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public     ..   …      ...  ......  .
```

Obtém propriedades de visualização de toda a apresentação. Somente leitura [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retorna:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Representa o número do primeiro slide na apresentação

**Retorna:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Representa o número do primeiro slide na apresentação

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. Somente leitura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Imprimir os rótulos aplicados
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Adicionar o novo rótulo
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Obter o Id do rótulo de sensibilidade da política
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Obter o identificador do site Azure AD da política
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Retorna um Slide, MasterSlide ou LayoutSlide por Id.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | long | Id de um slide. |

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - objeto IBaseSlide.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Retorna informações sobre de qual formato a apresentação foi carregada. Somente leitura [SourceFormat](../../com.aspose.slides/sourceformat).

**Retorna:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Retorna o tema mestre. Somente leitura [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Salva todos os slides de uma apresentação em um arquivo com o formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| format | int | Formato dos dados exportados. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Salva todos os slides de uma apresentação em um stream no formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de saída. |
| format | int | Formato dos dados exportados. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções de formato adicionais. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Salva todos os slides de uma apresentação em um stream no formato especificado e com opções adicionais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de saída. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções de formato adicionais. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Salva todos os slides de uma apresentação em um conjunto de arquivos representando marcação XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | As opções de formato XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Retorna objetos Image para todos os slides de uma apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções Tiff. |

**Retorna:**
com.aspose.slides.IImage[] - objetos Image.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Retorna objetos Thumbnail Image para slides especificados de uma apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções Tiff. |
| slides | int[] | Array com posições dos slides, começando em 1. |

**Retorna:**
com.aspose.slides.IImage[] - objetos Image.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Retorna objetos Thumbnail Image para todos os slides de uma apresentação com dimensionamento customizado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções Tiff. |
| scaleX | float | O valor pelo qual dimensionar esta miniatura na direção do eixo x. |
| scaleY | float | O valor pelo qual dimensionar esta miniatura na direção do eixo y. |

**Retorna:**
com.aspose.slides.IImage[] - objetos Image.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Retorna objetos Thumbnail Image para slides especificados de uma apresentação com dimensionamento customizado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções Tiff. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| scaleX | float | O valor pelo qual dimensionar esta miniatura na direção do eixo x. |
| scaleY | float | O valor pelo qual dimensionar esta miniatura na direção do eixo y. |

**Retorna:**
com.aspose.slides.IImage[] - objetos Image.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Retorna objetos Thumbnail Image para todos os slides de uma apresentação com tamanho especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções Tiff. |
| imageSize | java.awt.Dimension | Tamanho da imagem a ser criada. |

**Retorna:**
com.aspose.slides.IImage[] - objetos Image.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Retorna objetos Thumbnail Image para slides especificados de uma apresentação com tamanho especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções Tiff. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| imageSize | java.awt.Dimension | Tamanho da imagem a ser criada. |

**Retorna:**
com.aspose.slides.IImage[] - objetos Image.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Salva slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Salva slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo criado. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções de formato adicionais. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Salva slides especificados de uma apresentação em um stream no formato especificado mantendo o número da página.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de saída. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Salva slides especificados de uma apresentação em um stream no formato especificado mantendo o número da página.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de saída. |
| slides | int[] | Array com posições dos slides, começando em 1. |
| format | int | Formato dos dados exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opções de formato adicionais. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Une execuções com formatação idêntica em todos os parágrafos em todas as formas aceitáveis em todos os slides.

### dispose() {#dispose--}
```
public final void dispose()
```

Libera todos os recursos usados por este objeto Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um texto. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Realça todas as ocorrências do texto de exemplo com a cor especificada.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // realçando todas as ocorrências separadas de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | O texto a ser realçado. |
| highlightColor | java.awt.Color | A cor para realçar o texto. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Realça todas as ocorrências do texto de exemplo com a cor especificada.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // realçando todas as ocorrências separadas de 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | O texto a ser realçado. |
| highlightColor | java.awt.Color | A cor para realçar o texto. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opções de pesquisa de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objeto de retorno de chamada para receber resultados de pesquisa [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Realça todas as ocorrências da expressão regular com a cor especificada.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // realçando todas as palavras com 10 caracteres ou mais
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

| regex | java.util.regex.Pattern | A expressão regular java.util.regex.Pattern para obter strings a destacar. |
| highlightColor | java.awt.Color | A cor para destacar o texto. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber resultados de busca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Substitui todas as ocorrências do texto especificado por outro texto especificado.

--------------------

> ```
> O exemplo de código a seguir mostra como substituir uma string especificada por outra string especificada.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Substituir todas as ocorrências separadas de 'the' por '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | A string a ser substituída. |
| newText | java.lang.String | A string que substitui todas as ocorrências de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opções de pesquisa de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber resultados de busca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Substitui todas as correspondências da expressão regular pela string especificada.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Substituir todas as palavras com 10 símbolos ou mais por '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A expressão regular java.util.regex.Pattern para obter strings a substituir. |
| newText | java.lang.String | A string que substitui todas as ocorrências das strings a serem substituídas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | O objeto de retorno de chamada para receber resultados de busca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```


Recarrega os dados de todos os gráficos na apresentação a partir de suas pastas de trabalho de origem.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public final void refreshChartsData(boolean skipFailedCharts)
```


Recarrega os dados de todos os gráficos na apresentação a partir de suas pastas de trabalho de origem.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| skipFailedCharts | boolean | Determina se o processo de atualização continua caso um gráfico falhe ao atualizar. Se verdadeiro, os gráficos que causam uma exceção são ignorados; caso contrário, a exceção é propagada. |