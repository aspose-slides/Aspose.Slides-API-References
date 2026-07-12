---
title: NotesSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um slide de notas em uma apresentação.
type: docs
url: /pt/com.aspose.slides/notesslide/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Representa um slide de notas em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide de notas. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Retorna um TextFrame com o texto das notas, se houver. |
| [getThemeManager()](#getThemeManager--) | Retorna o gerenciador de tema sobrescrito. |
| [getParentSlide()](#getParentSlide--) | Retorna o slide pai. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide de notas. Somente leitura [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Retorna:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Retorna um TextFrame com o texto das notas, se houver. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retorna o gerenciador de tema sobrescrito. Somente leitura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retorna:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Retorna o slide pai. Somente leitura [ISlide](../../com.aspose.slides/islide).

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Leitura/Gravação boolean.

**Retorna:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |