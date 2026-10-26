---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o gerenciador que contém o comportamento dos marcadores de rodapé, data/hora e número de página do slide mestre e de todos os marcadores filho.
type: docs
url: /pt/com.aspose.slides/masterslideheaderfootermanager/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Representa o gerenciador que contém o comportamento dos marcadores de rodapé do slide mestre, de data/hora e de número de página, além de todos os marcadores filho. Marcadores filho são marcadores contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.
## Métodos

| Método | Descrição |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Altera a visibilidade do marcador de rodapé do slide mestre e de todos os marcadores de rodapé filho. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Altera a visibilidade do marcador de número de página do slide mestre e de todos os marcadores de número de página filho. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Altera a visibilidade do marcador de data/hora do slide mestre e de todos os marcadores de data/hora filho. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Define o texto no marcador de rodapé do slide mestre e em todos os marcadores de rodapé filho. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Define o texto no marcador de data/hora do slide mestre e em todos os marcadores de data/hora filho. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de rodapé do slide mestre e de todos os marcadores de rodapé filho. Marcadores filho são marcadores contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de rodapé visíveis, caso contrário - os oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de número de página do slide mestre e de todos os marcadores de número de página filho. Marcadores filho são marcadores contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de número de página visíveis, caso contrário - os oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de data/hora do slide mestre e de todos os marcadores de data/hora filho. Marcadores filho são marcadores contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de data/hora visíveis, caso contrário - os oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Define o texto no marcador de rodapé do slide mestre e em todos os marcadores de rodapé filho. Marcadores filho são marcadores contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Define o texto no marcador de data/hora do slide mestre e em todos os marcadores de data/hora filho. Marcadores filho são marcadores contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |