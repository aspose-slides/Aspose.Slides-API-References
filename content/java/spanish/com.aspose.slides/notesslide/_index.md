---
title: NotesSlide
second_title: Aspose.Slides para la referencia de API de Java
description: Representa una diapositiva de notas en una presentación.
type: docs
url: /es/com.aspose.slides/notesslide/
---
**Herencia:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas las interfaces implementadas:**  
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)  
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Representa una diapositiva de notas en una presentación.

## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el gestor HeaderFooter de la diapositiva de notas. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Devuelve un TextFrame con el texto de las notas si existe. |
| [getThemeManager()](#getThemeManager--) | Devuelve el gestor de tema que reemplaza. |
| [getParentSlide()](#getParentSlide--) | Devuelve la diapositiva principal. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el gestor HeaderFooter de la diapositiva de notas. Solo lectura [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Devuelve:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)

### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Devuelve un TextFrame con el texto de las notas si existe. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Devuelve el gestor de tema que reemplaza. Solo lectura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Devuelve:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Devuelve la diapositiva principal. Solo lectura [ISlide](../../com.aspose.slides/islide).

**Devuelve:**  
[ISlide](../../com.aspose.slides/islide)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura booleano.

**Devuelve:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura booleano.

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |