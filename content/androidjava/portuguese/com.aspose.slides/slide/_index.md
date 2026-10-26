---
title: Slide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um slide em uma apresentação.
type: docs
url: /pt/com.aspose.slides/slide/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Representa um slide em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide. |
| [getThemeManager()](#getThemeManager--) | Retorna o gerenciador de tema sobrescrito. |
| [getSlideNumber()](#getSlideNumber--) | Retorna o número do slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Retorna o número do slide. |
| [getHidden()](#getHidden--) | Determina se o slide especificado está oculto durante a exibição de slides. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se o slide especificado está oculto durante a exibição de slides. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retorna um objeto Thumbnail Image com dimensionamento personalizado. |
| [getImage()](#getImage--) | Retorna um objeto Thumbnail Image (20% do tamanho real). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Retorna um objeto Thumbnail Image com tamanho especificado. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Retorna um objeto de imagem tiff Thumbnail com parâmetros especificados. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Retorna um objeto Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Retorna um objeto Thumbnail Image com dimensionamento personalizado. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Retorna um objeto Thumbnail Image com tamanho especificado. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva o conteúdo do slide como um arquivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva o conteúdo do slide como um arquivo SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva o conteúdo do slide como um arquivo EMF. |
| [remove()](#remove--) | Remove o slide da apresentação. |
| [getLayoutSlide()](#getLayoutSlide--) | Retorna ou define o layout slide para o slide atual. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Retorna ou define o layout slide para o slide atual. |
| [reset()](#reset--) | Redefine a posição, tamanho e formatação de cada forma que possui um protótipo em LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Permite acessar o slide de notas, adicionar e remover. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Retorna todos os comentários de slide adicionados por um autor específico. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide. Somente leitura [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Retorna:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retorna o gerenciador de tema sobrescrito. Somente leitura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retorna:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Retorna o número do slide. O índice do slide na coleção [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) é sempre igual a SlideNumber - Presentation.FirstSlideNumber. Leitura/Escrita `int`.

**Retorna:**
`int`
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Define o número do slide. O índice do slide na coleção [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) é sempre igual a SlideNumber - Presentation.FirstSlideNumber. Leitura/Escrita `int`.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | `int` |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Determina se o slide especificado está oculto durante a exibição de slides. Leitura/Escrita `boolean`.

**Retorna:**
`boolean`
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Define se o slide especificado está oculto durante a exibição de slides. Leitura/Escrita `boolean`.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | `boolean` |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Leitura/Escrita `boolean`.

**Retorna:**
`boolean`
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Define se as formas no slide mestre devem ser exibidas nos slides ou não. Leitura/Escrita `boolean`.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | `boolean` |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Retorna um objeto Thumbnail Image com dimensionamento personalizado.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Acessar o primeiro slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Criar uma imagem em escala total
>      IImage bmp = sld.getImage(1f, 1f);
>      // Salvar a imagem no disco no formato JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converte o primeiro slide da apresentação para um objeto Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Salva a imagem no formato PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Criar uma imagem em escala total
>          IImage bmp = sld.getImage(1f, 1f);
>          // Salvar a imagem no disco no formato JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Definir dimensões
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Obter valores escalados de X e Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Criar uma imagem em escala total
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Salvar a imagem no disco no formato JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scaleX | `float` | O valor pelo qual dimensionar este Thumbnail no eixo x. |
| scaleY | `float` | O valor pelo qual dimensionar este Thumbnail no eixo y. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - objeto IImage.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Retorna um objeto Thumbnail Image (20% do tamanho real).

**Retorna:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Retorna um objeto Thumbnail Image com tamanho especificado.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converte o primeiro slide da apresentação para um Bitmap com o tamanho especificado
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Salva a imagem no formato JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamanho da imagem a ser criada. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Retorna um objeto de imagem tiff Thumbnail com parâmetros especificados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opções de Tiff. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Retorna um objeto Thumbnail Image.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Retorna um objeto Thumbnail Image com dimensionamento personalizado.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Cria as opções de renderização
>      IRenderingOptions options = new RenderingOptions();
>      // Cria opções de layout para notas e comentários
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Define a posição das notas na página
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Define a posição dos comentários na página
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Define a largura da área de saída dos comentários
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Define a cor da área de comentários
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Define opções de layout para renderização
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Converte o primeiro slide da apresentação para um objeto android.graphics.Bitmap
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Salva a imagem no formato GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| scaleX | `float` | O valor pelo qual dimensionar este Thumbnail no eixo x. |
| scaleY | `float` | O valor pelo qual dimensionar este Thumbnail no eixo y. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - objetos Bitmap.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Retorna um objeto Thumbnail Image com tamanho especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamanho da imagem a ser criada. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Salva o conteúdo do slide como um arquivo SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Salva o primeiro slide como um arquivo SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva o conteúdo do slide como um arquivo SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Salva o primeiro slide como um arquivo SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opções de geração SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Salva o conteúdo do slide como um arquivo EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Salva o primeiro slide como um metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |
### remove() {#remove--}
```
public final void remove()
```

Remove o slide da apresentação.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Retorna ou define o layout slide para o slide atual. Leitura/Escrita [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Retorna ou define o layout slide para o slide atual. Leitura/Escrita [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

Redefine a posição, tamanho e formatação de cada forma que possui um protótipo em LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Permite acessar o slide de notas, adicionar e remover. Somente leitura [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Retorna:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Retorna todos os comentários de slide adicionados por um autor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor dos comentários a encontrar ou null para retornar todos os comentários. |

**Retorna:**
com.aspose.slides.IComment[] - Array de [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Une execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis.