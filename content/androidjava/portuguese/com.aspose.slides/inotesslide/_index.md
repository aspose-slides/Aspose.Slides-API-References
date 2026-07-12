---
title: INotesSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um slide de notas em uma apresentação.
type: docs
url: /pt/com.aspose.slides/inotesslide/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Representa um slide de notas em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide de notas. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Retorna um TextFrame com o texto das notas, se houver. |
| [getParentSlide()](#getParentSlide--) | Retorna um ParentSlide somente leitura [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide de notas. Somente leitura [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Retorna:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Retorna um TextFrame com o texto das notas, se houver. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Retorna um ParentSlide somente leitura [ISlide](../../com.aspose.slides/islide).

**Retorna:**
[ISlide](../../com.aspose.slides/islide)