---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o gerenciador que contém o comportamento de todos os marcadores de rodapé, data/hora e número de página da apresentação.
type: docs
url: /pt/com.aspose.slides/ipresentationheaderfootermanager/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Representa o gerenciador que contém o comportamento de todos os marcadores de rodapé, data/hora e número de página da apresentação.

## Métodos

| Método | Descrição |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Altera a visibilidade de todos os marcadores de cabeçalho, incluindo mestre de notas, slides de notas e mestre de folhetos. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Altera a visibilidade de todos os marcadores de rodapé, incluindo slides mestres, slides de layout e slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Altera a visibilidade de todos os marcadores de número de página, incluindo slides mestres, slides de layout e slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Altera a visibilidade de todos os marcadores de data/hora, incluindo slides mestres, slides de layout e slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Define o texto para todos os marcadores de cabeçalho, incluindo mestre de notas, slides de notas e mestre de folhetos. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Define o texto para todos os marcadores de rodapé, incluindo slides mestres, slides de layout e slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Define o texto para todos os marcadores de data/hora, incluindo slides mestres, slides de layout e slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Altera a visibilidade dos marcadores de rodapé, data/hora e número de página para todos os slides de título e para o primeiro slide de layout. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Altera a visibilidade de todos os marcadores de cabeçalho, incluindo mestre de notas, slides de notas e mestre de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true – torna os marcadores de cabeçalho visíveis; caso contrário, os oculta. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Altera a visibilidade de todos os marcadores de rodapé, incluindo slides mestres, slides de layout e slides.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true – torna os marcadores de rodapé visíveis; caso contrário, os oculta. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade de todos os marcadores de número de página, incluindo slides mestres, slides de layout e slides.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true – torna os marcadores de número de página visíveis; caso contrário, os oculta. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade de todos os marcadores de data/hora, incluindo slides mestres, slides de layout e slides.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true – torna os marcadores de data/hora visíveis; caso contrário, os oculta. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Define o texto para todos os marcadores de cabeçalho, incluindo mestre de notas, slides de notas e mestre de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Define o texto para todos os marcadores de rodapé, incluindo slides mestres, slides de layout e slides.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Define o texto para todos os marcadores de data/hora, incluindo slides mestres, slides de layout e slides.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Altera a visibilidade dos marcadores de rodapé, data/hora e número de página para todos os slides de título e para o primeiro slide de layout. Slides de título – slides baseados no primeiro layout (independentemente do tipo desse primeiro layout).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true – torna os marcadores visíveis; caso contrário, os oculta. |