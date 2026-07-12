---
title: IZoomObject
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/izoomobject/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Representa um objeto Zoom em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getImageType()](#getImageType--) | Obtém ou define o tipo de imagem de um objeto Zoom. |
| [setImageType(int value)](#setImageType-int-) | Obtém ou define o tipo de imagem de um objeto Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Obtém ou define o comportamento de navegação na apresentação. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Obtém ou define o comportamento de navegação na apresentação. |
| [getShowBackground()](#getShowBackground--) | Obtém ou define o valor que especifica se o Zoom usará o fundo do slide de destino. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Obtém ou define o valor que especifica se o Zoom usará o fundo do slide de destino. |
| [getZoomImage()](#getZoomImage--) | Obtém ou define a imagem para o objeto Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Obtém ou define a imagem para o objeto Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Obtém ou define a duração da transição entre Zoom e slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Obtém ou define a duração da transição entre Zoom e slide. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Obtém ou define o tipo de imagem de um objeto Zoom. Leitura/gravação [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor padrão: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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
public abstract void setImageType(int value)
```

Obtém ou define o tipo de imagem de um objeto Zoom. Leitura/gravação [ZoomImageType](../../com.aspose.slides/zoomimagetype). Valor padrão: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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
public abstract boolean getReturnToParent()
```

Obtém ou define o comportamento de navegação na apresentação. Leitura/gravação boolean. Valor padrão: false

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

O valor true da propriedade especifica o comportamento de navegação de retorno ao pai na apresentação.

**Retorna:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Obtém ou define o comportamento de navegação na apresentação. Leitura/gravação boolean. Valor padrão: false

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

O valor true da propriedade especifica o comportamento de navegação de retorno ao pai na apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Obtém ou define o valor que especifica se o Zoom usará o fundo do slide de destino. Leitura/gravação boolean. Valor padrão: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Obtém ou define o valor que especifica se o Zoom usará o fundo do slide de destino. Leitura/gravação boolean. Valor padrão: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract IPPImage getZoomImage()
```

Obtém ou define a imagem para o objeto Zoom. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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
public abstract void setZoomImage(IPPImage value)
```

Obtém ou define a imagem para o objeto Zoom. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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
public abstract float getTransitionDuration()
```

Obtém ou define a duração da transição entre Zoom e slide. Leitura/gravação float. Valor padrão: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
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

Se não especificado (TransitionDur = 0), será usada a transição do slide de destino e os tempos associados a essa transição.

**Retorna:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Obtém ou define a duração da transição entre Zoom e slide. Leitura/gravação float. Valor padrão: 1.0f

--------------------

> ```
> O exemplo demonstra a alteração da duração da transição entre Zoom e slide:
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

Se não especificado (TransitionDur = 0), será usada a transição do slide de destino e os tempos associados a essa transição.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |