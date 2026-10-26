---
title: INotesSlideManager
second_title: Aspose.Slides for Java Referência da API
description: Gerenciador de slides de notas.
type: docs
url: /pt/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Gerenciador de slides de notas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Retorna o slide de notas da slide atual. |
| [addNotesSlide()](#addNotesSlide--) | Retorna o slide de notas da slide atual, criando um se não houver. |
| [removeNotesSlide()](#removeNotesSlide--) | Remove o slide de notas da slide atual. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

Retorna o slide de notas da slide atual. Retorna null se o slide não tem slide de notas. Somente leitura [INotesSlide](../../com.aspose.slides/inotesslide).

**Retorna:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

Retorna o slide de notas da slide atual, criando um se não houver.

**Retorna:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) para este slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

Remove o slide de notas da slide atual.