---
title: LayoutSlide
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um slide de layout.
type: docs
url: /pt/com.aspose.slides/layoutslide/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Representa um slide de layout.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide de layout. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Retorna o gerenciador de placeholder do slide de layout. |
| [getMasterSlide()](#getMasterSlide--) | Retorna ou define o slide mestre para um layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Retorna ou define o slide mestre para um layout. |
| [remove()](#remove--) | Remove o layout da apresentação. |
| [getThemeManager()](#getThemeManager--) | Retorna o gerenciador de tema de sobrescrita. |
| [getLayoutType()](#getLayoutType--) | Retorna o tipo de layout deste slide de layout. |
| [getDependingSlides()](#getDependingSlides--) | Retorna um array com todos os slides que dependem deste slide de layout. |
| [hasDependingSlides()](#hasDependingSlides--) | Retorna true se existir ao menos um slide que depende deste slide de layout. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna uma coleção de guias de desenho para o slide de layout. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide de layout. Somente leitura [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Retorna:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Retorna o gerenciador de placeholder do slide de layout. Somente leitura [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Retorna:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Retorna ou define o slide mestre para um layout. Leitura/gravação [IMasterSlide](../../com.aspose.slides/imasterslide).

**Retorna:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Retorna ou define o slide mestre para um layout. Leitura/gravação [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Remove o layout da apresentação.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retorna o gerenciador de tema de sobrescrita. Somente leitura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retorna:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Retorna o tipo de layout deste slide de layout. Somente leitura [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Retorna:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Retorna um array com todos os slides que dependem deste slide de layout.

**Retorna:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Retorna true se existir ao menos um slide que depende deste slide de layout. Somente leitura  boolean .

**Retorna:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser mostradas nos slides ou não. Leitura/gravação  boolean .

**Retorna:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica se as formas no slide mestre devem ser mostradas nos slides ou não. Leitura/gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Retorna uma coleção de guias de desenho para o slide de layout. Somente leitura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Adicionando o novo guia de desenho vertical à esquerda do centro do slide
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)