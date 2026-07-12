---
title: INotesSlideManager
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Administrador de diapositivas de notas.
type: docs
url: /es/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Notes slide manager.
## Métodos

| Método | Descripción |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Devuelve la diapositiva de notas para la diapositiva actual. |
| [addNotesSlide()](#addNotesSlide--) | Devuelve la diapositiva de notas para la diapositiva actual, creando una si no existe. |
| [removeNotesSlide()](#removeNotesSlide--) | Elimina la diapositiva de notas de la diapositiva actual. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Devuelve la diapositiva de notas para la diapositiva actual. Devuelve null si la diapositiva no tiene diapositiva de notas. Solo lectura [INotesSlide](../../com.aspose.slides/inotesslide).

**Devuelve:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Devuelve la diapositiva de notas para la diapositiva actual, creando una si no existe.

**Devuelve:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) para esta diapositiva.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Elimina la diapositiva de notas de la diapositiva actual.