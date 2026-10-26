---
title: INotesSlide
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa una diapositiva de notas en una presentación.
type: docs
url: /es/com.aspose.slides/inotesslide/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

Representa una diapositiva de notas en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva de notas. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Devuelve un TextFrame con el texto de las notas si existe. |
| [getParentSlide()](#getParentSlide--) | Devuelve un ParentSlide de solo lectura [ISlide](../../com.aspose.slides/islide). |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador HeaderFooter de la diapositiva de notas. De solo lectura [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Devuelve:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```

Devuelve un TextFrame con el texto de las notas si existe. De solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```

Devuelve un ParentSlide de solo lectura [ISlide](../../com.aspose.slides/islide).

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)