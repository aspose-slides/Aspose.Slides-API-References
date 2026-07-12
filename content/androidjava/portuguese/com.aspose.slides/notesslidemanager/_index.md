---
title: NotesSlideManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Gerenciador de slide de notas.
type: docs
url: /pt/com.aspose.slides/notesslidemanager/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Gerenciador de slide de notas.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Adicionar notas ao primeiro slide
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Salvar a apresentação no disco
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Remover notas do primeiro slide
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Salvar a apresentação no disco
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Retorna o slide de notas para o slide atual. |
| [addNotesSlide()](#addNotesSlide--) | Retorna o slide de notas para o slide atual, criando um caso não exista. |
| [removeNotesSlide()](#removeNotesSlide--) | Remove o slide de notas do slide atual. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Retorna o slide de notas para o slide atual. Retorna null se o slide não possui slide de notas. Somente leitura [INotesSlide](../../com.aspose.slides/inotesslide).

**Retorna:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Retorna o slide de notas para o slide atual, criando um caso não exista.

**Retorna:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) para este slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Remove o slide de notas do slide atual.