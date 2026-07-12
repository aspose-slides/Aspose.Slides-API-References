---
title: IMasterNotesSlide
second_title: Aspose.Slides para Android via referência da API Java
description: Representa o slide mestre de notas.
type: docs
url: /pt/com.aspose.slides/imasternotesslide/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

Representa o slide mestre de notas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide mestre de notas. |
| [getNotesStyle()](#getNotesStyle--) | Retorna o estilo de um texto de notas. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna uma coleção de guias de desenho para o slide mestre de notas. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide mestre de notas. Somente leitura [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**Retorna:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

Retorna o estilo de um texto de notas. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
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