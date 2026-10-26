---
title: ILayoutSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um slide de layout.
type: docs
url: /pt/com.aspose.slides/ilayoutslide/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Representa um slide de layout.
## Métodos

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna HeaderFooter manager do slide de layout. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Retorna o placeholder manager do slide de layout. |
| [getMasterSlide()](#getMasterSlide--) | Retorna ou define o master slide para um layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Retorna ou define o master slide para um layout. |
| [getLayoutType()](#getLayoutType--) | Retorna o tipo de layout deste slide de layout. |
| [hasDependingSlides()](#hasDependingSlides--) | Retorna true se existir ao menos um slide que dependa deste slide de layout. |
| [getDependingSlides()](#getDependingSlides--) | Retorna um array com todos os slides que dependem deste slide de layout. |
| [remove()](#remove--) | Remove o layout da apresentação. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna uma coleção de drawing guides para o slide de layout. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Retorna HeaderFooter manager do slide de layout. Somente leitura [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Retorna:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Retorna o placeholder manager do slide de layout. Somente leitura [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Retorna:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Retorna ou define o master slide para um layout. Leitura/Gravação [IMasterSlide](../../com.aspose.slides/imasterslide).

**Retorna:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Retorna ou define o master slide para um layout. Leitura/Gravação [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Retorna o tipo de layout deste slide de layout. Somente leitura [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Retorna:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Retorna true se existir ao menos um slide que dependa deste slide de layout. Somente leitura boolean.

**Retorna:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Retorna um array com todos os slides que dependem deste slide de layout.

**Retorna:**
com.aspose.slides.ISlide[] - Array com todos os slides que dependem deste slide de layout
### remove() {#remove--}
```
public abstract void remove()
```


Remove o layout da apresentação.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Retorna uma coleção de drawing guides para o slide de layout. Somente leitura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Adicionando o novo guia de desenho vertical à esquerda do centro do slide
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)