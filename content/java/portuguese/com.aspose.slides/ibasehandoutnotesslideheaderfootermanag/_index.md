---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Referência da API Aspose.Slides para Java
description: Representa o gerenciador que mantém o comportamento dos marcadores de posição, incluindo o marcador de posição de cabeçalho para todos os tipos de slides de folheto e notas.
type: docs
url: /pt/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Representa o gerenciador que mantém o comportamento dos marcadores de posição, incluindo o marcador de posição de cabeçalho para todos os tipos de slides de folheto e notas.

--------------------

O nome da interface original "IBaseHandoutNotesSlideHeaderFooterManager" foi truncado para "IBaseHandoutNotesSlideHeaderFooterManag" por compatibilidade COM (o comprimento do nome do tipo não pode ser superior a 39).
## Métodos

| Método | Descrição |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Obtém o valor que indica que um marcador de posição de cabeçalho está presente. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Altera a visibilidade do marcador de posição de cabeçalho do slide. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Define o texto do marcador de posição de cabeçalho do slide. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Obtém o valor que indica que um marcador de posição de cabeçalho está presente. Lê boolean.

**Retorna:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de posição de cabeçalho do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna o marcador de posição de cabeçalho visível, caso contrário - o oculta. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Define o texto do marcador de posição de cabeçalho do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |