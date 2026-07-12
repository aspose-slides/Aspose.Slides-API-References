---
title: MasterHandoutSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o slide mestre para folhetos.
type: docs
url: /pt/com.aspose.slides/masterhandoutslide/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Representa o slide mestre para folhetos.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide mestre de folhetos. |
| [getThemeManager()](#getThemeManager--) | Retorna o gerenciador de tema. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna uma coleção de guias de desenho para o slide mestre de folhetos. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna false. Leitura/Gravação boolean.

**Retorna:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna false. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide mestre de folhetos. Somente leitura [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Retorna:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Retorna o gerenciador de tema. Somente leitura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retorna:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Retorna uma coleção de guias de desenho para o slide mestre de folhetos. Somente leitura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Adicionando a nova guia de desenho horizontal acima do centro do slide
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)