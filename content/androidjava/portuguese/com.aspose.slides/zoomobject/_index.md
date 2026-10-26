---
title: ZoomObject
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/zoomobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Representa um objeto Zoom em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getImageType()](#getImageType--) | Obtém ou define o tipo de imagem de um objeto Zoom. |
| [setImageType(int value)](#setImageType-int-) | Obtém ou define o tipo de imagem de um objeto Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Obtém ou define o comportamento de navegação na apresentação de slides. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Obtém ou define o comportamento de navegação na apresentação de slides. |
| [getShowBackground()](#getShowBackground--) | Obtém ou define o valor que especifica se o Zoom usará o plano de fundo do slide de destino. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Obtém ou define o valor que especifica se o Zoom usará o plano de fundo do slide de destino. |
| [getZoomImage()](#getZoomImage--) | Obtém ou define a imagem para o objeto Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Obtém ou define a imagem para o objeto Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Obtém ou define a duração da transição entre o Zoom e o slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Obtém ou define a duração da transição entre o Zoom e o slide. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```


Obtém ou define o tipo de imagem de um objeto Zoom. Leitura/gravação [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor padrão: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Especifica se o objeto Zoom está usando a visualização do slide ou uma imagem de capa.

**Retorna:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Obtém ou define o tipo de imagem de um objeto Zoom. Leitura/gravação [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor padrão: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Especifica se o objeto Zoom está usando a visualização do slide ou uma imagem de capa.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```


Obtém ou define o comportamento de navegação na apresentação de slides. Leitura/gravação boolean. Valor padrão: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor true da propriedade especifica o comportamento de navegação de retorno ao pai na apresentação de slides.

**Retorna:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```


Obtém ou define o comportamento de navegação na apresentação de slides. Leitura/gravação boolean. Valor padrão: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor true da propriedade especifica o comportamento de navegação de retorno ao pai na apresentação de slides.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```


Obtém ou define o valor que especifica se o Zoom usará o plano de fundo do slide de destino. Leitura/gravação boolean. Valor padrão: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```


Obtém ou define o valor que especifica se o Zoom usará o plano de fundo do slide de destino. Leitura/gravação boolean. Valor padrão: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```


Obtém ou define a imagem para o objeto Zoom. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```


Obtém ou define a imagem para o objeto Zoom. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```


Obtém ou define a duração da transição entre o Zoom e o slide. Leitura/gravação float. Valor padrão: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Se não especificado (TransitionDur = 0), usará a transição do slide de destino e os tempos associados a essa transição.

**Retorna:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```


Obtém ou define a duração da transição entre o Zoom e o slide. Leitura/gravação float. Valor padrão: 1.0f

--------------------

> ```
> o exemplo demonstra a alteração da duração da transição entre Zoom e slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Se não especificado (TransitionDur = 0), usará a transição do slide de destino e os tempos associados a essa transição.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |