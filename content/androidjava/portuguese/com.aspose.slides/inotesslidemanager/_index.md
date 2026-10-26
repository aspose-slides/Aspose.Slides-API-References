---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Gerenciador de slide de notas.
type: docs
url: /pt/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Gerenciador de slide de notas.
## Methods

| Método | Descrição |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Retorna o slide de notas do slide atual. |
| [addNotesSlide()](#addNotesSlide--) | Retorna o slide de notas do slide atual, criando um se não existir. |
| [removeNotesSlide()](#removeNotesSlide--) | Remove o slide de notas do slide atual. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Retorna o slide de notas do slide atual. Retorna null se o slide não tem slide de notas. Somente leitura [INotesSlide](../../com.aspose.slides/inotesslide).

**Retorna:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Retorna o slide de notas do slide atual, criando um se não existir.

**Retorna:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) para este slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Remove o slide de notas do slide atual.