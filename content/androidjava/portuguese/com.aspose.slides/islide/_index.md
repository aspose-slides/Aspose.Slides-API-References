---
title: ISlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um slide em uma apresentação.
type: docs
url: /pt/com.aspose.slides/islide/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Representa um slide em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide. |
| [getSlideNumber()](#getSlideNumber--) | Retorna o número do slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Retorna o número do slide. |
| [getHidden()](#getHidden--) | Determina se o slide especificado está oculto durante a apresentação de slides. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se o slide especificado está oculto durante a apresentação de slides. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retorna um objeto de imagem com dimensionamento personalizado. |
| [getImage()](#getImage--) | Retorna um objeto Thumbnail Image (20% do tamanho real). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Retorna um objeto de imagem com tamanho especificado. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Retorna um objeto Thumbnail tiff bitmap com parâmetros especificados. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Retorna um objeto Thumbnail Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Retorna um objeto Thumbnail Bitmap com dimensionamento personalizado. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Retorna um objeto Thumbnail Bitmap com tamanho especificado. |
| [getLayoutSlide()](#getLayoutSlide--) | Retorna ou define o slide de layout para o slide atual. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Retorna ou define o slide de layout para o slide atual. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Permite acessar o slide de notas, adicioná-lo e removê-lo. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Retorna todos os comentários do slide adicionados por um autor específico. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva o conteúdo do slide como um arquivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva o conteúdo do slide como um arquivo SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva o conteúdo do slide como um arquivo EMF. |
| [remove()](#remove--) | Remove o slide da apresentação. |
| [reset()](#reset--) | Redefine a posição, tamanho e formatação de cada forma que tem um protótipo no LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide. Somente leitura [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Retorna:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Retorna o número do slide. O índice do slide na coleção [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) é sempre igual a SlideNumber - 1. Leitura/Gravação int.

**Retorna:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Retorna o número do slide. O índice do slide na coleção [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) é sempre igual a SlideNumber - 1. Leitura/Gravação int.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determina se o slide especificado está oculto durante a apresentação de slides. Leitura/Gravação boolean.

**Retorna:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determina se o slide especificado está oculto durante a apresentação de slides. Leitura/Gravação boolean.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Retorna um objeto de imagem com dimensionamento personalizado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | O valor pelo qual dimensionar este Thumbnail na direção do eixo x. |
| scaleY | float | O valor pelo qual dimensionar este Thumbnail na direção do eixo y. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Retorna um objeto Thumbnail Image (20% do tamanho real).

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Retorna um objeto de imagem com tamanho especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamanho da imagem a ser criada. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Retorna um objeto Thumbnail tiff bitmap com parâmetros especificados.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opções Tiff. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Retorna um objeto Thumbnail Bitmap.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Retorna um objeto Thumbnail Bitmap com dimensionamento personalizado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| scaleX | float | O valor pelo qual dimensionar este Thumbnail na direção do eixo x. |
| scaleY | float | O valor pelo qual dimensionar este Thumbnail na direção do eixo y. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Retorna um objeto Thumbnail Bitmap com tamanho especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opções de renderização. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamanho da imagem a ser criada. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Retorna ou define o slide de layout para o slide atual. Leitura/Gravação [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Retorna:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Retorna ou define o slide de layout para o slide atual. Leitura/Gravação [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Permite acessar o slide de notas, adicioná-lo e removê-lo. Somente leitura [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Retorna:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Retorna todos os comentários do slide adicionados por um autor específico.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor dos comentários a encontrar ou null para retornar todos os comentários. |

**Retorna:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Salva o conteúdo do slide como um arquivo SVG.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de destino |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva o conteúdo do slide como um arquivo SVG.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de destino |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opções de geração de SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Salva o conteúdo do slide como um arquivo EMF.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Fluxo de destino |

### remove() {#remove--}
```
public abstract void remove()
```

Remove o slide da apresentação.

### reset() {#reset--}
```
public abstract void reset()
```

Redefine a posição, tamanho e formatação de cada forma que tem um protótipo no LayoutSlide.