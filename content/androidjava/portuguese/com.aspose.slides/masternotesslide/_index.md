---
title: MasterNotesSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o slide mestre para notas.
type: docs
url: /pt/com.aspose.slides/masternotesslide/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Representa o slide mestre para notas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide mestre de notas. |
| [getThemeManager()](#getThemeManager--) | Retorna o gerenciador de tema. |
| [getNotesStyle()](#getNotesStyle--) | Retorna o estilo de um texto de notas. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna uma coleção de guias de desenho para o slide mestre de notas. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna false. Boolean de leitura/gravação.

**Retorna:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna false. Boolean de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide mestre de notas. Somente leitura [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Retorna:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Retorna o gerenciador de tema. Somente leitura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retorna:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Retorna o estilo de um texto de notas. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Retorna uma coleção de guias de desenho para o slide mestre de notas. Somente leitura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Adicionando o novo guia de desenho horizontal abaixo do centro do slide
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)