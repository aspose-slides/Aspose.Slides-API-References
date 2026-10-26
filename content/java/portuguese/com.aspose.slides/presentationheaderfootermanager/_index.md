---
title: PresentationHeaderFooterManager
second_title: Referência da API Aspose.Slides para Java
description: Representa o gerenciador que contém o comportamento de todos os marcadores de rodapé, data-hora e número de página da apresentação.
type: docs
url: /pt/com.aspose.slides/presentationheaderfootermanager/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

Representa o gerenciador que contém o comportamento de todos os marcadores de rodapé, data-hora e número de página da apresentação.
## Métodos

| Method | Description |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Altera a visibilidade de todos os marcadores de cabeçalho, incluindo master de notas, slides de notas e master de folhetos. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Altera a visibilidade de todos os marcadores de rodapé, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Altera a visibilidade de todos os marcadores de número de página, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Altera a visibilidade de todos os marcadores de data-hora, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Define texto para todos os marcadores de cabeçalho, incluindo master de notas, slides de notas e master de folhetos. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Define texto para todos os marcadores de rodapé, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Define texto para todos os marcadores de data-hora, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Altera a visibilidade dos marcadores de rodapé, data-hora e número de página para todos os slides de título e para o primeiro slide de layout. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```


Altera a visibilidade de todos os marcadores de cabeçalho, incluindo master de notas, slides de notas e master de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de cabeçalho visíveis, caso contrário - os oculta. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```


Altera a visibilidade de todos os marcadores de rodapé, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de rodapé visíveis, caso contrário - os oculta. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```


Altera a visibilidade de todos os marcadores de número de página, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de número de página visíveis, caso contrário - os oculta. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```


Altera a visibilidade de todos os marcadores de data-hora, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de data-hora visíveis, caso contrário - os oculta. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```


Define texto para todos os marcadores de cabeçalho, incluindo master de notas, slides de notas e master de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```


Define texto para todos os marcadores de rodapé, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```


Define texto para todos os marcadores de data-hora, incluindo slides mestre, slides de layout, slides, master de notas, slides de notas e master de folhetos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```


Altera a visibilidade dos marcadores de rodapé, data-hora e número de página para todos os slides de título e para o primeiro slide de layout. Slides de título – slides baseados no primeiro slide de layout (independente do tipo desse primeiro layout).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores visíveis, caso contrário - os oculta. |